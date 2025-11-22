# 🚲 Seoul Bike Sharing Demand Predictor

**[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZX-qj4H6I8mDYbzX1YlCpfnzpfRFt2D7?usp=sharing)**
**[![GitHub](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Divesh-Kshirsagar/Seoul-Bike-Sharing-Demand-Predictor)**
**[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)**

---

## 📌 Overview

This project focuses on **predicting bike rental counts** in Seoul using various regression models. The notebook explores both classical and neural network approaches to understand and forecast bike sharing demand based on weather and temporal features.

---

## 📊 Dataset

The **[Seoul Bike Sharing Demand Dataset](https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand)** is sourced from the UCI Machine Learning Repository:

> **Seoul Bike Sharing Demand** [Dataset]. (2020). UCI Machine Learning Repository. [https://doi.org/10.24432/C5F62R](https://doi.org/10.24432/C5F62R).

**Key Features:**
- Date, Hour, Temperature, Humidity, Wind Speed, Visibility, Dew Point, Solar Radiation, Rainfall, Snowfall, Bike Count, and more.

---

## 🔍 Notebook Contents

### 1️⃣ **Dataset Information**
- Description of the dataset and its variables.

### 2️⃣ **Data Loading & Preprocessing**
- Importing libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `tensorflow`).
- Loading and cleaning the dataset.
- Filtering for noon (hour 12) and dropping less relevant columns.

### 3️⃣ **Exploratory Data Analysis (EDA)**
- Scatter plots to visualize relationships between features and bike count.
- Dropping columns with weak linear relationships.

### 4️⃣ **Data Splitting**
- 60-20-20 split for training, validation, and test sets.

### 5️⃣ **Modeling**
- **Linear Regression:**
  - Simple Linear Regression (SLR) using only temperature.
  - Multiple Linear Regression (MLR) using all features.
- **Neural Networks:**
  - Linear regression with a single dense layer.
  - Multiple linear regression with neural nets (ReLU activations).
  - Complex neural networks for temperature-based prediction.

### 6️⃣ **Visualization**
- Training loss plots and model fit visualizations.

---

## 🛠️ How to Use

1. **Open in Colab:**
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZX-qj4H6I8mDYbzX1YlCpfnzpfRFt2D7?usp=sharing)

2. **Run the Notebook:**
   - Follow the step-by-step cells.
   - Ensure you have the required libraries installed.

3. **Clone the Repo:**
   ```bash
   git clone https://github.com/Divesh-Kshirsagar/Seoul-Bike-Sharing-Demand-Predictor.git
   ```

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

