# 🐷 Pig Behavior Monitoring Dataset

## 🔎 Overview

<p align="justify">
The Pig Behavior Monitoring Dataset provides annotated data for developing and evaluating computer-vision methods that monitor group-housed pigs in commercial barns. It comprises two complementary subsets: <b>Pig Multi-Behavior Detection</b>, which provides annotated images for five common pig behaviors—standing, side-lying, prone lying, climbing, and feeding—and <b>Individual Tracking</b>, which provides video sequences with frame-level identity annotations for tracking individual pigs over time. The dataset supports research on pig behavior detection and recognition, multi-object tracking, and individual-level analysis under practical farm conditions, including animal interactions, occlusion, and variable illumination.
</p>

<p align="justify">
<b>To access the dataset used in this study, please download all files from <a href="https://drive.google.com/file/d/10x8II3h6uW4UMsuyFcvNknnTdt-QEour/view?usp=sharing">Google Drive</a>.</b>
</p>

## 🗂️ Directory Structure

```text
pig-behavior-monitoring-dataset/
├── pig_multi_behavior_detection/
│   ├── images/
│   │   ├── 000000001968.jpg
│   │   ├── 000000001969.jpg
│   │   └── ...
│   └── annotations/
│       ├── 000000001968.txt
│       ├── 000000001969.txt
│       └── ...
└── pig_multi_behavior_tracking/
    ├── videos/
    │   ├── video_1.mp4
    │   ├── video_2.mp4
    │   └── ...
    └── annotations/
        ├── video_1_GT.txt
        ├── video_2_GT.txt
        └── ...
```

### 📁 Dataset Contents

**Pig Multi-Behavior Detection**

- `pig_multi_behavior_detection/images/` contains the image files.
- `pig_multi_behavior_detection/annotations/` contains the corresponding annotation files.

**Individual Tracking**

- `individual_tracking/videos/` contains the video sequences.
- `individual_tracking/annotations/` contains the corresponding tracking annotation files.

## ⬇️ Dataset Download

The dataset is publicly available on [Google Drive](https://drive.google.com/file/d/10x8II3h6uW4UMsuyFcvNknnTdt-QEour/view?usp=sharing).

## 📬 Contact

- shiwenhui@webmail.hzau.edu.cn
- cjs@webmail.hzau.edu.cn

## ⚖️ License

This dataset is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

