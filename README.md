# Smart Crop Planner – Recommendation & Yield Predictor
# Introduction
This project is a dual-function Machine Learning system designed to assist farmers and agricultural professionals. It provides:

Smart crop recommendations based on soil and weather parameters.

Crop yield prediction for a selected crop and year.

It combines both classification and regression models to create a complete agriculture advisory system.

# Objective
Recommend the most suitable crop based on soil and climate conditions.

Predict the estimated crop yield (in quintal/hectare) for a given year.

Help farmers in making data-driven decisions for better productivity.

 # Methodology
Two models were built:

✅ Crop Recommendation
→ RandomForestClassifier trained on:
Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, Rainfall
→ Output: Recommended Crop

✅ Crop Yield Prediction
→ RandomForestRegressor trained on:
Crop Name and Year
→ Output: Expected Yield (quintal/hectare)

 # Tools & Technologies Used
Language: Python

Environment: Jupyter Notebook

Libraries: pandas, numpy, scikit-learn, ipywidgets

Models: RandomForestClassifier, RandomForestRegressor

UI: IPython Widgets (No external UI framework used)

 # Dataset Details
Crop Recommendation Dataset:
Contains features like N, P, K, temperature, humidity, pH, rainfall, and crop label.

Crop Yield Dataset:
Crop-wise yield data by year (quintal/hectare). Cleaned manually for accurate prediction.

# Results
Model recommends the best crop with high accuracy using RandomForestClassifier.

Yield prediction is done using RandomForestRegressor with acceptable RMSE and good R² score.

Integrated both models into a single Jupyter Notebook interface for easy use.

# Future Scope
Integrate real-time data from soil sensors or weather APIs.

Add market price prediction for recommended crops.

Build mobile or web app for deployment in villages.

Include GPS-based location prediction for hyperlocal suggestions.

# Conclusion
This project applies machine learning to the agricultural domain for practical and impactful use.
It empowers farmers to choose the right crop and plan the expected yield, contributing to precision farming and increased productivity.
