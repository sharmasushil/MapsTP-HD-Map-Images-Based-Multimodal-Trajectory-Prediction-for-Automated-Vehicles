<p align="center">
    <h4 align="center"><a href="https://library.imaging.org/ei/articles/36/17/AVM-115">📑 Article</a>  | <a href="https://drive.google.com/drive/folders/1JPb64bGV88ymZkJrUBaKQg12tToZVF7T?usp=sharing">📂 Dataset</a> | <a href="https://docs.google.com/presentation/d/1R7yt0BJVVkZIXfyz3MIcuNJkGIw8Z_Vk/edit#slide=id.p1">🎙️Talk</a>    </h4> 
</p>

# MapsTP: HD Map Images Based Multimodal Trajectory Prediction for Automated Vehicles 🚗

Abstract: Predicting ego vehicle trajectories remains a critical challenge, especially in urban and dense areas
due to the unpredictable behaviours of other vehicles and pedestrians. Multimodal trajectory prediction
enhances decision-making by considering multiple possible future trajectories based on diverse sources of
environmental data. In this approach, we leverage ResNet-50 to extract image features from high-definition
map data and use IMU sensor data to calculate speed, acceleration, and yaw rate. A temporal probabilistic
network is employed to compute potential trajectories, selecting the most accurate and highly probable
trajectory paths. This method integrates HD map data to improve the robustness and reliability of trajectory
predictions for autonomous vehicles.

## Our proposed architecture ⛓️

Our proposed architecture: HD Map Integration for Vehicle Trajectory Planning. The process
begins with the feature extractor analyzing these inputs to create image features. These features are then
analyzed by a probabilistic network, which evaluates multiple potential trajectories and assigns probabilities to
each.

<img src="https://github.com/user-attachments/assets/77be7331-d7e2-4e62-baff-f6d4d9e1aa18" width ="650">




