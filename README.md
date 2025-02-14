# 20592_Spatial-Heterogeneity-Real-Estate
Exploring spatial heterogeneity in real estate pricing using Bayesian hierarchical mixed-effects models. This project leverages advanced statistical modeling and probabilistic programming (PyMC) to analyze the variable impact of house features across Melbourne's council areas.

📖 Overview

Understanding the spatial variability of real estate prices is crucial for policymakers, businesses, and investors. 
This project explores how house features (e.g., number of bedrooms, parking spaces, and distance to the city center) have different effects on house prices across Melbourne's council areas.

🎯 Research Goal

We investigate whether the impact of house features varies geographically by implementing a hierarchical Bayesian mixed-effects model using PyMC. 

This approach helps us:
- Identify key housing characteristics affecting price variation.
- Model the spatial heterogeneity of these effects.
- Improve real estate price forecasting with a robust probabilistic approach.

🗂 Dataset

Source: Melbourne housing dataset (13,580 observations, 21 features).

Key Variables: Price, BuildingArea, CouncilArea, Distance, Car, Bathroom, Bedroom2, Month.

Preprocessing: Bayesian imputation for missing values, outlier removal (IQR filtering), standardization.

🛠 Methodology

Hierarchical Bayesian Modeling (PyMC)

Mixed-Effects Model with spatial random slopes

Conditional Autoregressive (CAR) Prior for spatial dependencies

Inference using No-U-Turn Sampler (NUTS) for robust MCMC estimation

📊 Key Findings

The effect of Distance on price varies the most across council areas, confirming spatial heterogeneity.

Bedroom count has a strong positive impact, but its influence fluctuates by location.

The impact of building area remains relatively uniform, suggesting less spatial dependency.

🚀 Technologies Used

- 🐍 Python (NumPy, Pandas, Matplotlib, Seaborn)
- 🔮 PyMC for Bayesian modeling
- 📊 Statistical analysis & visualization
- 🏡 Spatial econometrics techniques
