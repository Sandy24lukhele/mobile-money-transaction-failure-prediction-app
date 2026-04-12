# mobile-money-transaction-failure-prediction-app
Project Description: This project is a Machine learning-based system designed detect and mitigating mobile money transaction failures  for telecom providers such as MTN Eswatini. Its analysis transaction patterns and predict possible failures in realtime to improvereliability and user experience. (Flask, MySQL, Scikit-learn)
Problem Statement: Mobile money users often experience transaction failures due to network issues, system and user errors, or congestion. These failures reduce trust and cause financial inconvenience.
Objectives:Detect transaction failures using machine learning ,Analyze causes of failed transactions,Provide mitigation strategies 
Improve success rate of transactions

Technologies Used: 

Backend: Python (Flask)
Machine Learning: Scikit-learn / Pandas / NumPy
Database: MySQL workbench 
Frontend: HTML, CSS, Bootstrap
IDE: VS Code

project structure:
project-folder/
 app/                  # Flask application
   routes.py         # Application routes
     models.py         # Database models
      templates/        # HTML files
       static/           # CSS, JS, images

  data/                 # Dataset used
  model/                # Trained ML model
  database/             # Database files 
  requirements.txt      # Dependencies
  run.py                # Main entry point
  README.md             # Documentation

 How to Run the Project:
1. Clone the repository
2. Navigate to the project folder
3. Install dependencies:
   pip install -r requirements.txt
4. Run the application:
   python app.py
5. Open browser:
   http://127.0.0.1:5000/

   Future Improvements:
  1. Deploy system to cloud
 2.Integrate with real telecom APIs  3.Enhance UI/UX
 4. Use real-time streaming data
 
