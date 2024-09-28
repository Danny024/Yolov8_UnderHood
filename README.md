# Yolov8_UnderHood
Examining Yolov8 under the hood and creating our own architecture from scratch. <br>

The You-Only-Look-Once is foundational single stage CNN model that is a mostly best choice for real time implementation because of its balance between speed and accuracy. It has a very high inference time making it suitable for real time application and embedded system with  low computational resources. <br
In the python notebook I built a foundational nano model of Yolov8 from scratch. This gives one the freedom to execute regularization techniques such as Elastic Weight Consolidation (EWC) and some other strategies to mitigate castatrophic forgetting to allow for continuous learning which is not a default feature of most Computer vision Foundational models.

