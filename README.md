# Lab 1: Introduction to Machine Learning and Setting the Environment

## 🎯 Objective

- Understand the basic concepts of Machine Learning (ML).
- Set up the Python development environment using Anaconda.
- Install and use essential ML libraries: **NumPy**, **Pandas**, **Matplotlib**, and **Scikit-learn**.

---

## 📘 Introduction

**Machine Learning (ML)** is a subfield of Artificial Intelligence (AI) focused on building systems that can learn from data and improve their performance without being explicitly programmed.

ML is used in:
- Image and speech recognition
- Autonomous vehicles
- Predictive analytics
- Natural Language Processing (NLP)

### Types of Machine Learning
- **Supervised Learning**: Learns from labeled data (e.g., classification, regression).
- **Unsupervised Learning**: Finds patterns in unlabeled data (e.g., clustering).
- **Reinforcement Learning**: Learns from feedback by interacting with an environment.

Python is the most popular language for ML due to its readability and ecosystem of libraries. **Anaconda** provides a robust and easy-to-manage ML environment.

---

## 🧰 Tools and Libraries

| Tool / Library   | Purpose                                      |
|------------------|----------------------------------------------|
| Anaconda Prompt  | Manage Python environments                   |
| Jupyter Notebook | Interactive coding and documentation         |
| NumPy            | Numerical computing                          |
| Pandas           | Data analysis and manipulation               |
| Matplotlib       | Data visualization                           |
| Scikit-learn     | ML algorithms and data preprocessing         |

---

## 🛠️ Procedure

### 1. Open Anaconda Prompt
> 📍 Start → Search **Anaconda Prompt** → Open it

### 2. Create a New Environment
```bash
conda create --name umar python=3.9
### 3. Activate the Environment

```bash
conda activate umar
### 4. Install Required Libraries

```bash
conda install numpy pandas matplotlib scikit-learn jupyter
### 5. Launch Jupyter Notebook

```bash
jupyter notebook
This will open a browser window.

Click **New → Python 3** to open a new notebook.

---

## ✅ Results

- ✅ A dedicated conda environment was successfully created.
- ✅ All required ML libraries (**NumPy**, **Pandas**, **Matplotlib**, **Scikit-learn**, **Jupyter**) were installed.
- ✅ Jupyter Notebook was launched and accessed through the Anaconda environment.

---

## 🧾 Conclusion

This lab provided a hands-on introduction to **Machine Learning** by setting up a clean and functional development environment. By using **Anaconda** for environment management and **Jupyter Notebook** for interactive development, we established a reliable workflow for future ML experiments and projects.

