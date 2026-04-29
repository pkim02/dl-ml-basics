# Implementation Proof

This repository is meant to be reviewed as implementation evidence. The notebook keeps the code cells and executed outputs that show the training flow end to end.

## What To Inspect

| Evidence | Where | What it proves |
| --- | --- | --- |
| `LinearRegressionModel` | `ml_basics.ipynb` | Implements a PyTorch `nn.Module` with a learnable linear layer and MSE training loop. |
| `LogisticRegressionModel` | `ml_basics.ipynb` | Builds a softmax-classification pipeline for MNIST using `CrossEntropyLoss`. |
| `FeedforwardNeuralNetModel` | `ml_basics.ipynb` | Extends logistic regression into a multilayer neural network with nonlinear activations. |
| Manual train/eval loops | `ml_basics.ipynb` | Shows gradient clearing, forward pass, loss calculation, backpropagation, optimizer steps, and accuracy computation. |
| CPU/GPU variants | `ml_basics.ipynb` | Shows the mechanics of moving models and tensors onto the active device. |

## Reviewer Notes

- The project is intentionally simple: it demonstrates that I understand the mechanics underneath later computer vision models.
- Outputs are kept in the notebook so reviewers can see losses, predictions, and accuracy checks without rerunning the full notebook.
- The code uses PyTorch primitives directly (`nn.Module`, `loss.backward()`, optimizer steps) instead of a high-level training framework.
