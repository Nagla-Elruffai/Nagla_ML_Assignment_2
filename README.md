Assignment Report Part 1: Wine Quality Classification

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

<br><br><br><br>

Assignment Report Part 2

<b> 1. Digit Classification (MNIST Dataset) </b> <br>
We evaluated multiple models on the MNIST digit classification dataset (images of handwritten digits, 28x28 pixels).
<img width="973" height="202" alt="image" src="https://github.com/user-attachments/assets/1139d408-6d2f-437d-894c-8c7ce215bd9d" />


Model Performance:
Logistic Regression: <b>92.02% accuracy</b>. A strong baseline but limited by its linear nature on pixel values.<br><br>
Random Forest Classifier: <b> 96.75% accuracy </b>. Robust and non-linear, though computationally heavier to train on large feature vectors.<br><br>
Multi-Layer Perceptron (MLP Neural Network): <b> 97.55% accuracy. </b> Outperformed classical machine learning approaches by learning non-linear feature representations.<br><br>
Convolutional Neural Network (CNN): <b> Achieved ~99.02% validation accuracy </b> within 5 training epochs. CNNs leverage spatial hierarchies (via convolution and pooling layers), making them the top-performing model for spatial image data.<br><br>
 
<b> 2. Object Detection & Face Detection (YOLOv5)</b><br>

Using a pre-trained state-of-the-art YOLOv5s (small) deep learning model, we performed real-time object detection on multiple scenes:

Personalized Face Detection: <br>

I Uploaded my selfie where the YOLOv5 model accurately detected my face as a person with 79% confidence (person 0.79).
<br><br>
<img width="797" height="858" alt="image" src="https://github.com/user-attachments/assets/337f37b9-86aa-4d9a-9253-6c33536cb062" />
