# Garbage-Classifier
Project Description:
The Garbage Classification Project aims to develop a system that can classify different types of waste
materials, such as glass, paper, cardboard, plastic, metal, and trash, from images. This project can be
used to improve recycling processes, enhance waste management, and contribute to environmental
sustainability.

Methodology:
Data Collection: The project starts with collecting a dataset of images containing various waste
materials. Each image is labeled with the corresponding waste type.
Image Preprocessing: Image preprocessing techniques are applied to standardize the dataset. This
includes resizing images and normalizing them to ensure consistency in the dataset.
Feature Extraction: Principal Component Analysis (PCA) is used to reduce the dimensionality of the
image data. This process extracts the most important features from the images, preserving their
variance.

Machine Learning Models:
Gaussian Naive Bayes: A Gaussian Naive Bayes classifier is employed to classify the waste materials
based on the reduced feature set.
k-Nearest Neighbors (k-NN): A k-NN classifier is trained to make predictions on the type of waste
material in an image.
Support Vector Machine (SVM): A One-Versus-Rest (OvR) SVM classifier is used for multi-class
classification of waste materials.
Evaluation: The models' performance is evaluated using metrics such as accuracy, precision, recall,
and F1-score. Confusion matrices provide insights into the classification results.

Technology Stack:
Programming Language: Python
Libraries and Frameworks: scikit-learn, NumPy, pandas, joblib, Flask, Flask-NGROK
Web Interface: Flask is used to create a web-based GUI to upload images for classification.
Deployment: Pyngrok is used for tunneling the Flask app to the web.
Graphical User Interface (GUI): A web-based GUI is created using Flask, where users can upload
images of waste materials. The GUI allows users to see the results of the classification process, i.e,
type of waste material.

Results:
The machine learning models have been trained to classify waste materials with a high degree of
accuracy.
Users can upload images through the web interface, and the system provides real-time classification
results.
The project contributes to waste management and recycling efforts by automating the classification
process, making it more efficient and reliable.
Specific performance results and metrics would be available upon evaluating the models with a test
dataset.

This project serves as a practical solution for waste material classification and can be used in real-
world scenarios to enhance recycling and waste management practices.
