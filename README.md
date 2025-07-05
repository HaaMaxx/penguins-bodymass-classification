# 🐧 Penguin Body Mass Prediction & Species Classification  
![R](https://img.shields.io/badge/R-Used-blue)  
![MIT License](https://img.shields.io/badge/License-MIT-green)

---

This project analyzes the [`palmerpenguins`](https://allisonhorst.github.io/palmerpenguins/) dataset to achieve two goals:

1. **Predict penguin body mass** using Linear Regression and Linear Mixed Models.
2. **Classify penguin species** using Generalized Linear Models (GLMs) and Machine Learning methods.

---

## 📊 Dataset

The dataset contains 344 observations of 3 penguin species from islands near Palmer Station, Antarctica.  
Key variables include:

- `species`, `island`, `bill_length_mm`, `flipper_length_mm`
- `body_mass_g`, `sex`, `year`

---

## 🛠️ Methods

- **Preprocessing**: Data cleaning, NA handling, encoding categorical variables
- **Modeling (Task 1)**:
  - Linear Regression
  - Linear Mixed Models (LMM)
- **Modeling (Task 2)**:
  - Multinomial Logistic Regression
  - Binary Logistic Regression
  - Optional comparison with Decision Trees / SVM

---

## 📈 Results Overview

| Task                            | Method                  | Performance Summary          |
|---------------------------------|--------------------------|------------------------------|
| Body Mass Prediction            | LMM > LM                | LMM captured nested structure |
| Species Classification          | Multinomial GLM         | Accurate for 3-species classification |
| Chinstrap vs Gentoo Subset     | Binary GLM              | Precision/Recall: >90%       |

Details available in the [📘 Report](./penguins_report.pdf) and [🎯 Slides](./penguins_presentation.pptx).

---

## 📂 Project Structure

