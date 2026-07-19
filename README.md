# 🚗 Car Price Prediction AI

> An end-to-end Machine Learning web application that predicts the selling price of used cars using vehicle specifications. Built with **Python**, **Scikit-learn**, and **Streamlit**.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red?logo=streamlit)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

Buying or selling a used car often involves estimating a fair market price. This project leverages **Machine Learning** to predict the selling price of a used car based on multiple vehicle attributes.

The application provides an intuitive web interface where users can enter vehicle details and receive an instant price prediction.

---

## 🚀 Live Demo

🌐 **Streamlit Application**


[View Website](https://project-carpriceprediction-eghi692bn3ec68z2r226qr.streamlit.app/)

---

## ✨ Features

- 🚗 Predicts used car selling prices instantly
- 🤖 Machine Learning-powered predictions
- 📊 Data preprocessing and feature engineering
- ⚡ Interactive Streamlit interface
- 📈 High-performance Random Forest Regressor
- 🎯 User-friendly design
- 💰 Automatic price formatting (Thousand, Lakh, Crore)
- 📱 Responsive web application

---

## 🖼️ Application Preview

### Home Page

```
(Add Screenshot Here)
```

### Prediction Result

```
(Add Screenshot Here)
```

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Programming Language | Python |
| Machine Learning | Scikit-learn |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Web Framework | Streamlit |
| Model Serialization | Pickle |
| IDE | Jupyter Notebook / VS Code |

---

## 📂 Project Structure

```
Car-Price-Prediction/
│
├── app.py
├── model_training.ipynb
├── README.md
├── requirements.txt
│
├── dataset/
│   └── car_data.csv
│
├── saved_models/
│   └── RandomForestRegressor.pkl
│
├── saved_scaling/
│   └── scaler.pkl
│
├── images/
│   ├── home.png
│   └── prediction.png
│
└── notebooks/
    └── EDA.ipynb
```

---

## 📊 Dataset

The dataset contains various attributes of used cars.

### Input Features

- Car Name
- Vehicle Age
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner Type
- Mileage
- Engine Capacity
- Maximum Power
- Number of Seats

### Target Variable

- Selling Price

---

## ⚙️ Machine Learning Pipeline

```
Dataset Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Categorical Encoding
        │
        ▼
Feature Scaling
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Model Serialization (.pkl)
        │
        ▼
Streamlit Deployment
```

---

## 🤖 Models Evaluated

Several regression algorithms were trained and compared.

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

### 🏆 Final Selected Model

**Random Forest Regressor**

Reasons for selection:

- High Prediction Accuracy
- Robust against Overfitting
- Handles Non-linear Relationships
- Better Generalization on Test Data

---

## 📈 Model Evaluation

The model was evaluated using standard regression metrics.

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

> Replace this section with your actual evaluation results.

Example:

| Metric | Value |
|---------|--------|
| R² Score | 0.94 |
| MAE | 0.45 |
| RMSE | 0.72 |

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/your-username/car-price-prediction.git
```

### Navigate to Project

```bash
cd car-price-prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

---

## 📦 Requirements

```
Python >= 3.10

streamlit
pandas
numpy
scikit-learn
matplotlib
seaborn
pickle5
```

Or install manually:

```bash
pip install streamlit pandas numpy scikit-learn matplotlib seaborn
```

---

## 💻 How to Use

1. Open the Streamlit application.
2. Enter all required vehicle details.
3. Click **Predict Price**.
4. The trained Machine Learning model predicts the estimated selling price.

---

## 📸 Screenshots

Add screenshots inside the **images/** folder.

Example:

```
images/
    home.png
    prediction.png
```

---

## 🔮 Future Enhancements

- Deep Learning-based prediction model
- Real-time market price integration
- Explainable AI using SHAP
- Cloud deployment (AWS / Azure / GCP)
- Vehicle image-based prediction
- Location-wise price estimation
- REST API using FastAPI
- Docker containerization
- CI/CD pipeline using GitHub Actions

---

## 🤝 Contributing

Contributions are always welcome.

1. Fork the repository.
2. Create your feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push the branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Priyanshu Saini**

B.Tech – Computer Science Engineering

Machine Learning | Data Science | Python Developer

GitHub:
https://github.com/your-username

LinkedIn:
https://www.linkedin.com/in/your-profile

Email:
your-email@example.com

---

## 🙏 Acknowledgements

- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

Your support motivates future improvements and new open-source projects.

---

## 📬 Contact

Feel free to connect for collaborations, suggestions, or feedback.

Happy Coding! 🚀
