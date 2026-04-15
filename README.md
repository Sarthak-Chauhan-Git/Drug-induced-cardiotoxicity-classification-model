# 🫀 Drug-Induced Cardiotoxicity Classification Model

A machine learning project for predicting whether a drug compound is likely to cause cardiotoxicity — a critical safety concern in pharmaceutical development.

---

## 📖 Overview

Drug-induced cardiotoxicity is one of the leading causes of drug failure during clinical trials and post-market withdrawals. Early identification of cardiotoxic compounds can save significant time and cost in drug discovery pipelines, and more importantly, protect patient safety.

This project builds and evaluates a binary classification model that predicts the cardiotoxic potential of drug-like molecules based on their chemical features.

---

## 📁 Repository Structure

```
Drug-induced-cardiotoxicity-classification-model/
│
├── Cardiotoxicity.ipynb    # Main Jupyter notebook with full pipeline
└── LICENSE                 # Apache-2.0 License
```

---

## 🔬 Workflow

The notebook covers the following steps:

1. **Data Loading & Exploration** — Loading the cardiotoxicity dataset and performing exploratory data analysis (EDA)
2. **Preprocessing** — Handling missing values, feature encoding, and normalization
3. **Feature Engineering** — Selecting and transforming relevant molecular/chemical descriptors
4. **Model Training** — Training one or more classification algorithms (e.g., Random Forest, SVM, XGBoost)
5. **Evaluation** — Assessing model performance using metrics such as accuracy, ROC-AUC, precision, recall, and F1-score
6. **Results & Insights** — Interpreting model outputs and identifying important features

---

## 🛠️ Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Key Libraries:**
  - `pandas`, `numpy` — data manipulation
  - `scikit-learn` — model building and evaluation
  - `matplotlib`, `seaborn` — visualization
  - `rdkit` *(if applicable)* — molecular descriptor computation

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

> If molecular descriptors from RDKit are used, install via conda:
> ```bash
> conda install -c conda-forge rdkit
> ```

### Running the Notebook

```bash
git clone https://github.com/Sarthak-Chauhan-Git/Drug-induced-cardiotoxicity-classification-model.git
cd Drug-induced-cardiotoxicity-classification-model
jupyter notebook Cardiotoxicity.ipynb
```

---

## 📊 Results

The model classifies drug compounds as **cardiotoxic** or **non-cardiotoxic** based on their chemical properties. Performance is evaluated on held-out test data using standard classification metrics.

---

## ⚠️ Disclaimer

This project is intended for research and educational purposes only. It should **not** be used as a substitute for clinical or regulatory safety assessments.

---

## 📄 License

This project is licensed under the [Apache License 2.0](LICENSE).

---

## 🙋 Author

**Sarthak Chauhan**
[GitHub Profile](https://github.com/Sarthak-Chauhan-Git)
