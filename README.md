# Introduction

This repository has been forked from [A Practical Guide to Graph Neural Networks](https://github.com/isolabs/gnn-tutorial), which contains the code for the extended examples in the paper ["A Practical Guide to Graph Neural Networks"](https://arxiv.org/abs/2010.05234).

## Folder structure

```
.
├── notebooks       # The .ipynb files of the example code
├── .gitignore                     
├── requirements.txt         # The pip requirements file
├── LICENSE
└── README.md
```

## Running on your own computer

To run the code, install the requirements with ```pip install -r requirements.txt```, preferably creating before a conda-based environment with the following command:

```
conda create -n gnn_tutorial python==3.8
conda activate gnn_tutorial
pip install -r requirements.txt
```

After these operations run the ```jupyter notebook``` command.

This code has been tested using Python 3.8.0.
