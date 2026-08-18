# Dataset Card: Pig Behavior Dataset

> **Completion status:** Template under preparation. Every bracketed item must be completed and checked before the public v1.0.0 release.

## 1. Dataset summary

- **Name:** Pig Behavior Dataset
- **Version:** [v1.0.0]
- **Persistent identifier:** [Zenodo DOI]
- **Licence:** [licence name and URL]
- **Primary contact:** [name and email]
- **Citation:** [paper citation and dataset citation]

## 2. Intended uses

The dataset is intended for research on:

- pig detection;
- individual pig tracking;
- multi-behaviour recognition;
- evaluation of computer-vision methods in group-housed pig environments.

It must not be used for purposes that conflict with the approved data-use agreement or applicable animal-welfare and privacy requirements.

## 3. Data composition

Complete the following before release:

- number of farms, pens, recording sessions, and sequences;
- number of animals and relevant population characteristics;
- video duration, frame rate, image resolution, and camera viewpoint;
- number of annotated frames and annotations per task;
- behaviour-class names, numeric IDs, and sample counts;
- file formats and total archive size.

## 4. Data collection and preprocessing

Document:

- recording environment and hardware at a level that supports reproducibility without exposing sensitive operational information;
- collection dates or date ranges, where appropriate;
- frame extraction, de-identification, and preprocessing steps;
- inclusion/exclusion criteria for videos and annotations.

## 5. Annotation protocol

Document:

- annotator training and quality-control procedures;
- tracking-ID convention;
- behaviour definitions and ambiguity-resolution rules;
- bounding-box, occlusion, truncation, and interpolation conventions;
- annotation format and example records.

## 6. Data splits and leakage control

The exact sequence lists must be stored in `splits/`. State clearly whether the split unit is a video, recording session, pen, animal group, or another independent unit. No overlapping frames from the same source sequence may occur across train, validation, and test sets.

## 7. Ethical, legal, and privacy considerations

Before publication, confirm that:

- the data owner and farm have authorised public release under the chosen licence;
- videos contain no identifiable people or sensitive facility information, or these have been removed;
- the listed creators and affiliations are approved by all relevant contributors.

## 8. Maintenance and versioning

- The paper will cite the version-specific DOI for v1.0.0.
- Any file-changing update will be released as a new dataset version with its own DOI.
- Corrections and changes will be recorded in [CHANGELOG.md](CHANGELOG.md).
