
# Vehicle Price Prediction System

## Overview
The Vehicle Price Prediction System is a machine learning-based web application that predicts vehicle prices using various input features such as horsepower, torque, brand, body style, drivetrain, and transmission type. The application is built using Python and Streamlit, providing an interactive and user-friendly interface for real-time predictions.

---

## Features
- Predicts vehicle prices instantly
- Interactive Streamlit user interface
- Feature importance visualization using Plotly
- Machine learning regression model
- Easy deployment using Streamlit Cloud

---

## Technologies Used
- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Plotly
- Pillow

---

## Project Structure

```bash
car-price-prediction/
│
├── app.py
├── linear_model.pkl
├── feature_importance.xlsx
├── requirements.txt
├── pic1.png
├── pic2.png
└── README.md
````

---

## Installation

### Clone Repository

```bash
git clone https://github.com/17sukh/car-price-prediction.git
cd car-price-prediction
```

### Create Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Application

```bash
streamlit run app.py
```

The application will open in your browser at:

```bash
http://localhost:8501
```

---

## Input Features

* Horsepower
* Torque
* Brand
* Body Size
* Body Style
* Engine Aspiration
* Drivetrain
* Transmission

---

## Output

* Predicted vehicle price
* Feature importance graph

---

## Dataset

Dataset used from Kaggle:

Car Features and MSRP Dataset
[https://www.kaggle.com/datasets/CooperUnion/cardataset](https://www.kaggle.com/datasets/CooperUnion/cardataset)

---

## Deployment

This project can be deployed using Streamlit Community Cloud.

Deployment Steps:

1. Push project to GitHub
2. Login to Streamlit Cloud
3. Select repository
4. Deploy `app.py`

---

## Future Improvements

* Add multiple ML models
* Improve UI/UX design
* Add real-time market data
* Support more vehicle brands
* Add prediction confidence score

