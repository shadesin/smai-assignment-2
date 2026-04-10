This repository contains jupyter notebooks and a pdf for smai-assignment-2, IIIT Hyderabad, Spring 2026. The assignment is based on Neural Networks.

The dataset for Q2 is available here: https://drive.google.com/file/d/1NB0p6rly0etGFSG-MLl4PJXSTnzLamq-/view?usp=sharing

### Dataset Structure

The dataset follows the standard **ImageFolder** format:

    currency_dataset_extended/
    ├── train/
    │   ├── 10/
    │   ├── 20/
    │   ├── 50/
    │   ├── 100/
    │   ├── 200/
    │   ├── 500/
    │   └── 2000/
    │
    └── test/
        ├── 10/
        ├── 20/
        ├── 50/
        ├── 100/
        ├── 200/
        ├── 500/
        └── 2000/

Each subdirectory represents a class label corresponding to a currency denomination.