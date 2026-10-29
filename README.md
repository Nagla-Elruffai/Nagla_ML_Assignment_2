Assignment Report: Wine Quality Classification

1. Overview
In this assignment, we explored and classified wine samples from the Italian Wine Dataset using three machine learning models: Support Vector Machine (SVM), Decision Tree, and Logistic Regression.

2. Dataset
Features: 13 chemical features (such as alcohol levels, malic acid, ash, color intensity, and proline).
Classes: 3 classes of wine cultivars.
Size: 178 samples (split into 70% training and 30% testing).

3. Preprocessing
Standardized features using StandardScaler to handle differing scales across chemical measurements.

4. Model Evaluation
Model	Features Used	Test Accuracy

Logistic Regression	First 2 Features (Alcohol, Malic Acid) = 98.1%

<img width="565" height="455" alt="image" src="https://github.com/user-attachments/assets/c2f85f35-db6f-4121-a530-f741b4428a88" />

Decision Tree	All 13 Features = 94.4%

<img width="755" height="589" alt="Screenshot 2026-10-29 at 3 27 24 PM" src="https://github.com/user-attachments/assets/5ac8ca36-a1e9-40d3-b079-927d08d75dce" />


6. Key Findings
   
Top Performance: The Logistic Regression model achieved a remarkable 98.1% accuracy using only the first two features (Alcohol and Malic Acid), indicating these are highly descriptive features.
Model Interpretability: The Decision Tree reached 94.4% accuracy and provided an easily interpretable, visual rule set showing major decision splits based on features like color_intensity.
