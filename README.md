# 🎓 Student Placement Prediction System

This project uses machine learning to predict whether a student is likely to be placed based on various academic and personal features. It's built using Python and Jupyter Notebook with a structured dataset for training and evaluation.

## 🚀 Features

- Predicts student placement status (Placed / Not Placed)
- Uses classification models (like Logistic Regression, Decision Tree, etc.)
- Data preprocessing and feature engineering
- Accuracy evaluation with test data
- Visualizations for better data understanding

## 📁 Project Structure

```
Student-Placement-Prediction-System/
├── placement_prediction.ipynb    # Main Jupyter Notebook for the project
├── train.csv                     # Training dataset
├── test.csv                      # Testing dataset
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

## 📊 Dataset Information

The dataset contains the following features:
- Gender
- Stream
- CGPA
- Internships
- Hosteler or Day Scholar
- Backlogs
- Placement status (target variable)

The data is split into training and testing sets for model evaluation.

## 🔧 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/manasdarak10/Student-Placement-Prediction-System.git
cd Student-Placement-Prediction-System
```

### 2. Install dependencies

Make sure Python is installed, then use pip to install the required packages:

```bash
pip install -r requirements.txt
```

### 3. Run the project

Open the notebook:

```bash
jupyter notebook placement_prediction.ipynb
```

Follow the notebook cells step by step to explore the dataset, preprocess the data, train the model, and test accuracy.

## 📦 requirements.txt

```txt
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

## 📈 Model Performance

- Accuracy and classification reports are displayed at the end of the notebook
- You can try different ML algorithms and compare results

## 💡 Future Enhancements

- Deploy the model using Flask/Streamlit as a web application
- Add GUI for inputting new student data
- Use ensemble learning to improve accuracy

## 👨‍💻 Author

**Manas Darak**  
GitHub: [@manasdarak10](https://github.com/manasdarak10)
