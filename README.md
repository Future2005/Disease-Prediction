# AI-Powered Health Advisor

Overview:
MediMate is an AI-powered web application that provides users with instant medical insights based on symptoms they input. The system uses machine learning to predict possible diseases and offers personalized recommendations including medication suggestions, diet plans, precautions, and fitness routines. It bridges the gap between health awareness and actionable guidance.

Key Highlights:
1.Symptom-Based Disease Prediction:
Users enter their symptoms through a simple interface. The backend ML model processes this input to predict the most likely illness.
2.Tailored Medical Guidance:
Based on the predicted condition, MediMate recommends the top 5 medicines (non-branded/common names), necessary precautions, a suitable diet, and a basic workout plan for recovery and well-being.
3.Flask Web App Interface:
The application is built using Flask and runs locally in a web browser. It is lightweight, fast, and user-friendly.
4.Machine Learning Backbone:
The predictive model is trained on a structured dataset using a Support Vector Classifier (SVC). It ensures accurate and relevant output based on the symptoms entered.
5.Data Privacy Focused:
MediMate does not store or share any user data. All symptom inputs are processed in real time, ensuring confidentiality and security.

Tech Stack:
Frontend: HTML, CSS (Bootstrap)
Backend: Python, Flask
ML Libraries: scikit-learn, pandas, numpy, joblib
Model: Support Vector Classifier (SVC)
Others: Jupyter Notebook (for model training), CSV dataset

How to Use:
Clone the repository and navigate to the project directory.
Create a virtual environment and install dependencies from requirements.txt.
Run python app.py to start the server.
Enter your symptoms and get your personalized health recommendations.

Project Structure:
app.py: Main application file (Flask backend)
dataset.csv: Training dataset for disease prediction
model/: Contains the trained ML model file
templates/: HTML pages for the UI
static/: CSS, images, and other static resources
utils.py: Helper functions for prediction and model loading
requirements.txt: List of Python dependencies

Future Enhancements:
Integration with a secure user login system
Option to download a summary report of recommendations
NLP-powered chatbot interface
Hosting the app online with user data tracking (with consent)


