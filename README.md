Customer Churn Prediction Web App with Real-Time Power BI Dashboard

Project Overview 🚀

This is a full-stack, end-to-end data analytics and machine learning project focused on predicting customer churn in the telecom industry. The application provides a user-friendly interface for real-time churn prediction, with live results pushed to a dynamic Power BI dashboard.

The project demonstrates a seamless integration of machine learning models, web development, and business intelligence to create a practical, production-ready solution.

Features ✨

1. Real-time Prediction: Instantly predict customer churn status based on user input.

2. Live Analytics: A Power BI dashboard updates in real time with each new prediction.

3. Intuitive UI: A clean, user-friendly web interface for inputting data.

4. Robust Backend: A Flask backend handles the machine learning model and API integration.

5. Full-Stack Deployment: The entire application is deployed and publicly accessible.

Tech Stack 🛠️

1. Backend: Python, Flask, Random Forest, REST API

2. Database: SQL (for data cleaning and preparation)

3. Frontend: HTML, CSS

4. Analytics & Visualization: Power BI (Streaming Dataset, REST API, iframe)

5. Deployment: Render

Project Structure and Workflow :

1. Data Cleaning & Preparation : The project began with a crucial data cleaning and transformation phase using SQL. This involved handling missing values, encoding categorical features, and preparing the raw telecom customer data to be used by the machine learning model.

2. Machine Learning Model : A Random Forest classification model, developed in Python, serves as the core of the prediction engine.
Why Random Forest? Its strong performance on both numerical and categorical data, resistance to overfitting, and ability to provide feature importance made it an ideal choice for this use case.

3. Web Application : A Flask web application was built to serve as the user-facing interface. It allows users to input customer details and submit them to the backend for prediction.

4. Real-Time Power BI Integration : The most innovative part of the project is the real-time analytics dashboard. A Power BI Streaming Dataset was created to receive live data. A REST API endpoint in the Flask app pushes new prediction data to Power BI. The interactive Power BI dashboard is embedded directly into the web app using an <iframe> with the "Publish to Web" feature.

5. Deployment : The entire application, including the Flask backend and web interface, was deployed on Render for easy public access and a production-ready environment.

Collaboration 🤝

This was a collaborative effort.
Soham Kalsi focused on developing the machine learning model and managing the Flask backend logic.
I focused on designing the Power BI dashboard, configuring real-time streaming, and integrating it into the web app.
Together, we ensured the system was scalable, cleanly designed, and production-ready.

How to Run Locally 💻

1. Clone the repository:
   
   git clone [your_github_repo_link]
   
2. Navigate to the project directory:

   cd [your_project_folder]

3. Create and activate a virtual environment (recommended).

4. Install the required packages:

   pip install -r requirements.txt

5. Run the Flask application:

   python app.py


Live Demo : 

Live Project: [https://lnkd.in/dy6KxYWX](https://customer-churn-prediction-g0xf.onrender.com/)

Demo Video: A short video showcasing the full end-to-end flow is available on my LinkedIn post.

Contact : 

Sahil : https://www.linkedin.com/in/sahil-bhardwaj-24b2082b6/

Soham Kalsi: https://www.linkedin.com/in/sohamkalsi/












