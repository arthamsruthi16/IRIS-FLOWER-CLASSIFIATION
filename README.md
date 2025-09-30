# Iris-Flower-Classification
A machine learning project that applies classification algorithms (Logistic Regression, KNN, SVM, Random Forest) on the Iris dataset with visualization and model evaluation.   
It involves predicting the species of iris flowers (*setosa*, *versicolor*, *virginica*) based on the length and width of their sepals and petals.

---

## 📂 Dataset

- The dataset contains **150 samples** of iris flowers.
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- Target:
  - Species → `setosa`, `versicolor`, `virginica`

---

##  Project Workflow

1. **Data Collection**  
   Load the Iris dataset (from CSV).

2. **Data Preprocessing**  
   - Handle missing values (if any)  
   - Encode target labels (`setosa`, `versicolor`, `virginica`)  

3. **Exploratory Data Analysis (EDA)**  
   - Summary statistics  
   - Correlation heatmap  
   - Pair plots & visualizations  

4. **Model Training**  
   - Split dataset into training & testing sets  
   - Train models like:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)

5. **Model Evaluation**  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report  

6. **Visualization**  
   - Heatmaps for correlation  
   - Distribution plots  
   - Decision boundaries (optional)

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<arthamsruthi16>/IRIS-FLOWER-CLASSIFICATION.git
cd IRIS-FLOWER-CLASSIFICATION
````

### 2️⃣ Install dependencies

If `pip` works:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

If `pip` is not recognized, use full path to Python:

```powershell
"C:\Users\arthamsruthi16>\AppData\Local\Programs\Python\Python37\python.exe" -m pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 📊 Usage

Run the main script:

in Jupyter Notebook:

```bash
jupyter notebook
```

---

## ✅ Results

* Achieved **\~95–98% accuracy** with models like Random Forest and SVM.
* `setosa` species is linearly separable, while `versicolor` and `virginica` show some overlap.
* Visualization examples:

  * Correlation Heatmap
  * Pairplots of features
  * Confusion Matrix

---

## 📸 Sample Outputs

### Correlation Heatmap

<img width="637" height="528" alt="image" src="https://github.com/user-attachments/assets/42bd5e28-1f4d-4549-b526-24df8b216b42" />


### Confusion Matrix

<img width="501" height="393" alt="image" src="https://github.com/user-attachments/assets/a72c81e5-9163-4935-940c-33d7a85d8cd5" />


---

## 🔮 Future Improvements

* Deploy as a **Flask / Streamlit web app**
* Add hyperparameter tuning with **GridSearchCV**
* Try deep learning models for comparison

---

## 👩‍💻 Author

- **Sruthi**  
- Internship Project  
- GitHub: [arthamsruthi16](https://github.com/arthamsruthi16)  

---
