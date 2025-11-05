# Implementation of the Study: "Adaptive Detection of Software Aging under Workload Shift"

This repository contains the code and resources used in the study "Adaptive Detection of Software Aging under Workload Shift". The project implements a machine learning approach to detect software aging in environments with dynamic workload variations.

## Citation

If you use this code in your research, please cite the following paper:

```bibtex
@inproceedings{silva2025adaptive,
  title={Adaptive Detection of Software Aging under Workload Shift},
  author={Moura, Rafael Jos{\'e} and Nascimento, Maria Gizele and Machida, Fumio and Andrade, Ermeson},
  booktitle={Simp{\'o}sio em Sistemas Computacionais de Alto Desempenho (SSCAD)},
  pages={242--253},
  year={2025},
  organization={SBC}
}
```

## Methodology

The process was divided into two main stages, each corresponding to a Jupyter notebook:

1.  **`labeling.ipynb`**: Performs the preprocessing and labeling of raw time-series data to identify and classify periods of software aging.
2.  **`experiments.ipynb`**: Uses the labeled data to train a machine learning model and evaluates its performance in scenarios that simulate different types of concept drift (sudden, gradual, and recurring), applying detection and adaptation techniques.

## Dataset

The original (unlabeled) dataset was obtained from the work of Couto et al. (2024).

```bibtex
@article{couto2024comparative,
  title={A Comparative Analysis of Software Aging in Relational Database System Environments},
  author={Couto, Herderson and Machida, Fumio and Callou, Gustavo and Andrade, Ermeson},
  journal={IEEE Transactions on Emerging Topics in Computing},
  year={2024},
  publisher={IEEE}
}
```
