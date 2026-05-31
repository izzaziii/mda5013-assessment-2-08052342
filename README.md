# Pediatric Pneumonia Chest X-Ray Classification

This repository contains a deep learning pipeline for binary classification of pediatric chest radiographs to diagnose pneumonia vs. normal healthy lungs. It compares a custom Convolutional Neural Network (CNN) built from scratch against a pre-trained **DenseNet121** model using transfer learning, both compiled and managed within Keras 3.

---

## Prerequisites

First, ensure you have `uv` installed on your machine.

**On macOS / Linux:**
```bash
curl -LsSf https://astral-sh/uv/install.sh | sh
```

**On Windows (PowerShell):**
```powershell
powershell -c "irm https://astral-sh/uv/install.ps1 | iex"
```

**Via Homebrew (Alternative macOS):**
```bash
brew install uv
```

---

## 🛠️ Repository Setup

### Synchronize Dependencies
Navigate to the project root directory in your terminal and run:
```bash
uv sync
```
---

## 📁 Repository Structure

```
├── .venv/                         # Local virtual environment (managed by uv)
├── chest_xray/                    # Radiograph dataset (Pneumonia vs. Normal)
├── data-exploration.ipynb         # Main Jupyter Notebook (data prep, baseline model, DenseNet121)
├── pyproject.toml                 # Declarative project metadata and dependencies
├── uv.lock                        # Fully resolved reproducible dependency lockfile
└── README.md                      # Setup and usage guide (this file)
```
