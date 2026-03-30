### Turning Geospatial Data into Actionable Insights for Sustainable Plantation Monitoring

Detecting individual palm trees from high-resolution imagery is not just a computer vision problem — it’s a step toward more efficient, data-driven, and sustainable plantation management.

In this project, I developed an end-to-end deep learning pipeline to automatically detect palm trees using YOLOv26, starting from raw geospatial imagery to model deployment. The workflow integrates GIS-based preprocessing with modern object detection techniques to handle large-scale spatial data.

This project demonstrates how Geospatial AI can bridge the gap between satellite data and real-world decision-making.

⚙️ Workflow in short:
- Image tiling in QGIS (Deepness plugin)
https://plugins.qgis.org/plugins/deepness/
- Labeling & dataset prep in Roboflow
https://roboflow.com/
- Model training & evaluation (YOLO26m)
https://docs.ultralytics.com/models/yolo26/#detection-coco
https://docs.ultralytics.com/usage/cfg/#augmentation-settings
- Implementation of the model on new data

📊 Results
- Stable convergence during training and validation
- Precision & Recall > 0.85
- mAP@50 > 0.90

These results indicate that the model performs well in detecting palm trees even in complex and dense plantation environments.

![image alt](https://github.com/diniyrti/YOLO26-Palm-Tree-Detection/blob/main/images/results.png)

![image alt](https://github.com/diniyrti/YOLO26-Palm-Tree-Detection/blob/main/images/sample_inference.jpg)
