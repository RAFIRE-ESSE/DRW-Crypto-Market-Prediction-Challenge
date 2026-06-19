# 📈 DRW — Crypto Market Prediction Challenge

![Finance](https://img.shields.io/badge/-Finance-1a1b26?style=flat-square&logoColor=c0caf5) ![Crypto](https://img.shields.io/badge/-Crypto-1a1b26?style=flat-square&logoColor=c0caf5) ![Market Prediction](https://img.shields.io/badge/-Market%20Prediction-1a1b26?style=flat-square&logoColor=c0caf5) ![Time Series](https://img.shields.io/badge/-Time%20Series-1a1b26?style=flat-square&logoColor=c0caf5) ![Feature Engineering](https://img.shields.io/badge/-Feature%20Engineering-1a1b26?style=flat-square&logoColor=c0caf5)

![Banner](./banner.png)

> [!IMPORTANT]
> **Host:** `DRW Trading`  
> **Platform Link:** [Kaggle Competition](https://www.kaggle.com/competitions/drw-crypto-market-prediction)  
> **Dataset Link:** [Kaggle Dataset](https://www.kaggle.com/competitions/drw-crypto-market-prediction/data)  
> **Domain:** `Crypto & Financial Markets`

## 📖 Overview

Crypto market price prediction challenge using order book signals. Very noisy data, so key focus was on robust feature engineering.

## ⚙️ Standard Pipeline Workflow

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'background': '#0f0f12', 'primaryColor': '#1a1b26', 'edgeLabelBackground':'#11111b', 'tertiaryColor': '#1a1b26'}}}%%
flowchart LR
    A[Data Gathering] --> B[Preprocessing & EDA]
    B --> C[Model Training]
    C --> D[Inference & Submission]
    style A fill:#1e1e24,stroke:#7aa2f7,stroke-width:2px,color:#c0caf5
    style B fill:#1e1e24,stroke:#bb9af7,stroke-width:2px,color:#c0caf5
    style C fill:#1e1e24,stroke:#f7768e,stroke-width:2px,color:#c0caf5
    style D fill:#1e1e24,stroke:#9ece6a,stroke-width:2px,color:#c0caf5
```

## 🗂️ Notebook Architecture & Inventory

### 📂 Preprocessing & EDA
*Data cleaning, feature engineering, and exploratory data analysis.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📁 **EDA_and_Visualization** | Multi-Version Script | [v1](./Preprocessing%20%26%20EDA/EDA_and_Visualization/v1.ipynb), [v2](./Preprocessing%20%26%20EDA/EDA_and_Visualization/v2.ipynb), [v3](./Preprocessing%20%26%20EDA/EDA_and_Visualization/v3.ipynb), [v4](./Preprocessing%20%26%20EDA/EDA_and_Visualization/v4.ipynb) | `Avg 856 KB` | `Requests API` |
| 📁 **LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_EDA_and_Visualization** | Multi-Version Script | [v1](./Preprocessing%20%26%20EDA/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_EDA_and_Visualization/v1.ipynb), [v2](./Preprocessing%20%26%20EDA/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_EDA_and_Visualization/v2.ipynb), [v3](./Preprocessing%20%26%20EDA/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_EDA_and_Visualization/v3.ipynb) | `Avg 1200 KB` | `LightGBM, XGBoost, CatBoost` |
| 📁 **LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_EDA_and_Visualization_2** | Multi-Version Script | [v1](./Preprocessing%20%26%20EDA/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_EDA_and_Visualization_2/v1.ipynb), [v2](./Preprocessing%20%26%20EDA/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_EDA_and_Visualization_2/v2.ipynb) | `Avg 104 KB` | `LightGBM, XGBoost, CatBoost` |
| 📁 **LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_DecisionTree_EDA_and_Visualization** | Multi-Version Script | [v1](./Preprocessing%20%26%20EDA/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_DecisionTree_EDA_and_Visualization/v1.ipynb), [v2](./Preprocessing%20%26%20EDA/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_DecisionTree_EDA_and_Visualization/v2.ipynb), [v3](./Preprocessing%20%26%20EDA/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_DecisionTree_EDA_and_Visualization/v3.ipynb) | `Avg 41 KB` | `LightGBM, XGBoost, CatBoost` |

### 📂 Training
*Model training and tuning scripts.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📁 **LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_DecisionTree_Training** | Multi-Version Script | [v1](./Training/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_DecisionTree_Training/v1.ipynb), [v2](./Training/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_DecisionTree_Training/v2.ipynb), [v3](./Training/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_DecisionTree_Training/v3.ipynb), [v4](./Training/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_DecisionTree_Training/v4.ipynb), [v5](./Training/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_DecisionTree_Training/v5.ipynb), [v6](./Training/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_DecisionTree_Training/v6.ipynb) | `Avg 12 KB` | `LightGBM, XGBoost, CatBoost` |

---

## 🚀 Navigation & Usage Guidelines

> [!TIP]
> 1. **EDA & Preprocessing**: Verify data loaders, actigraphy or DICOM image transformations before model training.
> 2. **Training & Optimization**: Check model definition parameters and training logs to reproduce network weights.
> 3. **Inference & Post-Processing**: Run final pipelines to verify predictions and check submission formats.


---

> *"In the volatile market, greed and panic are the dual engines of chaos."*
>
> — **Vigneshwaran S**
