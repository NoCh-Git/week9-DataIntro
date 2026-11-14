# Session 9 — Intro to Data Course

This repository contains the materials for **Session X** of *Course Y*.  
- Slides: see [`slides/`](./slides/) folder  
- Notebooks: see [`notebooks/`](./notebooks/) folder 
---

## 📑 Session Outline
This session introduces Neural Networks and Unsupervised Learning, exploring how neural networks learn complex relationships from data and how clustering algorithms discover patterns without predefined labels.
- Neural Networks: Artificial neurons, activation functions, multilayer perceptrons (MLPs), backpropagation, gradient descent and regularisation.
- Unsupervised Learning: Supervised vs. unsupervised learning, clustering, similarity and distance measures.
- K-Means Clustering: Centroids, feature scaling, choosing K (elbow method and silhouette score), visualisation and interpretation of clusters.
Practical exercises: Build a neural network classifier and apply K-Means clustering to explore and interpret patterns in data.

---
## 🚀 Environment Setup

Before starting, please **fork this repository** and create a fresh Python virtual environment.  
All required libraries are listed in `requirements.txt`.

> ⚠️ If you encounter errors during `pip install`, try removing the version pinning for the failing package(s) in `requirements.txt`.  
> On Apple M1/M2 systems you may also need to install additional system packages (the “M1 shizzle”).

---

### macOS / Linux (bash/zsh)

```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate

# Upgrade pip and install dependencies
pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (PowerShell)
```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
.venv\Scripts\Activate.ps1

# Upgrade pip and install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (Git Bash)
```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
source .venv/Scripts/activate

# Upgrade pip and install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

You’re now ready to run the session notebooks!

Deactivate the environment when you’re done:
```bash
deactivate
```
