# Improving DroTrack
This project was a collaborative effort by Alexandre St-Aubin, Alexis Viau-Cardinal, and Rafid Saif, in the context of a final project for the course COMP 558 at McGill University in the Fall 2024 semester. The original repository can be found [here](https://github.com/AlexisViauCardinal/COMP558-FinalProject), and the project website [here](https://alestaubin.github.io/Improving_Drotrack/). The project report can be found [here](ImprovingDroTrack.pdf).
## Abstract 
The increased deployment of Unmanned Aerial Vehicles (UAVs) has amplified the demand for robust object tracking methods, essential for applications like search and rescue, surveillance, and agriculture. 
State-of-the-art feature-based trackers such as DroTrack integrate optical flow and segmentation to achieve real-time performance in drone-based scenarios. 
However, they suffer from significant limitations, including poor resilience to occlusion, unreliable recovery, and inefficient handling of size and orientation changes. 
In this work, we propose an improved tracking pipeline that combines feature-based tracking with DroTrack’s optical flow framework, enhancing its robustness to occlusions, high object velocity, and orientation changes.
Our experiments on the VisDrone dataset compare our approach against DroTrack and other baseline methods, evaluating tracking accuracy and runtime performance. 
Results demonstrate that our method improves tracking robustness, particularly in scenarios with occlusion and fast object speeds, albeit at the cost of reduced frame rate. 


### My Contributions
- Implemented ORB for faster feature extraction than SIFT.
- Implemented the testing scripts and analyzed the results.
- Did a review of the litterature on feature-based object tracking, and in particular, drone-based tracking.
- Implemented the project website.
