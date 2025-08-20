# Hackathon Project Setup Guide

This guide explains how to set up the development environment for our hackathon project using VS Code, Anaconda, and Git.

---

## 1️⃣ Install VS Code

- Download and install [Visual Studio Code](https://code.visualstudio.com/).  
- In VS Code, install the following extensions:
  - **Intellicode**
  - **Python**
  - **Jupyter**

---

## 2️⃣ Install Anaconda

- Download and install [Anaconda](https://www.anaconda.com/products/distribution) for your operating system.  

---

## 3️⃣ Create Conda Environment

Open your terminal (Anaconda Prompt or VS Code terminal) and run:

```bash
# Create a new environment named 'hack_env' with Python 3.10
conda create -n hack_env python=3.10

# Activate the environment
conda activate hack_env
```
- Deactivate your Conda environment when you’re done working for the day
```bash
conda deactivate
```

---

## 3️⃣ Use Notebooks in VS Code

- Create a new notebook (.ipynb)
- Click kernel selector (top-right)
- Choose: Jupyter kernel >> Python 3.10 (hack_env)
- If you dont see it immediately close vscode and open it again

---

## 4️⃣ Git Workflow

```bash
# Clone repo
git clone <repo_url>
cd <repo_folder>

# Pull latest updates
git pull origin main

# After changes, commit and push
git add .
git commit -m "Your message"
git push origin main
```

---
⚠️ Everyone must use the same Python version and environment.
---

## 5️⃣ Packages to install

- 01_data_exploration
  
  ```bash
  pip install pandas matplotlib seaborn statsmodels scikit-learn prophet
  ```
