# 🌀 MathMorph

> An Interactive Visual Playground for Machine Learning Mathematics

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

**MathMorph** is a comprehensive, interactive, and visually stunning mathematical playground designed to help you explore machine learning and AI concepts from absolute first principles. By leveraging dynamic Jupyter widgets, live plotting, and interactive parameter sliders, MathMorph transforms abstract equations into intuitive, real-time visual deformations, optimization walks, and statistical experiments.

---

## 🎨 Interactive Exploration Modules

The workspace is organized into three progressive notebooks:

### 📐 [01. Linear Algebra](file:///Users/saiyashpoojari/Desktop/MathMorph/01_linear_algebra.ipynb)
*Every dataset is a matrix, every model parameter is a vector weight, and every layer transformation is matrix multiplication.*
* **Vector Operations Playground:** Geometrically visualize vector addition and scaling tip-to-tail.
* **Linear Transformations Simulator:** Interactively rotate, shear, scale, and reflect 2D space by controlling basis vector matrices ($\hat{i}$ and $\hat{j}$).
* **Eigenvalues & Eigenvectors Visualizer:** Find and watch the invariant directions of space deformations under linear transformations.

### 📈 [02. Calculus & Optimization](file:///Users/saiyashpoojari/Desktop/MathMorph/02_calculus_optimization.ipynb)
*Training a neural network is simply navigating a high-dimensional loss landscape to find global minima.*
* **1D Gradient Descent:** Tune learning rates and start coordinates to visualize convergence, overshoot, and divergence.
* **2D Optimization Landscapes:** Interactively step through gradient descent on multivariate functions (Paraboloids, Rosenbrock valley, Saddle points).
* **Learning Rate Playground:** See the effects of vanishing and exploding gradients in real time.

### 🎲 [03. Probability & Statistics](file:///Users/saiyashpoojari/Desktop/MathMorph/03_probability_statistics.ipynb)
*AI is about making decisions under uncertainty. Probability is the language of that uncertainty.*
* **Probability Distributions Lab:** Manipulate parameters for Gaussian, Binomial, and Exponential distributions.
* **Central Limit Theorem Demonstrator:** Perform custom sample size simulations and witness normal distributions emerge.
* **Interactive Bayesian Inference:** Update beliefs in real time as new data evidence arrives.

---

## 🚀 Getting Started

### Prerequisites

You will need Python 3.10+ and the packages listed in `requirements.txt`.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/saiyash07/MathMorph.git
   cd MathMorph
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Jupyter Playground:**
   ```bash
   jupyter notebook
   ```

---

## 🛠️ Project Structure

```
MathMorph/
├── 01_linear_algebra.ipynb         # Vector addition, transformations, eigenspaces
├── 02_calculus_optimization.ipynb  # Gradient descent, multi-variable optimization, learning rates
├── 03_probability_statistics.ipynb # Probability distributions, CLT, Bayesian inference
├── generate_notebooks.py           # Helper script to dynamically regenerate notebooks
├── requirements.txt                # Project dependencies (numpy, matplotlib, ipywidgets, etc.)
├── LICENSE                         # MIT License
└── README.md                       # High emphasis project documentation
```

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](file:///Users/saiyashpoojari/Desktop/MathMorph/LICENSE) file for details.

## 👤 Author

**Yash Poojari**
* GitHub: [@saiyash07](https://github.com/saiyash07)

# Step 33
