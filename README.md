# Predictive-Modeling-for-Agriculture
A farmer asked a machine learning expert for help choosing the best crop for his field but could only afford to measure one soil property: nitrogen, phosphorous, potassium, or pH. This becomes a feature selection problem, aiming to identify the single most important soil feature for accurate crop prediction.
🌾📊 Predictive Modeling for Agriculture | Feature Importance Analysis

This assignment focused on solving a practical agricultural challenge: helping farmers choose the best crop while minimizing soil testing costs. Since measuring all soil metrics can be expensive, the goal was to determine which single soil feature provides the strongest predictive power.

📁 Dataset Used: soil_measures.csv
Features: Nitrogen (N), Phosphorous (P), Potassium (K), pH
Target: Crop type (multi-class, 22 categories)

🔍 Methodology:
• Loaded and inspected the dataset (no missing values, clean labels)
• Performed basic exploratory data analysis
• Split the data into training and test sets using stratified sampling
• Trained four independent multi-class classification models, each using only one soil feature
• Evaluated each model using accuracy to ensure fair comparison
• Stored results in a performance dictionary and identified the top feature

📈 Key Result:
The model trained using Potassium (K) alone consistently outperformed the others, making it the most predictive single soil metric for crop classification in this dataset.

🌱 Why it matters:
This project demonstrates how machine learning can support cost-effective decision-making in agriculture, enabling farmers to prioritize the most impactful soil test while still maximizing crop yield.

