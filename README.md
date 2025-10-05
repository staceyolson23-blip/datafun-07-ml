# datafun-07-ml
**Author:** Stacey Olson  
**Date:** October 2025  
**Repository:** [datafun-07-ml](https://github.com/staceyolson23-blip/datafun-07-ml)

---

## 📘 Overview
This project introduces **Predictive Machine Learning** through **Simple Linear Regression**.  
You’ll use both **SciPy** and **scikit-learn** to build and compare supervised learning models.  
Visualizations are created using **Matplotlib** and **Seaborn** within a Jupyter notebook.

Project tasks include:
- Charting a straight line (Celsius ↔ Fahrenheit)
- Building a linear regression model on NYC January temperature data
- Making and comparing predictions
- Creating scatter plots and best-fit lines
- Reflecting on model accuracy and limitations

---

## ⚙️ Environment & Setup

```bash
# Clone the repository
git clone https://github.com/staceyolson23-blip/datafun-07-ml.git
cd datafun-07-ml
git pull

# Create and activate a virtual environment

# macOS / Linux
python3 -m venv .venv
source .venv/bin/activate

# Windows PowerShell
py -m venv .venv
.\.venv\Scripts\Activate

# Upgrade tools and install dependencies
python -m pip install -U pip setuptools wheel
pip install -r requirements.txt
```
---
## 🔁 Repeatable Workflow
```
# Always start by pulling latest changes
git pull

# Activate your venv
source .venv/bin/activate        # macOS/Linux
# .\.venv\Scripts\Activate       # Windows PowerShell

# (Optional) Sync dependencies
pip install -r requirements.txt

# Work on your project
jupyter lab

# After working
git add -A
git commit -m "feat: progress on notebook"
git push
```
---
## 🧱 Project Structure
```
datafun-07-ml/
├─ data/           # CSVs or small datasets
├─ notebooks/      # Jupyter notebooks (main notebook: stacey_ml.ipynb)
├─ reports/        # exported figures or writeups
├─ src/            # reusable python modules (optional)
├─ requirements.txt
├─ requirements.lock.txt
├─ .gitignore
└─ README.md
```
---
## 📦 Requirements
Your requirements.txt should include:
```
jupyterlab
numpy
pandas
pyarrow
matplotlib
seaborn
scipy
```
To lock exact versions (optional):
```
pip freeze > requirements.lock.txt
git add requirements.lock.txt
git commit -m "build: lock dependency versions"
git push
```
---
## 🧪 Verification
Run the following to verify your setup:
```
python -m pip list
jupyter lab
```
All imports in your notebook should work without error.
---
## 🎯 Project Goals
This project demonstrates your ability to:

1. **Initialize a professional ML project**  
   - Create a GitHub repository with standard files  
   - Set up a local virtual environment and install dependencies  

2. **Visualize a simple linear relationship**  
   - Plot Celsius vs. Fahrenheit using the equation \( y = mx + b \)  

3. **Build a regression model with SciPy**  
   - Load NYC January temperature data  
   - Use `scipy.stats.linregress()` to calculate slope and intercept  
   - Predict the average high for 2024 and visualize the best-fit line  

4. **Build a regression model with scikit-learn**  
   - Split data into training and testing sets  
   - Fit a `LinearRegression` model  
   - Compare predictions and model performance  

5. **Communicate findings**  
   - Compare SciPy and scikit-learn approaches  
   - Reflect on accuracy, limitations, and potential improvements  

6. **(Optional)**  
   - Explore the **California Housing Dataset** using multiple ML models  
---
## 🗒️ Notes
Keep a log of key commands used and any troubleshooting steps.
Record additional dependencies if you install new packages.