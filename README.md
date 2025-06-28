

# ❤️ Heart Disease Prediction

Predicting whether a person is likely to have heart disease (1) or not (0) based on clinical and health measurements using machine learning techniques.



## 📑 Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Project Objectives](#project-objectives)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Model Building](#model-building)
* [Results](#results)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



## 📝 Introduction

The **Heart Disease Prediction** project uses machine learning algorithms to classify whether an individual is at risk of heart disease based on clinical and demographic data. This can aid healthcare professionals in early diagnosis and preventive care.



## 📊 Dataset

* **Source:** UCI Machine Learning Repository - Heart Disease Dataset
* **Link:** [Heart Disease Dataset]()
* **Attributes:**

| Feature  | Description                                                       |
| -------- | ----------------------------------------------------------------- |
| age      | Age of the person                                                 |
| sex      | Gender (1 = male; 0 = female)                                     |
| cp       | Chest pain type (0-3)                                             |
| trestbps | Resting blood pressure                                            |
| chol     | Serum cholesterol (mg/dl)                                         |
| fbs      | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)             |
| restecg  | Resting electrocardiographic results (0-2)                        |
| thalach  | Maximum heart rate achieved                                       |
| exang    | Exercise induced angina (1 = yes; 0 = no)                         |
| oldpeak  | ST depression induced by exercise                                 |
| slope    | Slope of the peak exercise ST segment                             |
| ca       | Number of major vessels (0-3) colored by fluoroscopy              |
| thal     | Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect) |
| target   | Diagnosis of heart disease (1 = disease; 0 = no disease)          |



## 🎯 Project Objectives

✅ Load and explore the heart disease dataset

✅ Perform data preprocessing (handle missing values, encoding)

✅ Visualize data to understand distributions and correlations

✅ Build classification models (Logistic Regression, Random Forest, SVM, etc.)

✅ Evaluate model performance using accuracy, precision, recall, and F1-score

✅ Predict heart disease status for new patient data



## 🛠️ Technologies Used

* Python 3.x
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook



## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/heart_disease_prediction.git
cd heart_disease_prediction
```

2. **Create virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate      # On Linux/Mac
venv\Scripts\activate         # On Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```



## ▶️ Usage

1. **Run the Jupyter Notebook**

```bash
jupyter notebook Heart_Disease_Prediction.ipynb
```

2. **Follow the notebook steps to:**

* Explore and understand data
* Visualize feature relationships
* Preprocess and prepare data for modeling
* Build, train, and evaluate classification models
* Predict heart disease status for new input data



## 🏗️ Model Building

The following models were implemented and compared:

| Model                            | Description                            |
| -------------------------------- | -------------------------------------- |
| **Logistic Regression**          | Baseline classification model          |
| **Decision Tree**                | Simple interpretable classifier        |
| **Random Forest**                | Ensemble method for improved accuracy  |
| **Support Vector Machine (SVM)** | Effective for higher-dimensional space |
| **K-Nearest Neighbors (KNN)**    | Instance-based learning                |

**Evaluation Metrics:**

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix



## 📈 Results

* **Best performing model:** *Specify model name here*
* **Accuracy:** *Value here*
* **Precision:** *Value here*
* **Recall:** *Value here*
* **F1-Score:** *Value here*

> The Random Forest Classifier achieved the highest performance due to its robustness to overfitting and ability to handle feature interactions.



## 🤝 Contributing

Contributions are welcome to improve the model, add deployment integrations, or build a frontend interface for real-time predictions.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request



## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.



## 📬 Contact

**Ugama Benedicta Kelechi**
[LinkedIn](www.linkedin.com/in/ugama-benedicta-kelechi-codergirl-103041300) | [Email](mailto:ugamakelechi@gmail.com) | [Portfolio](#)



### ⭐️ If you find this project useful, please give it a star!

