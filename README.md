# watchpose
datasets and source codes of watchpose

## Dataset
Due to limited space, here we only provide testing data and their ground truth. If you want full training data, please send us email: yangcong955@126.com

2. At present, it is only open to non-profit institutions such as schools and research institutes, and not to companies and enterprises. Any other use beyond that is prohibited. To ensure the continuous development of this project, we demand responsible use of the data you are about to acquire.
3. Without permission, it is not allowed to forward, publish or distribute this dataset or its subsets to any organization or individual in any ways or by any means.
4. Any copy and sharing requests should be forwarded to the official contact email.
5. Please cite our paper if FatigueView dataset is useful to your research:
  1. Cong Yang, Zhengyu Yang, Weiyu Li and John See. FatigueView: A Multi-Camera Video Dataset for Vision-based Drowsiness Detection. arXiv preprint arXiv:2000.00000, 2021.

data structure:

obj1
   -- small_distance: around 50cm camear-object distance with normal marker
      -- img_0_99.jpg: original image
      -- makloca_0_99.txt: marker location (four corners) within the image
      -- tran_0_99.txt: rotation and translation
   -- big _distance: around 100-200cm camera-object distance with nestmarker
      -- img_0_99.jpg: original image
      -- makloca_0_99.txt: marker location (four corners) within the image
      -- tran_0_99.txt: rotation and translation
