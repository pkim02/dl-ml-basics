# Deep Learning Basics in PyTorch

Portfolio project by `@pkim02`.

## Project Goal

A PyTorch implementation notebook for linear regression, logistic regression, and feedforward neural networks, including MNIST classification experiments.

## Notebooks

- `ml_basics.ipynb`: Deep Learning Basics in PyTorch

## What I Implemented

- Linear regression with gradient-based optimization in PyTorch.
- Logistic regression and cross-entropy training for MNIST.
- Feedforward neural networks with sigmoid, tanh, and ReLU variants.
- CPU/GPU training patterns and model save/load examples.

## Results

The notebook keeps executed outputs for losses, predictions, and accuracy checks so reviewers can inspect the training behavior without rerunning every cell.

The notebooks keep most executed outputs so reviewers can inspect the results directly on GitHub. Full reproduction may require downloading the referenced public datasets or pretrained weights.

## How To Run

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

Open the notebook listed above and run cells in order. GPU is optional for review, but recommended for rerunning training-heavy experiments.

## Citations

- PyTorch documentation: https://pytorch.org/docs/stable/index.html
- MNIST dataset: http://yann.lecun.com/exdb/mnist/

## Copyright And Data Note

This repository contains a cleaned portfolio version of my own implementation work. Assignment prompts, submission metadata, personal identifiers, and course-provided local figures were removed. The MIT license applies only to the code and documentation in this repository. Papers, datasets, pretrained weights, and any third-party libraries or assets keep their original licenses and terms.
