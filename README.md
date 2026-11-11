# **Transformer Health Index Prediction Using Machine Learning**
This project implements machine learning algorithms to predict transformer Health Index (HI) using transformer condition data.

## **Algorithms**
- Random Forest
- Gradient Boosting
- XGBoost
## **Methods**
- Data preprocessing
- Feature selection
- Sample weighting
- Regression evaluation
- Classification evaluation
## **Evaluation Metrics**

Regression: MAE, MSE, RMSE, MAPE, and R².

Classification: Accuracy, Precision, Recall, and F1-Score.

## **Project Objective**

To evaluate and compare machine learning algorithms for transformer Health Index prediction, particularly when dealing with imbalanced datasets.

## Dataset

The dataset used in this project is the **Sample Power Transformers Health Condition Dataset** provided by Eason Lai on Kaggle.

**Dataset Information:**
- Total observations: 470
- Input features: 14
- Target variable: Health Index (HI)
- Data characteristics: Imbalanced dataset

**Dataset Source:**

[Kaggle - Sample Power Transformers Health Condition Dataset](https://www.kaggle.com/datasets/easonlai/sample-power-transformers-health-condition-dataset)

The dataset contains transformer condition parameters, including Dissolved Gas Analysis (DGA) data and transformer oil and electrical properties.

**Features:**
- Hydrogen
- Oxigen
- Nitrogen
- Methane
- CO
- CO2
- Ethylene
- Ethane
- Acethylene
- DBDS (Dibenzy Disulfide)
- Power Factor
- Interfacial Voltage
- Dielectric Rigidity
- Water Content

**Target Variable:**
- Health Index

## Health Index Interpretation

The transformer condition is interpreted based on its Health Index (HI) value. The following table presents the relationship between Health Index, transformer condition, and expected lifetime.

| Health Index (%) | Condition | Expected Lifetime |
|:---:|:---:|:---|
| 85–100 | Very Good | More than 15 years |
| 70–85 | Good | More than 10 years |
| 50–70 | Fair | 3–10 years |
| 30–50 | Poor | Less than 3 years |
| 0–30 | Very Poor | Near the end of life |

**Note:** The condition thresholds are used to interpret the predicted Health Index values.
