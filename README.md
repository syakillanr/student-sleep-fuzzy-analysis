# student-sleep-fuzzy-analysis
Project Title: Student Sleep Quality Analysis using Fuzzy Logic

Objective: Developing a rule-based AI system to classify university students' sleep quality based on lifestyle factors like caffeine intake, screen time, and study hours. 

Dataset: https://www.kaggle.com/datasets/arsalanjamal002/student-sleep-patterns 

Overview
This project applies a Fuzzy Logic Framework to a dataset of 500 students to translate subjective lifestyle data into actionable insights. While many AI models are "black boxes," this fuzzy inference system provides transparency through human-readable IF-THEN rules.




The Fuzzy Framework
The system is built using the following modules:


Fuzzification: Converting crisp inputs (e.g., hours of sleep) into membership degrees (Low, Medium, High) using triangular and trapezoidal functions.


Rule Base: 10 linguistic rules defining sleep health, such as:


IF sleep duration is low OR caffeine intake is high, THEN sleep quality is poor. 


IF physical activity is high, THEN sleep quality is good. 


Defuzzification: Using the Centroid of Area (CoA) method to produce a final Sleep Quality score.


Key Results

Accuracy: The model achieved a 48.0% prediction accuracy.



Insights: Analysis confirmed that excessive caffeine and study hours were primary drivers of "Poor" sleep quality, while physical activity and moderate study hours boosted "Good" sleep outcomes.

Technologies Used
Language: Python


Libraries: scikit-fuzzy for inference, pandas for data handling, numpy for mathematical operations
