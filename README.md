# Pose-Estimation
pose estimation with Keypoint-RCNN and YOLOv8

In this project, I intend to perform pose estimation using the keypoint-RCNN and YOLOv8 networks on a CCTV dataset. I will showcase the results of these two networks. The keypoint-RCNN network is a two-stage model for pose estimation and object detection, and it is based on keypoints. The architecture of this network is as follows:

![Keypoint-RCNN-neural-network-structure-mainly-consists-of-feature-extractor-region](https://github.com/ahmadrezabaqerzade/Pose-Estimation/assets/94822419/ed05898c-1c33-44a9-9e13-d0143a25bc3f)

The YOLOv8 network is also a single-stage network and is used for both pose estimation and object detection. The structure of this network is as follows:


![1_YkkGwFBksWVbm4GmZfSDsg](https://github.com/ahmadrezabaqerzade/Pose-Estimation/assets/94822419/69d26aa3-198e-4093-a99a-c5d07d0d556b)

The CCTV dataset consists of 700 images captured from surveillance cameras and is used for pose estimation and object detection on humans. I have divided this dataset into training, validation, and test sets, with 490 images for training, 105 images for validation, and 105 images for testing. The annotations for these three sets are provided in CSV files:

train_df: train annotation 

valid_df: validation annotation 

test_df: test annotation 

dataset link = <https://www.kaggle.com/datasets/jonathannield/cctv-human-pose-estimation-dataset>




https://github.com/ahmadrezabaqerzade/Pose-Estimation/assets/94822419/c0439fbc-b7b3-4983-8ac7-d79a02bef881

