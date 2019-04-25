# Binocular-Light-Field-Imaging-Data

This repository provides the Binocular-LF database developed in the paper 
### “Binocular Light-Field: Imaging Theory and Occlusion-Robust Depth Perception Application”.

![framework](/imgs/framework.png)

The binocular-LF database contains synthetic samples rendered by applying the _Blender add-on setup_ from Honauer et al. [lightfield_benchmark_accv_2016](http://lightfield-analysis.net/benchmark/paper/lightfield_benchmark_accv_2016.pdf) and real-world scenes captured by a binocular-LF system using the _Lytro Illum camera_. The number of labels is __64__.

Furthermore, a simple synthetic scene with only three parallel planes is presented for simulation experiment. It is named __“training_16”__. The number of labels is __16__.

* __Synthetic Samples__ 
![synthetic samples](/imgs/synthetic_data.png)

* __Training_16__ 
![training](/imgs/training_16.png)

* For each synthetic sample, we provide:
1. __Raw_LF_data folder:__ the Left LF data and the Right LF data in the resolution _13x13x512x512x3_.
2. __LF_GT_data folder:__ the Left LF and Right LF ground truth depth maps and disparity maps in the .pfm format; the camera settings and disparity ranges in the .cfg format.
3. __SV_GT_Disp folder:__ the ground truth disparity map with sub-pixel scale.
4. __LF_GT_Occlusion:__ the LF ground truth occlusion map.
5. __LF_GT_Occlusion_dilate:__ the LF ground truth occlusion map with dilating_param = 1.
6. __SV_GT_Occlusion:__ the SV ground truth occlusion map.

* __Real-World Scenes__ 
![real-world](/imgs/real-world_data.png)

* For each real-world scene, we provide the Left LF data and the Right LF data in the resolution _9x9x400x600x3_.

The database will be enlarged in the future.
