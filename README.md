
# Data-Driven Supply Chain Analytics

A collection of data-driven supply chain projects developed in Python, exploring how statistical methods, optimization, and machine learning can support decision-making under demand uncertainty.

The projects progress from fundamental demand analysis and data-driven optimization to contextual modeling, regression, time-series features, and tree-based machine learning.

---

## Projects

### 1. Statistical Demand Modeling
`statistical-demand-modeling.ipynb`

Analysis of historical demand patterns and uncertainty using descriptive statistics and variability measures. The project evaluates demand distributions and compares decision strategies under asymmetric costs.

**Key methods:**  
`Descriptive Statistics` · `Coefficient of Variation` · `Demand Analysis` · `Cost Evaluation`

---

### 2. Sample Average Approximation
`sample-average-approximation.ipynb`

Data-driven optimization using historical demand observations. The project analyzes service levels, underage and overage costs, salvage values, and applies Sample Average Approximation to determine optimal decisions from empirical demand data.

**Key methods:**  
`Sample Average Approximation (SAA)` · `Empirical Distributions` · `Service-Level Analysis` · `Cost Optimization`

---

### 3. Feature-Based SAA Modeling
`feature-based-saa-modeling.ipynb`

Extension of Sample Average Approximation through contextual demand segmentation. Demand observations are grouped using features such as season and weekday, allowing decisions to adapt to different demand environments.

The project also examines the trade-off between model flexibility and generalization when increasingly granular feature combinations are introduced.

**Key methods:**  
`Contextual Features` · `Demand Segmentation` · `Feature Engineering` · `SAA` · `Model Evaluation`

---

### 4. Linear Regression & Time-Series Modeling
`linear-regression-modeling.ipynb`

Predictive modeling using contextual and temporal information. Linear regression models are trained with numerical and categorical features and extended through interaction terms.

The project also investigates temporal demand dependencies using autocorrelation and lagged demand features, connecting predictive modeling with data-driven operational decisions.

**Key methods:**  
`Linear Regression` · `One-Hot Encoding` · `Feature Engineering` · `Interaction Terms` · `Autocorrelation` · `Lagged Features`

---

### 5. Decision Trees & Random Forests
`decision-tree-random-forest.ipynb`

Application of tree-based machine learning models to data-driven decision-making. Decision Trees and Random Forests are trained and compared using different hyperparameter settings.

Validation performance is used to investigate model complexity, robustness, and the effect of overfitting on decision quality.

**Key methods:**  
`Decision Trees` · `Random Forests` · `Hyperparameter Tuning` · `Validation` · `Model Comparison`

---

## Tech Stack

**Language & Environment**  
`Python` · `Jupyter Notebook`

**Data & Machine Learning**  
`NumPy` · `pandas` · `scikit-learn`

**Optimization & Decision Modeling**  
`PuLP` · `ddop`

---

## Skills Demonstrated

- Exploratory and statistical demand analysis
- Data-driven optimization under uncertainty
- Feature engineering and contextual modeling
- Machine learning model development
- Time-series feature analysis
- Hyperparameter tuning and model validation
- Translating predictive models into operational decisions
- Comparing models based on decision costs rather than predictive accuracy alone

---

## About

These projects were completed as part of coursework in **Data-Driven Supply Chain Management** and demonstrate the progression from statistical demand analysis to machine-learning-based decision models.
