# Manual vs Automatic Optimizers in Deep Learning

This repository explores the effects of **manual vs automatic training loops** in neural networks, using **PyTorch**. It also investigates how different **feature scaling methods** affect model performance when paired with each training approach.

---

##  Project Objectives

- Implement and compare:
  - Manual training loop with direct parameter updates
  - Automatic training loop using optimizers (`Adam`, `RMSProp`)
- Evaluate:
  - The impact of `StandardScaler`, `MinMaxScaler`, and `RobustScaler`
  - Training and validation loss across different configurations
- Visualize training dynamics for insight into convergence, stability, and overfitting
- Summarize findings in a well-documented LaTeX report

---

##  Techniques Used

- PyTorch for model implementation and optimization
- Scikit-learn for preprocessing and scaling
- Matplotlib for loss curve visualization
- Manual gradient descent vs. `optimizer.step()`
- Exploratory data analysis (histograms, pairplots)

---

##  Structure
```
├── notebooks/ # Main notebook directory 
├── logs/ # Plots and visuals 
└── README.md
```
---

##  Sample Outputs


---

##  Requirements

```bash
pip install torch scikit-learn matplotlib seaborn
```
##  Run It
Open the notebook:

```
jupyter notebook 21P0102_ass1.ipynb
```
