🧠 Mental Health Score Prediction

📌 Project Overview

Mental Health Score Prediction is a machine-learning-powered web application that analyzes lifestyle, behavioral, and personal factors to estimate a user's mental health score.

The project demonstrates how Python, Data Analysis, Machine Learning, FastAPI, and Web Development can be combined to build a practical predictive application.

«Note: This application is intended for educational and demonstration purposes only. The prediction should not be considered a medical diagnosis or professional mental-health assessment.»

---

🎯 Objectives

- Analyze factors associated with mental health.
- Clean and preprocess real-world data.
- Perform Exploratory Data Analysis (EDA).
- Identify important patterns and relationships.
- Train a machine-learning model to predict a mental health score.
- Build a user-friendly web interface for predictions.
- Deploy the application online using Render.

---

🛠️ Technologies Used

- Python
- Pandas – Data manipulation and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Scikit-learn – Machine Learning
- FastAPI – Backend API and web application
- Uvicorn – ASGI server
- HTML5
- CSS3
- JavaScript
- Git & GitHub
- Render – Cloud deployment

---

🔄 Project Workflow

Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Selection
   ↓
Data Preprocessing
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Saving
   ↓
FastAPI Application
   ↓
Web Interface
   ↓
Render Deployment

---

📊 Key Features

- User-friendly web interface
- Input-based mental health score prediction
- Data preprocessing and feature engineering
- Machine-learning model training
- Model evaluation
- Real-time prediction through FastAPI
- Responsive web interface
- REST API backend
- Cloud deployment using Render

---

🤖 Machine Learning

The project follows a standard machine-learning workflow:

1. Load the dataset.
2. Handle missing and inconsistent values.
3. Perform exploratory data analysis.
4. Select relevant features.
5. Encode categorical variables where required.
6. Split the dataset into training and testing sets.
7. Train the machine-learning model.
8. Evaluate model performance.
9. Save the trained model.
10. Load the model through FastAPI.
11. Generate predictions for new user inputs.

---

📁 Project Structure

Mental Health Score/
│
├── app.py
├── model.py
├── requirements.txt
├── README.md
├── Procfile
│
├── dataset/
│   └── Student Social Media And Mental Health Impact.csv
│
├── templates/
│   └── index.html
│
├── static/
│   ├── style.css
│   └── script.js
│
└── model/
    └── mental_health_model.pkl

---

🚀 How to Run Locally

1. Clone the Repository

git clone https://github.com/RadhikaBhedurkar/Mental-Health-Score.git

2. Navigate to the Project Folder

cd "Mental Health Score"

3. Create a Virtual Environment

python -m venv venv

4. Activate the Virtual Environment

Windows PowerShell

venv\Scripts\Activate.ps1

5. Install Dependencies

pip install -r requirements.txt

6. Run the FastAPI Application

For local development:

uvicorn app:app --reload

7. Open the Application

http://127.0.0.1:8000/

FastAPI Documentation

The automatically generated API documentation is available at:

http://127.0.0.1:8000/docs

---

☁️ Deployment on Render

The application can be deployed online using Render.

1. Push the Project to GitHub

Make sure your project contains:

app.py
requirements.txt
model/
templates/
static/

and push the project to GitHub.

git add .
git commit -m "Deploy mental health score prediction app"
git push origin main

---

2. Create a Render Web Service

1. Go to Render.
2. Sign in using your GitHub account.
3. Select New → Web Service.
4. Connect the repository:

Mental-Health-Score

5. Select the appropriate branch, usually:

main

---

3. Configure Render

Use the following settings:

Environment

Python

Build Command

pip install -r requirements.txt

Start Command

uvicorn app:app --host 0.0.0.0 --port $PORT

The "$PORT" variable allows Render to provide the port required by the deployed application.

---

4. Deploy

Click:

Create Web Service

Render will install the dependencies, build the application, and start the FastAPI server.

After successful deployment, Render provides a public URL similar to:

https://mental-health-score.onrender.com

You can use this URL to access the deployed application.

---

📦 Requirements

Example "requirements.txt":

fastapi
uvicorn
pandas
numpy
scikit-learn
matplotlib
seaborn
jinja2
python-multipart

Add any additional packages used by your application to "requirements.txt".

---

🔌 API

The FastAPI application provides an API endpoint for generating predictions.

FastAPI automatically provides interactive API documentation:

/docs

You can use the Swagger UI to test the prediction endpoint directly from your browser.

---

🌐 Deployment Architecture

User
  ↓
Web Browser
  ↓
Render
  ↓
FastAPI
  ↓
Machine Learning Model
  ↓
Prediction
  ↓
Web Response

---

📈 Future Improvements

- Improve model accuracy through hyperparameter tuning.
- Add additional mental-health-related features.
- Compare multiple machine-learning algorithms.
- Add model performance visualizations.
- Add authentication and user accounts.
- Improve UI/UX.
- Add database integration.
- Implement continuous deployment through GitHub.
- Add monitoring for the deployed application.

---

⚠️ Disclaimer

This project is created for educational and demonstration purposes.

The predicted score is generated by a machine-learning model and should not be used as a medical diagnosis or replacement for professional mental-health advice.

---

👩‍💻 Author

Radhika Bhedurkar

Data Analyst & Data Science Enthusiast

🔗 GitHub: https://github.com/RadhikaBhedurkar

🔗 LinkedIn: https://www.linkedin.com/in/radhika-bhedurkar

---

⭐ If You Like This Project

If you find this project useful, consider giving the repository a ⭐ on GitHub!
