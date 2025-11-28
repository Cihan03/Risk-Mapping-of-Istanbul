# Risk Mapping of Istanbul
Earthquake Risk Analysis Using Machine Learning, SHAP, and LIME

This project aims to estimate and visualize the relative earthquake risk levels across Istanbul’s 39 districts using a combination of geospatial data, machine learning models, and explainable AI methods.

Note: This project was developed during my Erasmus exchange semester at Leuphana Universität Lüneburg (Germany), as part of the “Explainable AI & Visualization” course.

# Objectives

Build a district-level risk scoring system using multiple demographic & geospatial features.
Train machine learning models to classify districts into Low, Medium, and High risk.
Use SHAP and LIME to provide model interpretability.
Produce an interactive and visual earthquake risk map of Istanbul.

# Main Features Used

Etki_Skoru — historical earthquake impact
Fay_Skoru — distance to fault lines
Rakım_Skoru — elevation
Nüfus_Yogunlugu — population density
Bina_Yogunlugu — building density
Bina_Yasi_Skoru — average building age
Kat_Skoru — building height
Zemin_Skoru — soil quality
Yesilsiz_Alan_Skoru — lack of green areas
Altyapi_Skoru — district-level infrastructure (hospitals, etc.)

All features were normalized between 0–1.

# Machine Learning Models

The following models were trained:

Model	Accuracy
Logistic Regression	0.75
Decision Tree	0.56
Random Forest	0.75

# Explainable AI: SHAP & LIME

To understand why the model makes certain predictions.

# Geographic Visualization

A final risk map was created using GeoPandas and Folium. This map highlights the spatial risk distribution across Istanbul’s 39 districts.

# How to Run the Project

1. Install the required Python packages: pip install -r requirements.txt
2. Launch Jupyter Notebook: jupyter notebook notebooks/PROJECT-CihanOzkan.ipynb

# Notes

This project is intended for educational and research purposes.
Risk scores are relative, not absolute earthquake predictions.
Maps use publicly available administrative boundary data.

# Author

Cihan Özkan
Management Information Systems (MIS)
Marmara University & Erasmus Exchange Student at Leuphana Universität Lüneburg (Germany)
