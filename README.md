<p align="center">
    <h4 align="center"><a href="https://arxiv.org/pdf/2407.05811v2">📑 Article</a> |  <a href="https://docs.google.com/presentation/d/1R7yt0BJVVkZIXfyz3MIcuNJkGIw8Z_Vk/edit#slide=id.p1">🎙️Talk</a>    

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

## Results 
As illustrated in Figure below, on the left side, we utilize HD map or raster map data from Nuscene. The HD map
provides detailed and precise information regarding the environment surrounding the vehicle. This map information includes accurate lane markings, road boundaries, traffic signs, and other objects present in the scene. In the middle, the multi-model trajectory prediction is depicted in red. This visualization showcases multiple
possible trajectories, each representing a potential path that a vehicle might take, considering various factors
such as speed and direction. It provides valuable insights into the diverse range of paths that vehicles could
follow in different scenarios. Note that, our model’s trajectory predictions are well-represented, as evidenced
by the ground truth depicted on the right-hand side in green. This alignment with ground truth demonstrates
the efficacy of our model in accurately forecasting vehicle trajectories. In Figure, we consider the highest
probability to predict the trajectory, but we also take into account other probabilities for different scenarios.

<img src="https://github.com/user-attachments/assets/f1dbbf7b-1710-41e3-9a23-2436fa1a9e06" width ="650">

## Citation👇🏻

If you use this dataset in your research or work, we kindly request that you cite the following paper:

```BibTeX
@article{sharma2024mapstp,
  title={MapsTP: HD Map Images Based Multimodal Trajectory Prediction for Automated Vehicles},
  author={Sharma, Sushil and Das, Arindam and Sistu, Ganesh and Halton, Mark and Eising, Ciar{\'a}n},
  journal={arXiv preprint arXiv:2407.05811},
  year={2024}
}
```


