# E2E 
### E2E: Targetless Automatic Edge-2-Edge extrinsic calibration algorithm.


### 📬 Contact
If you have any questions, please feel free to contact: Weijie Zhu [zwj@seu.edu.cn]

## 1. Introduction
### E2E is a targetless, automatic edge-to-edge calibration method based solely on laser reflectivity, aimed at enhancing calibration accuracy and feature consistency in the LiDAR-Camera calibration (LCC) task. Traditional methods primarily focus on the 3D information of LiDAR point clouds for feature detection. In contrast, the proposed method leverages the superior capabilities of laser reflectivity to perceive color, depth, and material properties. This strategy enables robust edge feature consistency in 2D, thereby enhancing overall calibration accuracy.

<div align="center">
    <img src="pics/Intro/overview.png" width = 100% >
</div>

## 2. Experiment Result of Natural Scenes
### The experimental scenes, illustrated in below figure, include eight randomly selected natural environments such as corridors, walls, buildings, and parking area. 
<div align="center">
    <img src="pics/Intro/scene.png" width = 100% >
</div>

### The calibration result of overlapping map between the laser refectivity and original image.
<div align="center">
    <img src="pics/Intro/result.png" width = 100% >
</div>
