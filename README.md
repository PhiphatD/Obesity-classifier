# Obesity Classification Project

## 📋 Project Overview
This project implements a machine learning model to classify obesity levels based on various lifestyle and demographic factors. The model predicts obesity categories (0-6) using features such as age, gender, height, weight, eating habits, physical activity, and other lifestyle indicators.

## 🎯 Objective
Develop a multiclass classification model to predict obesity levels with high accuracy using lifestyle and demographic data.

## 📊 Dataset
- **Source**: MOBS-02S.csv
- **Size**: 2,111 records
- **Features**: 16 input features + 1 target variable
- **Target Classes**: 7 obesity levels (0-6)

### Features Description
- `gender`: Gender (Male/Female)
- `age`: Age in years
- `height`: Height in meters
- `weight`: Weight in kg
- `overweight_family`: Family history of overweight (0/1)
- `consum_cf`: Consumption of high caloric food frequency
- `consum_vf`: Vegetable consumption frequency
- `comsum_daily`: Daily meal consumption pattern
- `consum_other`: Other food consumption habits
- `smoking`: Smoking status (yes/no)
- `consum_water`: Water consumption level
- `cal_monitoring`: Calorie monitoring (yes/no)
- `phyical_activity`: Physical activity frequency
- `device_usage`: Technology device usage
- `consum_alchohol`: Alcohol consumption frequency
- `transportation`: Transportation method
- `Obesity`: Target variable (0-6 obesity levels)

## 🔧 Project Structure
```
Obesity-classifier/
├── MOBS-02S.csv                              # Original dataset
├── MOBS_02S_Clean.csv                        # Cleaned dataset
├── Obesity_Preprocessing_Data_Cleaning.ipynb # Data preprocessing notebook
├── Obesity_Modeling.ipynb                    # Model training notebook
├── best_model.keras                          # Trained model file
├── README.md                                 # Project documentation
├── requirements.txt                          # Python dependencies
└── .gitignore                               # Git ignore file
```

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required libraries (see requirements.txt)

## 📈 Model Performance
The model uses multiclass classification with the following evaluation metrics:
- **Macro-F1 Score**: Balanced performance across all classes
- **Accuracy**: Overall classification accuracy
- **Confusion Matrix**: Detailed class-wise performance

## 🔄 Workflow
1. **Data Preprocessing** (`Obesity_Preprocessing_Data_Cleaning.ipynb`):
   - Data cleaning and exploration
   - Feature engineering
   - Data transformation

2. **Model Training** (`Obesity_Modeling.ipynb`):
   - Model selection and training
   - Hyperparameter tuning
   - Model evaluation


## 📁 Files Description
- `MOBS-02S.csv`: Original raw dataset
- `MOBS_02S_Clean.csv`: Preprocessed and cleaned dataset
- `best_model.keras`: Trained Keras model ready for inference
- `Obesity_Preprocessing_Data_Cleaning.ipynb`: Complete data preprocessing pipeline
- `Obesity_Modeling.ipynb`: Model training and evaluation pipeline

