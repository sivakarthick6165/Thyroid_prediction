# *Thyroid Disease Prediction Web App*  
![Python](https://img.shields.io/badge/Python-3.11-blue)  
![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-red)  
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-KNN%20&%20Decision%20Tree-brightgreen)  
![Status](https://img.shields.io/badge/Status-Completed-blueviolet)

## *🎯 Project Overview*
The *Thyroid Disease Prediction* system is a machine learning-based web application that allows users to predict the presence of thyroid disease using medical input features. The project uses *K-Nearest Neighbors (KNN)* and *Decision Tree Classifier* models to provide accurate and fast predictions.

---

## *👨‍💻 Developer*
- *Sivakarthick B* (22UCS037)  

---

## *🔍 Features*
- User-friendly Streamlit web interface  
- Thyroid disease prediction based on patient input  
- Preprocessed real-world dataset from *Kaggle*  
- Accuracy comparison between KNN and Decision Tree  
- Trained model integration and deployment  

---

## *🛠️ Technologies Used*
| Tech        | Usage                               |
|-------------|--------------------------------------|
| *Python*  | Programming Language                 |
| *Pandas*  | Data Cleaning & Preprocessing        |
| *Sklearn* | Machine Learning Models              |
| *Streamlit*| Web Application Interface            |
| *Matplotlib / Seaborn* | Data Visualization      |

---

## *📁 Folder Structure*
thyroid_prediction_project/ │ ├── dataset/ │   └── thyroiddata.csv │ ├── model/ │   └── saved_knn_model.pkl │ ├── app.py ├── model_training.ipynb ├── requirements.txt └── README.md

---

## *📊 Dataset Info*
- *Source*: [Kaggle](https://www.kaggle.com/datasets)  
- *Filename*: thyroiddata.csv  
- *Attributes*: Includes features like age, TSH, T3, TT4, T4U, FTI, etc.  
- *Label*: Target column for thyroid condition classification  

---

## *⚙️ How to Run*
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/thyroid-prediction.git
   cd thyroid-prediction

2. Install dependencies:

pip install -r requirements.txt


3. Run the app:

streamlit run app.py
