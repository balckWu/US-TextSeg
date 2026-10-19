# US-TextSeg repository naming and source record

Date: 2026-10-19.

## Canonical repository

- Repository: <https://github.com/balckWu/US-TextSeg>.
- Manuscript archive: <https://github.com/balckWu/US-TextSeg/tree/kbs-v9-20261019>.
- Paper method name: **US-TextSeg**.

This repository was created at the author's request to align the public repository
name with the manuscript. It starts from a clean export of the already verified
KBS v9 source release:

- Source repository: <https://github.com/balckWu/TaskSegment>.
- Source commit: `c7f8971d9c185eb53726e59449361110e09e2218`.
- Source tag in that repository: `kbs-v9-20261019`.

The tag names identify releases within their respective repositories. The new
repository has its own commit, including this naming record and updated links.
The original repository and its published tag are preserved.

## Scope

Only documentation and repository naming are changed from the source export.
Model, training, inference, evaluation, configuration, tests, and archived metric
files are byte-for-byte identical to that validated source release. The existing
validation report describes checks on those unchanged source files; migration
does not claim another training run or clinical evaluation.

Internal Python package and checkpoint identifiers remain `tasksegment` and
`TaskSegment` to retain compatibility with the completed experiments. The
Iris-2D name still identifies the separately implemented comparison baseline.

Datasets, clinical images, model weights, support manifests, credentials, and
training logs are not included. Third-party source notices are preserved.
