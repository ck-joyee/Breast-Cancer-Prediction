# 🎗️ Breast Cancer Prediction using Machine Learning

A machine learning project that predicts whether a breast tumour is **malignant (M)** or **benign (B)** using the Wisconsin Breast Cancer Dataset. Three classification models are compared, with **Random Forest achieving the highest accuracy**.

This project is related to my published research on optimising post-cancer treatment prognosis using ensemble techniques, published in *WSEAS Transactions on Computer Research*.

---

## 📊 Dataset

- **Source:** Wisconsin Breast Cancer Dataset
- **Records:** 569 patient samples
- **Features:** 30 numeric features including radius, texture, perimeter, area, smoothness, compactness, concavity, and symmetry measurements
- **Target:** Diagnosis — Malignant (M) or Benign (B)

---

## 🧠 Models Compared

| Model | Type |
|---|---|
| Logistic Regression | Linear classifier |
| Decision Tree | Tree-based classifier |
| Random Forest | Ensemble classifier ✅ Best |

---

## ⚙️ Workflow

1. **Data Loading & Exploration** — checked shape, null values, and class distribution
2. **Preprocessing** — label encoding, null column removal, feature scaling with StandardScaler
3. **Visualisation** — correlation heatmap, pair plots, class distribution chart
4. **Model Training** — trained all three models on 80% of the data
5. **Evaluation** — compared accuracy scores and classification reports on the test set
6. **Model Export** — saved the best model using `joblib` for reuse

---

## 🛠️ Tech Stack

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
- Joblib (model persistence)

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/ck-joyee/Breast-Cancer-Prediction.git
cd Breast-Cancer-Prediction

# 2. Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn joblib

# 3. Launch the notebook
jupyter notebook Breast_Cancer.ipynb
```

---

## 📁 Project Structure

```
Breast-Cancer-Prediction/
│
├── data/
│   └── breast_cancer.csv       # Dataset
├── Breast_Cancer.ipynb         # Main notebook
├── Breast Cancer Prediction.joblib  # Saved model
└── README.md
```

---

## 📌 Related Publication

> **Optimizing Post-Cancer Treatment Prognosis: A Study of Machine Learning and Ensemble Techniques**
> Published in *WSEAS Transactions on Computer Research*
> 🔗 [Read the paper](https://wseas.com/index.php/cr/article/view/6)

---

## 👩‍💻 Author

**Joyee Chakraborty**
Master of Information Technology — Central Queensland University, Brisbane
🔗 [LinkedIn](https://www.linkedin.com/in/joyee-chakraborty) | [Portfolio](https://joyee-ck.netlify.app/)
