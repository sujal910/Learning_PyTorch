<div align="center">

# 🔥 Learning PyTorch

**A structured, beginner-to-intermediate notebook series for learning PyTorch from scratch.**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

</div>

---

## 📖 About

This repository is my personal PyTorch learning journey — structured as a series of hands-on Jupyter notebooks that build on each other, from basic tensor operations all the way to convolutional neural networks.

Each notebook is self-contained with explanations, code, and visualizations. The goal is to understand the **why** behind every concept, not just copy-paste code.

---

## 📂 Repository Structure

```
Learning_PyTorch/
│
├── 01_Tensors/
│   └── 01_pytorch_tensors.ipynb       # Tensor basics, operations, GPU usage
│
├── 02_Workflow/
│   └── 02_pytorch_workflow.ipynb      # Training loop, loss, optimizer, eval
│
├── 03_Neural_Networks/                 ← coming soon
│   └── 03_neural_networks.ipynb       # nn.Module, layers, activations
│
├── 04_Datasets_DataLoaders/            ← coming soon
│   └── 04_datasets.ipynb              # Custom datasets, DataLoader, transforms
│
├── 05_CNNs/                            ← coming soon
│   └── 05_cnn.ipynb                   # Conv2d, pooling, image classification
│
├── Extra_Resources/
│   └── matplotlib_basics.ipynb        # Quick matplotlib reference
│
└── README.md
```

---

## 📋 Notebook Index

| # | Topic | Notebook | Status |
|---|-------|----------|--------|
| 01 | PyTorch Tensors & Operations | `01_Tensors/` | ✅ Done |
| 02 | PyTorch Training Workflow | `02_Workflow/` | ✅ Done |
| 03 | Neural Networks (`nn.Module`) | `03_Neural_Networks/` | 🔄 In progress |
| 04 | Datasets & DataLoaders | `04_Datasets_DataLoaders/` | ⬜ Upcoming |
| 05 | Convolutional Neural Networks | `05_CNNs/` | ⬜ Upcoming |

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install torch torchvision matplotlib jupyter
```

> Recommended: Python 3.10+, PyTorch 2.x

### Run Locally

```bash
git clone https://github.com/sujal910/Learning_PyTorch.git
cd Learning_PyTorch
jupyter notebook
```

---

## 🧭 Learning Path

This repo follows the **PyTorch for Deep Learning** curriculum:

```
Tensors → Training Workflow → Neural Networks → CNNs → Transfer Learning
```

Each section builds on the previous one — start from `01_Tensors/` if you're new.

---

## 📌 Notes

- Notebooks are written using **PyTorch 2.x** — older versions may have minor API differences
- GPU is optional; all notebooks run on CPU by default
- Extra_Resources contains supplementary material (matplotlib, etc.) that supports the main series

---

<div align="center">

**Made with ❤️ while learning ML from scratch**

⭐ Star this repo if it helps you on your own learning journey!

</div>
