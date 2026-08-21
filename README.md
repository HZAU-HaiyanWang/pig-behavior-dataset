# Pig Behavior Monitoring Dataset

The Pig Behavior Monitoring Dataset is an annotated resource designed to support the development and evaluation of computer-vision methods for automated monitoring of group-housed pigs in commercial barn environments. It comprises two complementary subsets: **Pig Multi-Behavior Detection**, which provides annotated images for five common pig behaviors—standing, side-lying, prone lying, climbing, and feeding—and **Individual Tracking**, which provides video sequences with frame-level identity annotations for tracking individual pigs over time. The dataset supports research on pig behavior detection and recognition, multi-object tracking, and individual-level analysis under practical farm conditions, including animal interactions, occlusion, and variable illumination.

## Overview

<!-- A dataset overview figure will be added here. -->
![Pig behavior dataset overview](./overview.png)
## Dataset Summary

Detailed statistics for each subset—including the number of images, labels, videos, frames, tracked identities, recording duration, and split counts—will be reported in the fixed Version 1.0.0 release.

## Behavior Classes

The Pig Multi-Behavior Detection subset covers five primary behaviors:

1. Standing
2. Side-lying
3. Prone lying
4. Climbing
5. Feeding

The numerical class-ID mapping used in the annotation files will be included when the labels are released.

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

## Annotation Format

A detailed, line-level specification of the detection and tracking annotation formats—including coordinate conventions, class IDs, frame numbering, and individual identity definitions—will be published with Version 1.0.0.

## Data Split

The exact training, validation, and test manifests will be released as `multi_behavior_detection_split.csv` and `individual_tracking_split.csv`. Where possible, the split will be defined at the source-sequence level to avoid placing highly related frames from the same sequence in different subsets.

## Data Collection and Ethics

The data were recorded from group-housed pigs in commercial barn environments. The final public release will include the applicable animal-welfare, ethical-approval, and data-permission information.

## License

This is a pre-release repository. No data-use license has been granted yet. The final data license will be selected by the data owners before Version 1.0.0 is published; CC BY 4.0 is the proposed default, subject to confirmation of institutional and farm permissions.

## Citation

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

## Version and Availability

This repository is currently in preparation and contains documentation and directory placeholders only; the dataset files are not yet available for download. Version 1.0.0 will be released as a fixed GitHub version and archived as a Zenodo dataset record with a persistent DOI.
