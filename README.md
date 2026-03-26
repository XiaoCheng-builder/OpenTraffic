# OpenTraffic
OpenTraffic is a next‑generation open‑source ecosystem for intelligent traffic perception, designed to bridge the gap between cutting‑edge vision research and real‑world traffic analytics. It delivers a unified, modular foundation that empowers researchers, engineers, and urban mobility innovators to build, benchmark, and deploy high‑performance traffic understanding systems with unprecedented efficiency.

Powered by state‑of‑the‑art vision models and a flexible pipeline architecture, OpenTraffic abstracts away the complexity of multi‑object tracking, anomaly detection, and scene quality assessment, enabling teams to focus on solving domain‑specific challenges. Its components are engineered for scalability—from edge cameras to cloud clusters—and come with reproducible benchmarks, interactive annotation tools, and seamless integration paths.

With OpenTraffic, what once required months of custom development can now be assembled in days. It is not merely a collection of models, but a complete production‑ready framework that accelerates the entire lifecycle: data generation, model training, real‑time inference, and system evaluation. Whether you are managing a single intersection or a city‑wide network, OpenTraffic provides the building blocks to turn visual data into actionable traffic intelligence—open, transparent, and built for the future.



## Introduction
**OpenTraffic** introduces a novel family of **fully open-source** Vision Small Models, which deliver **state-of-the-art performance** at a significantly lower cost.

### Visual object detection

- [cars_detection](https://github.com/XiaoCheng-builder/YOLO-ALG/tree/cars-detection): Vehicle model recognition using YOLOv11 for multi-class object detection.

- [non-motor-vehicle](https://github.com/XiaoCheng-builder/YOLO-ALG/tree/non-motor-vehicle): Non-motorized vehicle detection for traffic monitoring using YOLOv11.

- [snow_detection](https://github.com/XiaoCheng-builder/YOLO-ALG/tree/main/snow_detection): Multi‑feature fusion road snow detection system supporting real‑time video, snow level assessment, and lane visibility analysis.

### Target tracking

- [vehicle_flow_detection](https://github.com/XiaoCheng-builder/YOLO-ALG/blob/main/vehicle_flow_detection): Multi‑object tracking and traffic flow counting system based on YOLOv11 + DeepSORT, supporting counting line crossing statistics, ROI‑based entry/exit counting, and vehicle speed analysis.

### Traffic Anomaly Detection

- [integrated_traffic_system_v3_yolo](https://github.com/XiaoCheng-builder/YOLO-ALG/tree/main/integrated_traffic_system_v3_yolo): YOLOv11 + DeepSORT based unified system for detecting retrograde, queue, conflict, red‑light violation, and timing anomalies in traffic scenes. Supports vehicle/pedestrian detection, world‑coordinate transformation, and multi‑task visualization.

- [traffic_light_timing_validation](https://github.com/XiaoCheng-builder/YOLO-ALG/tree/main/traffic_light_timing_validation): YOLO‑based traffic light timing validation system supporting duration checks, sequence verification, multi‑direction synchronization, and anomaly detection (flicker, stuck, multiple lights on). Includes interactive region setup and detailed report generation.

### Image Segmentation

- [water_detection](https://github.com/XiaoCheng-builder/YOLO-ALG/tree/main/water_detection): Road waterlogging detection system supporting traditional vision methods and deep learning segmentation, with water level assessment and real‑time video inference.

### Image Classification

- [image_quality_classification](https://github.com/XiaoCheng-builder/YOLO-ALG/tree/main/image_quality_classification): ResNet34‑based image quality classification system for detecting blurred, clear, low‑light, occluded, and overexposed images. Supports training, inference, and data generation from video.

This initiative is jointly established and co-developed with the following research institutions:

- Tsinghua University  
- Beijing Jiaotong University  
- Beijing University of Posts and Telecommunications


## Contact
If you are interested in discussion or joining us, please send emails to 1753390706@qq.com.
