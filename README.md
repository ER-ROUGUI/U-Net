# U-Net

# Autonomous Vehicle Road Segmentation using U-Net

## Context
In the field of autonomous vehicles, environment perception is a crucial step to ensure safe and efficient driving (prior to the localization and navigation stages). One of the fundamental aspects of this perception is image segmentation, which allows for the identification and classification of various road elements, such as road markings (especially lane lines), other vehicles, pedestrians, traffic signs, and much more.

As an engineer passionate about artificial intelligence applied to robotics and autonomous systems, I focused on using Convolutional Neural Networks (CNNs), specifically the U-Net architecture, to perform road segmentation.

**Lane and Boundary Detection:** 
By correctly identifying the perimeter of the road to consistently stay in the correct lane, this visual data is designed to be fused with LiDAR data (3D Point Clouds >> e.g., **Velodyne**, which I use in other projects). This sensor fusion enables the autonomous vehicle to better track its trajectory and strictly comply with traffic rules.

In this project, I concentrated on image segmentation using a U-Net network that can later be integrated into a broader sensor fusion system, ultimately improving the overall perception capabilities of the autonomous vehicle.

## Objective
The main goal of this project is to develop an image segmentation model for autonomous cars capable of accurately identifying the road perimeter. This segmentation aims to enhance the vehicle's perception and optimize real-time decision-making (during the localization and navigation stages). By eventually combining this visual information with data from other sensors like LiDAR, IMU, and radar, we can significantly strengthen the system's understanding of the driving environment.

## Sources & References

**YouTube Tutorials & Demonstrations:**
* [Video Reference 1](https://www.youtube.com/watch?v=azM57JuQpQI&list=PLZsOBAyNTZwbR08R959iCvYT3qzhxvGOE)
* [Video Reference 2 (Shorts)](https://www.youtube.com/shorts/vtcX16GF62Y)

**Articles & Literature:**
* [U-Net for Semantic Segmentation on Unbalanced Aerial Imagery](https://towardsdatascience.com/u-net-for-semantic-segmentation-on-unbalanced-aerial-imagery-3474fa1d3e56/)

**Dataset:**
* [Semantic Segmentation Makassar-IDN Road Dataset](https://www.kaggle.com/datasets/nublanazqalani/semantic-segmentation-makassaridn-road-dataset)
