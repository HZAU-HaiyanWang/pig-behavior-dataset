# Pig Behavior Monitoring Dataset

This repository contains two annotated datasets for monitoring group-housed pigs.

## Directory Structure

```text
pig-behavior-dataset/
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
