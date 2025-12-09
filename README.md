# Predicting Coastal Plastic Waste Risk Using Random Forest

This project applies supervised machine learning to classify country-level coastal plastic waste risk using environmental and socioeconomic indicators across 165 countries. A Random Forest classifier is trained to categorize nations into four risk levels — **Low, Medium, High, and Very High** — to support sustainability screening and policy prioritization.

---

## 🔍 Project Overview

Marine plastic pollution poses a major threat to coastal ecosystems, human health, and tourism-dependent economies. Risk levels are influenced by complex interactions among waste generation patterns, recycling infrastructure, and consumption behavior.

This project uses data science to:
- Explore global plastic waste trends through statistical analysis.
- Build a predictive classification model for coastal waste risk.
- Evaluate model performance on real-world environmental data.
- Derive interpretable insights for decision-making.

---

## 📊 Dataset

The dataset contains cross-sectional waste indicators for **165 countries**, including:

- **Per Capita Plastic Waste (kg)**
- **Recycling Rate (%)**
- **Total Plastic Waste (million tons)**
- **Primary Waste Sources**
- **Coastal Waste Risk Labels** *(Low, Medium, High, Very High)*

---

## 🧪 Exploratory Data Analysis (EDA)

Key EDA findings:

- Waste generation and per-capita consumption show **high right-skewness**, driven by a few extreme producer countries.
- **Median recycling rate = 5.4%**, while the global average is **13.1%**, highlighting major infrastructural gaps.
- **Per-capita waste showed extreme variance**, with outliers exceeding 1,500 kg/person/year.

Descriptive statistics (mean, median, and standard deviation) guided feature understanding and justified the use of tree-based models capable of handling skewed distributions and nonlinear interactions.

---

## 🤖 Methodology

### Modeling Pipeline
1. Data preprocessing and feature standardization  
2. Train-test split (**80/20**)  
3. Random Forest classifier training  
4. Cross-class prediction  
5. Model evaluation

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Macro and weighted averages

---

## ✅ Results

- **Overall accuracy:** 63.6%  
- High-risk category achieved strong performance (**F1 = 0.79**)  
- Perfect classification of the **Very High-risk category**, though limited by severe class imbalance  
- Moderate performance in Medium- and Low-risk categories due to overlap and boundary labeling ambiguity

---

## 🧠 Tools & Technologies

All analysis and modeling were performed using:

- **Python**
- **Pandas & NumPy** – Data processing
- **Scikit-learn** – Modeling and evaluation
- **Matplotlib & Seaborn** – Visualization

Reproducibility was ensured with fixed random seeds and standardized workflows.

---

## 📌 Key Insights

- Machine learning is effective for **screening high-risk coastal waste regions**.
- Nonlinear feature relationships are well captured by Random Forests.
- Class imbalance and threshold-based labels remain key modeling challenges.
- Feature importance supports **interpretable policy guidance**.

---

## 🚀 Future Improvements

Planned extensions include:

- Applying **SMOTE or weighted classifiers** to handle class imbalance.
- Incorporating **geospatial data** for finer regional analysis.
- Evaluating **boosting algorithms** (XGBoost, LightGBM) for performance comparison.
- Using **time-series data** to analyze policy trends over multiple years.

---

## 📜 Author

**Lasisi Romoke Adunbarin**  
Data Scientist & Tech Educator  
Research focus: environmental analytics, machine learning for sustainability, and data-driven policy insights.

---

## 📄 License

This project is open for academic, research, and educational use.  


