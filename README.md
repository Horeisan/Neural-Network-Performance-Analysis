# Neural-Network-Performance-Analysis

## Project Description
This project demonstrates the implementation and optimization of **Multi-Layer Perceptron (MLP)** models using **PyTorch**. The analysis is performed on the **Energy Efficiency dataset** to predict heating and cooling loads through regression.

The main focus of the study is to evaluate how different hyperparameters and regularization techniques impact model generalization. Key components include:

* **Robust Evaluation:** Using **5-fold cross-validation** to ensure stable performance metrics across different data splits.
* **Architectural Experiments:** Comparing a **baseline model** against **larger networks** to observe the effects of increased capacity on learning.
* **Overfitting Mitigation:** Testing the effectiveness of **Dropout layers** and **L2 regularization** (weight decay) in reducing the gap between training and validation loss.
* **Optimization Analysis:** Investigating the influence of various **learning rates**, **optimizers** (Adam vs. SGD), and **batch sizes** on convergence behavior.
