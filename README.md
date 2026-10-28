# OKR: Orthogonal Knowledge Refreshing for Domain-Incremental Object Detection

**ECCV 2026**

Aoting Zhang, Dongbao Yang, Chang Liu, Xiaopeng Hong, Can Ma, Yu Zhou

[Paper](https://arxiv.org/abs/2607.17340) | [PDF](https://arxiv.org/pdf/2607.17340)

## Overview

Orthogonal Knowledge Refreshing (OKR) addresses exemplar-free domain-incremental object detection through:

- Domain-specific low-rank branches that are combined for prediction.
- Orthogonal gradient refreshing to reduce interference with previously learned domains.
- Topology-aware consistency to preserve semantic structure across domains.

The paper reports improvements of **5.6 mAP points** on the Pascal VOC series and **6.5 mAP points** on the BDD100K series over the best exemplar-free baseline.

## Repository status

This initial version contains paper information and citation metadata. Training code, configurations, and checkpoints are not included yet.

## Citation

```bibtex
@misc{zhang2026orthogonalknowledgerefreshing,
  title         = {Orthogonal Knowledge Refreshing for Domain-Incremental Object Detection},
  author        = {Aoting Zhang and Dongbao Yang and Chang Liu and Xiaopeng Hong and Can Ma and Yu Zhou},
  year          = {2026},
  eprint        = {2607.17340},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV},
  url           = {https://arxiv.org/abs/2607.17340}
}
```
