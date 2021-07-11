# Introduction

This repository has been forked from [A Practical Guide to Graph Neural Networks](https://github.com/isolabs/gnn-tutorial), which contains the code for the extended examples in the paper ["A Practical Guide to Graph Neural Networks"](https://arxiv.org/abs/2010.05234).

## Folder structure

```
.
├── html            # Exported .html files of the notebooks
├── notebooks       # The .ipynb files of the example code
├── .gitignore                     
├── env.yml         # The conda environment dependencies file
├── LICENSE
└── README.md
```

## Running on your own computer

To run the code, use a conda-based package manager and install dependencies from the file ```env.yml``` .yml file. Do this using the following command (or similar):

```
conda env create -f env.yml
```

Activate this environment and run the ```jupyter notebook``` command.

This code has been tested using Python 3.8.0.
