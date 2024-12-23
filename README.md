# Zebrafish-Analysis-Behavior

### Description
Zebrafish is a commonly used model organism in biomedical and pharmaceutical research, especially in behavioral studies. Many researchers use zebrafish for drug clinical trials to analyze the effects of drugs on characteristics and develop new medications. In this study, we tracked and analyzed the movement changes induced by physical factors and the MPTP drug factor using three different populations of zebrafish. Due to the complexity of zebrafish movements, tracking them is a challenge. We integrated the YOLOv7 object detection model and the StrongSORT multi-object tracking method to develop an automated zebrafish tracking system to analyze movement features.

We established motion trajectory data and collected time-series data for about 23 movement features, including distance, velocity, and various body angles. Then, we used Approximate Entropy to quantify the variations in movement features and applied a T-test to differentiate between different populations. Finally, we analyzed the movement differences between populations using the multiscale entropy method. This helps us understand the effects of drugs on zebrafish movement and evaluate the therapeutic outcomes.

---
### Detection and Tracking
<p align="center">
<img src="https://github.com/user-attachments/assets/759de8f8-9f1b-40d0-bb74-9ba1f53c7b33" width="300" height="auto">
</p>

---
### Image processing and Skeleton capture
<p align="center">
<img src="https://github.com/user-attachments/assets/a44e1e9a-cb65-424d-ba19-cc8f7aab3562" width="750" height="auto">
</p>

---
### Analysis-Behavior
#### Joint Angle Feature
- Calculate the angles of different body parts over time.
- Measure the angle changes between two points at different times.
- Track the angle changes of a single point every three frames.
- Calculate the angle between the head and the X-axis.
- Calculate the angle between the head and the Y-axis for every two frames.
<p align="center">
<img src="https://github.com/user-attachments/assets/3589bd21-5815-49d8-b773-17fcd90c4b87">
</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/aa31fb24-8984-44c1-900a-97bef5ac0a3f" width="680" height="auto">
</p>



#### Curve Feature
<p align="center">
<img src="https://github.com/user-attachments/assets/f4c1dd59-acd9-4e96-b1cf-b5b6d3fdd949" width="350" height="auto">
</p>

#### Tail Area
<p align="center">
<img src="https://github.com/user-attachments/assets/25d467a6-87af-4761-a621-0f76166cd38e" width="300" height="auto">
</p>

#### Trajectory
<p align="center">
<img src="https://github.com/user-attachments/assets/53640227-59f4-48ea-96cb-aedeaf4b171e" width="900" height="auto">
</p>

#### Approximate Entropy (ApEn)
<p align="center">
<img src="https://github.com/user-attachments/assets/c4832351-d640-4584-a1ac-768293942c5d" width="800" height="auto">
</p>

