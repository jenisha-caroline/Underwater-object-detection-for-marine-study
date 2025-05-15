UNDERWATER-OBJECT-DETECTION-FOR-MARINE-STUDY.

OVERVIEW:

Underwater environments present unique challenges for object detection due to factors like low visibility, turbidity, and lighting conditions. This project aims to address these challenges by implementing and comparing various state-of-the-art models, including YOLOv5, YOLOv8, EfficientDet, and Detectron2, to determine the most effective approach for underwater object detection

DATASETS:

Roboflow Aquarium Dataset: Contains 638 images with categories like fish, jellyfish, and stingrays.

Brackish Underwater Image Dataset: Comprises 14,674 images featuring crabs, small fish, and shrimp.

TrashCan1.0 Dataset: Includes 7,212 images categorized into bio, trash, and unknown.

Trash-ICRA19 Dataset: Features 5,700 images with labeled bounding boxes for trash, biological objects, and ROVs.

HICRD Dataset: Offers 8,003 images, including restored reference images for underwater image restoration.

MODEL ARCHITECTURES:

YOLOv5: Known for its speed and efficiency in real-time applications.

YOLOv8: An advanced version of YOLO with improved accuracy and flexibility.

EfficientDet: Optimized for both accuracy and computational efficiency.

Detectron2: A modular and flexible object detection library.

EVALUATION:
ko
Model performance is evaluated using metrics such as mean Average Precision (mAP), Intersection over Union (IoU), and inference time. For instance, YOLOv8 achieved an mAP of 98.20% on the Brackish-Dataset, while EfficientDet reached 98.56% mAP with a modified BiSkFPN mechanism.

CONCLUSION:

Underwater object detection has emerged as a pivotal technology in marine studies, facilitating the monitoring and analysis of marine ecosystems, resource management, and environmental conservation. The integration of deep learning techniques, particularly convolutional neural networks (CNNs), has significantly enhanced the accuracy and efficiency of object detection in challenging underwater environments.

Despite the advancements, several challenges persist, including the inherent complexities of underwater imagery such as low visibility, turbidity, and lighting variations. These factors can degrade image quality and complicate the detection process. Moreover, the scarcity of annotated underwater datasets limits the training of robust models capable of generalizing across diverse marine conditions.

Future research should focus on developing more sophisticated models that can effectively handle the unique characteristics of underwater environments. This includes improving model robustness to varying lighting conditions, enhancing the detection of small and clustered objects, and creating comprehensive datasets that encompass a wide range of marine species and scenarios. Additionally, the incorporation of attention mechanisms and multi-scale features has shown promise in addressing some of these challenges.
