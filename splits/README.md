# Reproducible data splits

This directory will contain the exact split manifests used for the manuscript experiments.

Planned files:

```text
detection_train.txt
detection_val.txt
detection_test.txt
tracking_train.txt
tracking_val.txt
tracking_test.txt
```

Each file should contain one stable sequence identifier per line, using the same relative identifier as the released data archive. If detection and tracking use the same partition, keep separate files anyway so the experimental protocol is explicit.

Before release, verify that:

1. every released sequence belongs to exactly one split for each applicable task;
2. no sequence or overlapping portion of the same source video appears in more than one split;
3. the files reproduce the results reported in the manuscript;
4. split counts match `metadata/statistics.csv`.
