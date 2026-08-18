# Pig Behavior Monitoring Dataset

The Pig Behavior Monitoring Dataset is an annotated resource designed to support the development and evaluation of computer-vision methods for automated monitoring of group-housed pigs in commercial barn environments. It comprises two complementary subsets: **Pig Multi-Behavior Detection**, which provides annotated images for five common pig behaviors—standing, side-lying, prone lying, climbing, and feeding—and **Individual Tracking**, which provides video sequences with frame-level identity annotations for tracking individual pigs over time. The dataset supports research on pig behavior detection and recognition, multi-object tracking, and individual-level analysis under practical farm conditions, including animal interactions, occlusion, and variable illumination.

## Overview

## Directory Structure

```text
pig-behavior-monitoring-dataset/
├── pig_multi_behavior_detection/
│   ├── images/
│   │   ├── 000000000001.jpg
│   │   ├── 000000000002.jpg
│   │   └── ...
│   └── labels/
│       ├── 000000000001.txt
│       ├── 000000000002.txt
│       └── ...
├── individual_tracking/
│   ├── videos/
│   │   ├── video1.mp4
│   │   ├── video2.mp4
│   │   └── ...
│   └── annotations/
│       ├── 000000000001.txt
│       ├── 000000000002.txt
│       └── ...
└── README.md
```

## Pig Multi-Behavior Detection

- `pig_multi_behavior_detection/images/` contains the image files.
- `pig_multi_behavior_detection/labels/` contains the corresponding annotation files.
- Image and label files use the same base filename.

## Individual Tracking

- `individual_tracking/videos/` contains the video sequences.
- `individual_tracking/annotations/` contains the corresponding tracking annotation files.

## Release Information

The final public release will be updated with the dataset version, licence, persistent DOI, download information, and citation details after final verification and Zenodo publication.

For manuscript reproducibility, the exact training, validation, and test split files will also be made publicly available before the revised manuscript is submitted.
