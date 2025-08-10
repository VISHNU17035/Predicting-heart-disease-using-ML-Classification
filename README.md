# Heart Disease Prediction using Machine Learning

This project applies various Python-based machine learning and data science libraries to build a model capable of predicting whether a person has heart disease based on their medical attributes.

---

## 📌 Project Workflow
We follow the steps below:
1. **Problem Definition**  
2. **Data Collection & Understanding**  
3. **Evaluation Criteria**  
4. **Feature Exploration**  
5. **Model Building**  
6. **Experimentation & Improvement**  

---

## 1. Problem Definition
> **Goal:** Given clinical parameters about a patient, can we predict whether they have heart disease?  

---

## 2. Data
- **Source:** Cleveland Heart Disease dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease)  
- **Alternate Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)  

---

## 3. Evaluation Metric
We aim to achieve **≥ 95% accuracy** during the proof of concept stage.  

---

## 4. Features
Below is the **data dictionary** for the dataset:

| Feature   | Description |
|-----------|-------------|
| `age` | Age in years |
| `sex` | 1 = male; 0 = female |
| `cp` | Chest pain type:<br>0 = Typical angina<br>1 = Atypical angina<br>2 = Non-anginal pain<br>3 = Asymptomatic |
| `trestbps` | Resting blood pressure (mm Hg) |
| `chol` | Serum cholesterol (mg/dl) |
| `fbs` | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| `restecg` | Resting electrocardiographic results:<br>0 = Normal<br>1 = ST-T Wave abnormality<br>2 = Left ventricular hypertrophy |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina (1 = yes; 0 = no) |
| `oldpeak` | ST depression induced by exercise |
| `slope` | Slope of peak exercise ST segment:<br>0 = Upsloping<br>1 = Flat<br>2 = Downsloping |
| `ca` | Number of major vessels (0-3) colored by fluoroscopy |
| `thal` | Thalium stress result:<br>1, 3 = Normal<br>6 = Fixed defect<br>7 = Reversible defect |
| `target` | Target variable: 1 = Disease present, 0 = No disease |

---

## 🛠 Technologies Used
- **Python**
- **pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## 🚀 How to Run
```bash
# Clone this repository
git clone https://github.com/yourusername/heart-disease-prediction.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook heart_disease_prediction.ipynb
