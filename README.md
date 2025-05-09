# Breast Cancer Death Probability Prediction

This Flask application predicts the 5-year death probability of breast cancer patients using machine learning models. The model is based on patient data, including:
- **Age**
- **Year of Operation**
- **Number of Axillary Nodes**

The prediction helps in understanding the survival chances of patients based on these key factors.

## 🧭 Overview

This Flask app demonstrates how to deploy a machine learning model for predicting the 5-year death probability of breast cancer patients. It allows users to input patient data and receive the prediction using a trained machine learning model.

## 🔧 Project Structure

Flask/
├── app.py # Main Flask app to handle routes and model inference
├── templates/ # HTML templates for user input forms
│ └── index.html # Homepage template for input form
├── static/ # Static files (CSS, JS, images)
│ └── styles.css # Custom styling for the app (if applicable)
├── model/ # Folder containing the trained machine learning model
│ └── breast_cancer_model.pkl # Saved ML model
└── requirements.txt # Python dependencies

bash
Copy
Edit

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/wanglmnju/Flask.git
cd Flask
2. Create Virtual Environment (Optional but recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Load the Model (if not done already)
Make sure the machine learning model (breast_cancer_model.pkl) is placed in the model/ folder or any directory you prefer.

5. Run the App
bash
Copy
Edit
python app.py
Then visit http://127.0.0.1:5000/ in your browser to use the app.

📦 Dependencies
Flask

scikit-learn (for machine learning)

pandas

numpy
