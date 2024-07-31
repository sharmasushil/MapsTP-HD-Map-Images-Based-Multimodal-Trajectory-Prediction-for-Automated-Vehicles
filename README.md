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

## Our Overview 📑
Our Overview: Segment anything model extracts bounding box info. GNN processes the graph for spatial feature relations, predicting ego vehicle trajectory with LSTM layers.

<img src="https://github.com/sharmasushil/Optimizing-Ego-Vehicle-Trajectory-Prediction-The-Graph-Enhancement-Approach/assets/70905483/ad96c3e6-42d0-4553-8aea-fbcfac442e37" width ="650">


## Our proposed architecture ⛓️
Semantic segmentation derives bounding box coordinates and mask details from a BEV, this information is then utilized by a DNN to inform a KNN, which establishes connections between the boxes to create a graph. A GNN, enhanced with positional encoding, captures spatial features, while LSTM layers integrate temporal dynamics for the prediction of the ego vehicle’s trajectory.

<img src="https://github.com/sharmasushil/Optimizing-Ego-Vehicle-Trajectory-Prediction-The-Graph-Enhancement-Approach/assets/70905483/140fda00-482d-448f-bc57-663990356165" width = "650">

## CARLA Results Visualization 📈

Qualitative results: Left depicts a random frame from the Carla simulation, and the middle illustrates the GNN graph structure
with nodes and edges. On the right, the predicted trajectory of the ego vehicle is plotted over a 5-step horizon, where the starting step is
marked in blue, and the predicted trajectory is represented in red.


<img src="https://github.com/sharmasushil/Optimizing-Ego-Vehicle-Trajectory-Prediction-The-Graph-Enhancement-Approach/assets/70905483/b97c4dc1-cfe0-400d-a285-cc26e894ab6b" width ="650">

## Citation 👇🏻
If you use this dataset in your research or work, we kindly request that you cite the following paper:
