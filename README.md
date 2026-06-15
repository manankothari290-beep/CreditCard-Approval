# Credit Card Approval Prediction

🔗 **Live Demo:** [https://credit-card-eight-gamma.vercel.app](https://credit-card-eight-gamma.vercel.app)

A Machine Learning web application that predicts whether a credit card application will be **Approved** or **Not Approved** based on applicant details such as income, education, employment, credit history, and more.

## Features

- **ML-Powered Predictions** — Uses a Decision Tree Classifier trained on real credit card application data
- **Interactive Web Form** — Easy-to-use form to input applicant details
- **Instant Results** — Get approval prediction in seconds

## Tech Stack

- **Backend:** Python, Flask
- **ML:** scikit-learn, pandas, NumPy
- **Deployment:** Vercel (Serverless)

## How to Run Locally

```bash
cd "Credit_Card_Approval_Project/5. Project Executable Files"
python3 app.py
```

Then open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

## Project Structure

```
├── api/                        # Vercel serverless deployment
│   ├── index.py                # Flask app entry point
│   ├── model/                  # Trained ML model
│   └── templates/              # HTML templates
├── Credit_Card_Approval_Project/
│   ├── 1. Project Initialization and Planning Phase/
│   ├── 2. Data Collection and Preprocessing Phase/
│   ├── 3. Model Development Phase/
│   ├── 4. Model Tuning and Optimization Phase/
│   ├── 5. Project Executable Files/
│   └── 6. Documentation and Demonstration/
├── vercel.json                 # Vercel configuration
└── requirements.txt            # Python dependencies
```

## Team

Prepared by — **Mehul, Manan, Pratyaksh**
