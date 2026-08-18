# Metadata requirements

Before v1.0.0 is published, add the following files to this directory:

- `classes.yaml` — class IDs, names, and definitions.
- `sequence_metadata.csv` — one row per released sequence, including a stable sequence ID and split assignment.
- `annotation_format.md` — precise specifications for every annotation file.
- `split_policy.md` — split unit, split rationale, and leakage-control rules.
- `statistics.csv` — sequence, frame, instance, and class totals for each split.
- `SHA256SUMS.txt` — SHA-256 checksum for every downloadable release archive.

Use stable sequence identifiers that exactly match the names used in the archive and files under `splits/`.
