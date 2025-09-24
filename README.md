# Peer Review Toxicity Dataset

This repository contains the dataset for our paper:  
**[Benchmark on Peer Review Toxic Detection: A Challenging Task with a New Dataset](https://arxiv.org/pdf/2502.01676)**

## Overview
This dataset was developed to support research on detecting toxicity in peer reviews. It includes sentence-level annotations aimed at identifying toxic language in academic peer review comments.

## Important Notes
- **Annotation Level:**  
  The annotations are performed at the **sentence level**, not at the full review level. This means that context across multiple sentences in a review may not be fully captured.

- **Annotation Process:**  
  Three independent annotators were involved in the labeling process to reach consensus.  
  However, **toxicity is inherently subjective**, and different readers may have varying opinions on certain instances.

- **Refined Labels:**  
  Before releasing the dataset, we further refined the labels.  
  As a result, the **statistics may differ slightly** from those reported in the original paper.

## Considerations for Use
If you plan to use this dataset for your research or applications, please keep the previous factors in mind.

## Citation
If you use this dataset, please cite our paper:
@article{luo2025benchmark,
  title        = {Benchmark on Peer Review Toxic Detection: A Challenging Task with a New Dataset},
  author       = {Luo, Man and Peterson, Bradley and Gan, Rafael and Ramalingame, Hari and Gangrade, Navya and Dimarogona, Ariadne and Banerjee, Imon and Howard, Phillip},
  journal      = {CoRR},
  volume       = {abs/2502.01676},
  year         = {2025},
  url          = {https://arxiv.org/pdf/2502.01676},
  archivePrefix = {arXiv},
  eprint       = {2502.01676}
}

