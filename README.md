# 🐷 Pig Behavior Monitoring Dataset

The Pig Behavior Monitoring Dataset is an annotated resource designed to support the development and evaluation of computer-vision methods for automated monitoring of group-housed pigs in commercial barn environments. It comprises two complementary subsets: **Pig Multi-Behavior Detection**, which provides annotated images for five common pig behaviors—standing, side-lying, prone lying, climbing, and feeding—and **Individual Tracking**, which provides video sequences with frame-level identity annotations for tracking individual pigs over time. The dataset supports research on pig behavior detection and recognition, multi-object tracking, and individual-level analysis under practical farm conditions, including animal interactions, occlusion, and variable illumination.

## 🔎 Overview

<!-- A dataset overview figure will be added here. -->
![Pig behavior dataset overview](./overview.png)
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

The stable dataset download link will be provided here when Version 1.0.0 is publicly released.

## 📬 Contact

- shiwenhui@webmail.hzau.edu.cn
- cjs@webmail.hzau.edu.cn


## 📝 Citation

If you use this dataset in your research, please cite:

```bibtex
@article{ShiPigBehaviorMonitoring,
    author    = {Wenhui Shi and Jusong Cao and Shengxin Wang and Jiawei Li and Yuhua Fu and Guoliang Li and Xuewen Xu and Xinyun Li and Haiyan Wang},
    title     = {Innovative Dual-Network Framework for Monitoring Multiple Behaviors of Individual Pigs in Group-Housed Environments},
    journal   = {},
    volume    = {},
    pages     = {},
    year      = {},
    issn      = {},
    doi       = {}
}
```

The bibliographic details will be completed when the associated article is formally published.

