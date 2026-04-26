# Multiple Disease Prediction System

## Overview
This project is a Machine Learning based web application built using Django that predicts multiple diseases based on user input.

### Diseases Supported
- Diabetes Prediction
- Heart Disease Prediction
- Liver Disease Prediction
- Kidney Disease Prediction
- Brain Disease (Alzheimer's) Prediction
- Lung Disease / Asthma Prediction

## Tech Stack
- Python
- Django
- Machine Learning
- Pandas
- NumPy
- Pickle
- HTML/CSS
- SQLite

## Features
- User-friendly disease prediction forms
- Multiple ML models integrated
- Real-time prediction results
- Web-based interface
- Separate modules for each disease

## Project Structure
```bash
final_project/
│── app/
│   ├── models/          # Trained ML models (.pkl)
│   ├── templates/       # HTML pages
│   ├── static/          # CSS files
│   ├── views.py
│   └── urls.py
│
│── final_project/
│   ├── settings.py
│   ├── urls.py
│
└── manage.py
```

## Installation

### 1 Clone Repository
```bash
git clone https://github.com/your-username/multiple-disease-prediction.git
cd multiple-disease-prediction/final_project/final_project
```

## Create Virtual Environment
```bash
python -m venv venv
```

Activate environment:

Windows:
```bash
venv\Scripts\activate
```

Linux/Mac:
```bash
source venv/bin/activate
```

## Install Dependencies
```bash
pip install django pandas numpy scikit-learn
```

(Or use requirements.txt if added)

```bash
pip install -r requirements.txt
```

## Run Migrations
```bash
python manage.py migrate
```

## Run Project
```bash
python manage.py runserver
```

Open browser:
```bash
http://127.0.0.1:8000/
```

## How It Works
1. User selects disease prediction module.
2. Enter required medical parameters.
3. Trained ML model processes input.
4. Prediction result is displayed instantly.

## Machine Learning Models Used
Stored in:
```bash
app/models/
```

Models:
- diabetes.pkl
- heart.pkl
- liver.pkl
- kidney.pkl
- brain.pkl
- asthama.pkl

## Future Improvements
- Add authentication
- Improve model accuracy
- Deploy on cloud
- Add more disease predictions

## Author
Nishant
