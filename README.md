# IR_VIO_papers

## IR视觉定位
2013 Journal of Field Robotics： [Selective Combination of Visual and Thermal Imaging for Resilient Localisation in Adverse Conditions: Day and Night, Smoke and Fire](SIFT_IR_visual_localisation.pdf)

在扬尘、烟雾等复杂环境下，使用RGB和红外图像分别提取SIFT特征。对RGB相机的特征匹配结果以及红外相机的匹配结果进行比较，并取更优者用于定位。定位系统基于纯视觉，IMU仅用于比例复原，不与视觉定位进行融合。

[Perception Quality Evaluation with Visual and Infrared Cameras in Challenging Environmental Conditions](SIFT_IR_visual.pdf)

与上一篇文章属同一系列，对RGB和红外相机的比较和取舍方式的详细介绍。

[RGB-T SLAM: A Flexible SLAM Framework By Combining Appearance and Thermal Information](RGBT_SLAM.pdf)

同时使用RGB相机和红外相机分别进行特征匹配，并分别赋予红外特征与RGB特征权重，计算加权后的特征匹配相似度，以剔除较差的特征匹配，从RGB与红外特征中同时提取匹配度最优的特征。相机的定位基于Bundle Adjustment算法。

[Performance Evaluation of Feature Detectors and Descriptors Beyond the Visible](feature_performance_evaluation_IR.pdf)

对可见光图像常用的SIFT，SURF，ORB等特征在红外图像中的特征匹配表现进行了评估。作者的评估实验是通过旋转原图像并将旋转后的图像与原图像进行特征提取与匹配。

[Keyframe‐based thermal–inertial odometry](Keyframe‐based%20thermal–inertial%20odometry.pdf)

视觉部分完全基于热图像的视觉惯性定位。被用于在矿山内定位，目前不支持Loop Closure。

## IR相机的其他应用
[Multispectral Domain Invariant Image for Retrieval-based Place Recognition](Place_recognition.pdf)

利用CycleGAN域迁移(Domain Adaptive)特性的热图像地点识别。

[Classifying Emotions in Rehabilitation Robotics Based on Facial Skin Temperature](Classifying_emotions_in_rehabilitation_robotics_based_on_facial_skin_temperature.pdf)

利用面部热图像进行情感检测，被用于中风患者康复机器人。

