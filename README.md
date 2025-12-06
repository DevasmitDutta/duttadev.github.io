# Wildfire Ignition Classification Project  
<!-- <img align="right" width="220" height="220" src="/assets/IMG/template_logo.png"> -->

<img align="right" width="220" height="220" alt="template_logo" src="https://github.com/user-attachments/assets/fb28b5da-20c8-41cf-a859-ebd25b98505a" />

Hi everyone — welcome to my AOS C111/204 final project site!

This project applies machine learning methods to a spatial wildfire ignition classification task.  
Using a synthetic dataset that imitates ignition patterns, a **custom convolutional neural network (CNN)** was trained and benchmarked against **classical machine learning models** including Logistic Regression, Support Vector Machines, Decision Trees, and Random Forests.

The goal was to:
- build and train ML models,
- evaluate their predictive performance,
- explain modelling decisions,
- and publish all results in a reproducible report.

This website hosts my final write-up, figures, and associated code.

---

## 🔍 Project Overview

### 💡 Why this topic?
Wildfire behaviour is spatial in nature — ignition spreads across landscapes rather than isolated data points.  
This makes it a good test case for comparing **deep learning architectures that learn spatial features** against **shallow learning models that operate on flattened inputs**.

### 📌 What I implemented
✔ Programmatic dataset generation  
✔ CNN model definition using PyTorch  
✔ Training with validation tracking  
✔ Classical ML baselines for comparison  
✔ Performance metrics:
- accuracy
- ROC curves
- confusion matrices  
✔ Reported findings and interpretation

### 📈 Key results
- The custom CNN achieved the highest accuracy and clearer separation between ignition and non-ignition cases.
- Traditional models performed reasonably well but struggled when spatial information was flattened away.
- The experiment demonstrates how **feature representation** influences machine learning performance.

---

## 📄 Report Access

You can read my full technical report here:  
➡️ [Open Project Report](/assets/Report_Devasmit_Dutta__1_.pdf)  
(or view it under `project.md` if you prefer markdown formatting)

---

## 💻 Code Access

My code is available here as a downloadable notebook:  
➡️ [Download Project Code](/assets/project_code.ipynb)

It contains:
- data generation routines  
- model architecture implementation  
- training loop  
- evaluation and visualisation

---

## 🌐 How this website works

This website is hosted using **GitHub Pages + Markdown**.  
Markdown files (like this README) automatically render as web pages through Jekyll themes.

To explore or modify:
- Edit `_config.yml` to change title and theme  
- Update `README.md` to change your homepage  
- Add more markdown pages for future projects  

---

## ✨ Final Notes

This site doubles as a **public portfolio**, so I may expand it with new research, experiments, papers, and visualisations over time.  
Thanks for visiting — feel free to explore!
