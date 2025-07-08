# 🧠 Breast Cancer Prediction using Machine Learning

This repository contains a Jupyter Notebook that demonstrates how to build a predictive model to detect breast cancer using machine learning techniques. The goal is to classify whether a tumor is **malignant** or **benign** based on various features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

---

## 📌 Project Highlights

- ✅ **Data Source**: Breast Cancer Wisconsin (Diagnostic) dataset from `sklearn.datasets`
- 📊 **Exploratory Data Analysis (EDA)** and **Data Preprocessing**
- 📈 Multiple ML Models used: 
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - K-Nearest Neighbors
- 🏆 Model Comparison based on Accuracy
- 🧪 Performance Evaluation using Confusion Matrix, Accuracy Score, and Classification Report
- 💡 User-friendly visualizations using `matplotlib` and `seaborn`

---

## 📁 Folder Structure

```
breast-cancer-prediction/
│
├── Breast Cancer Prediction.ipynb     # Main notebook with code and output
├── README.md                          # Project documentation
└── requirements.txt                   # Python dependencies (optional)
```

---

## 🛠️ Installation

To run this notebook locally, follow the steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/breast-cancer-prediction.git
cd breast-cancer-prediction
```

2. (Optional) Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🔍 Dataset Features

Some of the features used for prediction:

- Radius, Texture, Perimeter, Area, Smoothness
- Compactness, Concavity, Symmetry, Fractal Dimension

---

## 📊 Results

The Random Forest Classifier achieved the **highest accuracy**, followed closely by Logistic Regression. Visualizations clearly show the performance of each model, aiding in understanding model selection.

---

## 📚 Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

---

## 🚀 Future Work

- Add hyperparameter tuning
- Try deep learning approaches
- Deploy using Streamlit or Flask

---

## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📃 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

**Author:** Nivedi Kolhe  
**Email:** *your-email@example.com*  
**GitHub:** [@your-username](https://github.com/your-username)

---

⭐ If you find this project helpful, feel free to star this repo and share it!