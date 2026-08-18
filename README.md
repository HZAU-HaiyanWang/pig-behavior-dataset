# Pig Behavior Dataset

An annotated image dataset for individual tracking and multi-behavior recognition of group-housed pigs.

## Directory structure

```text
pig-behavior-dataset/
├── dataset/
│   ├── images/
│   └── labels/
└── README.md
```

- `dataset/images/` contains the released image files.
- `dataset/labels/` contains the corresponding annotation files. Each annotation file must use the same base filename as its image.

## Release status

The dataset files, licence, persistent DOI, and citation information will be added after final verification and Zenodo publication.

For the manuscript revision, the exact train/validation/test allocation must also be made public. To keep this repository simple, the final files can be placed directly in `dataset/` as:

```text
train.txt
val.txt
test.txt
```

Each file should list the image or sequence identifiers used in that split.

## Data access and citation

The final versioned dataset will be archived on Zenodo. This README will then be updated with the version-specific DOI, download link, licence, and citation.
