# WatchPose

WatchPose is a simple but efficient camera pose data collection method, WatchPose, to improve the generalization and robustness of camera pose regression models. Specifically, WatchPose tracks nested markers and visualizes viewpoints in an Augmented Reality- (AR) based manner to properly guide users to collect training data from broader camera-object distances and more diverse views around the objects.

## Citation
@article{Yang2020watchpose,
  title={WatchPose: A View-Aware Approach for Camera Pose Data Collection in Industrial Environments},
  author={Yang, Cong and Simon, Gilles and See, John and Berger, Marie-Odile and Wang, Wenyong},
  journal={Sensors},
  volume={20},
  number={11},
  pages={3045},
  year={2020},
  publisher={Multidisciplinary Digital Publishing Institute}
}

## Dataset: Industral10

1. Due to space limitation in github, here we only provide testing data and their ground truth. If you want full training data, please send us email: yangcong955@126.com
2. At present, it is only open to non-profit institutions such as schools and research institutes, and not to companies and enterprises. Any other use beyond that is prohibited. To ensure the continuous development of this project, we demand responsible use of the data you are about to acquire.
3. Without permission, it is not allowed to forward, publish or distribute this dataset or its subsets to any organization or individual in any ways or by any means.
4. Please cite our paper if Industral10 dataset is useful to your research

data structure:

- obj1
   -- small_distance: around 50cm camear-object distance with normal marker
      -- img_0_99.jpg: original image
      -- makloca_0_99.txt: marker location (four corners) within the image
      -- tran_0_99.txt: rotation and translation
   -- big _distance: around 100-200cm camera-object distance with nestmarker
      -- img_0_99.jpg: original image
      -- makloca_0_99.txt: marker location (four corners) within the image
      -- tran_0_99.txt: rotation and translation
