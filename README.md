# Diabetes Prediction Using Machine Learning

## 📌 Overview
This project predicts the likelihood of diabetes in patients using machine learning. It includes a trained model and a Streamlit web application for easy interaction. The model uses historical medical data to identify patterns that indicate the presence of diabetes. The web app provides an intuitive interface for users to input their health metrics and get instant predictions.

## 📊 Methodology
1. **Data Collection**: The dataset used consists of multiple health parameters such as age, BMI, glucose level, and HbA1c levels.
2. **Data Preprocessing**: Handling missing values, normalizing numerical data, and encoding categorical features.
3. **Feature Engineering**: Selecting the most relevant features that influence diabetes prediction.
4. **Model Training**: A Logistic Regression model is trained on the dataset to classify patients as diabetic or non-diabetic.
5. **Evaluation Metrics**: Accuracy, precision, recall, and ROC-AUC score are used to assess model performance.

## 📂 Project Structure
```
/diabetes-prediction
├── diabetes_dataset.csv        # Dataset used for training
├── diabetes_model.pkl         # Trained ML model
├── diabetes_preprocessor.pkl  # Preprocessing pipeline
├── requirements.txt           # Required dependencies
├── streamlit-app.py           # Streamlit web application
├── README.md                  # Project documentation
```

## ⚙️ Setup Instructions
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/Srinivasareddyseelam/Diabetes-prediction-using-Machine-Learning.git
cd Diabetes-prediction-using-Machine-Learning
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```sh
python -m venv venv  # For Windows
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate  # For Windows
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App
```sh
streamlit run streamlit-app.py
```

## 🎯 Features
✅ Trained ML model for diabetes prediction  
✅ Data preprocessing using a stored pipeline  
✅ User-friendly interface with Streamlit  
✅ Easy-to-deploy and extend  
✅ Provides quick and accurate results based on input parameters  
✅ Interactive visualizations to explore health data trends  
✅ Model explanations to help users understand predictions  

## 🚀 Future Improvements
- Improve model accuracy with hyperparameter tuning
- Add more features for better predictions
- Deploy the app using cloud platforms
- Integrate more datasets for better generalization
- Implement deep learning models for improved accuracy
- Enhance the UI/UX of the web application

## 👨‍💻 Contributors
- **Srinivasareddy Seelam** - [GitHub Profile](https://github.com/Srinivasareddyseelam)

