# Diagnosify-Disease-Prediction-Using-Symptoms

Overview: This project is a AIML-based application that predicts the most likely disease based on the symptoms and other inputs that are provided by the user/patient. The system is built using Python and various relevant libraries such as scikit-learn, pandas, NumPy, Matplotlib, etc., . The program asks the user a series of questions about their symptoms, and issues, it processes those inputs, and then predicts the disease with most probablity with an accuracy rate of more than 85%. This tool aims to provide a preliminary diagnosis, offering users an insight into potential health issues before visiting a healthcare professional. Basically there will be two datasets one with the symptoms and another with the related diseases, the symptoms dataset is mapped with the diseases dataset so that when the user enters one or more symptoms the trained model will predict the most probable disease. Features:

Symptom-Based Disease Prediction: Users input their symptoms, and the program predicts the most likely disease.
Interactive Questionnaire: A user-friendly interface that guides users through symptom-related questions, providing an intuitive experience.
Data-Driven Insights: The system utilizes a trained machine learning model that can handle large sets of symptoms to provide accurate predictions.
High Accuracy: The model has been trained with medical data to achieve an accuracy of around 85%, offering reliable disease predictions.
Implementation:

The application is built using Python, a popular language for data science and machine learning. Key libraries employed include:

scikit-learn: A comprehensive machine learning library for tasks such as classification (disease prediction in this case).
pandas: A powerful data manipulation and analysis library for handling and cleaning symptom data.
NumPy: A fundamental library for numerical computations, providing efficient operations on arrays and matrices.
Matplotlib: A versatile plotting library for visualizing data and results, aiding in understanding the model's performance.
Workflow:

Data Collection: A dataset of patient symptoms and corresponding diagnoses is gathered or created.
Data Preprocessing: The data is cleaned, normalized, and transformed into a suitable format for the machine learning model.
Model Training: A machine learning algorithm, such as a decision tree, random forest, or neural network, is trained on the preprocessed data to learn the relationship between symptoms and diseases.
Model Evaluation: The trained model's performance is evaluated using metrics like accuracy, precision, recall, and F1-score to assess its predictive capabilities.
Application Development: A user interface is created to allow users to input their symptoms. The trained model then processes the input and provides the predicted disease.
Applications:

Personal Health Management: Individuals can use the application for self-assessment and to gain insights into potential health concerns.
Healthcare Assistance: The application can aid healthcare providers in patient triaging, initial diagnosis, and patient education.
Medical Research: Researchers can leverage the application to analyze disease patterns and improve the predictive model.
Public Health Initiatives: The application can contribute to disease surveillance and promote preventive health measures.
Remote Healthcare: It can facilitate remote health consultations and provide preliminary diagnoses in areas with limited healthcare access.
