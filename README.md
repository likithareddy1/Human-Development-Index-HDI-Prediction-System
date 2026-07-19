# Human-Development-Index-HDI-Prediction-System

A Machine Learning-based web application that predicts the **Human Development Index (HDI)** of a country using key socio-economic indicators such as **Life Expectancy, Mean Years of Schooling, Expected Years of Schooling, and Gross National Income (GNI) per Capita**. The application is developed using **Python, Scikit-learn, and Flask** with an interactive web interface.

---

## 📌 Features

- Predict Human Development Index (HDI)
- Data preprocessing and missing value handling
- Exploratory Data Analysis (EDA)
- Data visualization using Matplotlib and Seaborn
- Linear Regression model for prediction
- Interactive Flask web application
- Responsive user interface
- Model saved using Pickle for deployment

---

## 🛠️ Technologies Used

- Python
- Flask
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle
- HTML
- CSS

---

## 📂 Project Structure

```text
HDI_Prediction/
│
├── app.py
├── train_model.py
├── hdi_model.pkl
├── requirements.txt
├── README.md
│
├── Dataset/
│   └── HumanDevelopmentIndex.csv
│
├── templates/
│   ├── home.html
│   ├── indexnew.html
│   └── result.html
│
├── static/
│   ├── css/
│   ├── images/
│   └── plots/
│
└── notebooks/
    └── HDI_Analysis.ipynb
```

---

## 📊 Dataset

The dataset contains Human Development indicators for multiple countries, including:

- Country
- Life Expectancy
- Mean Years of Schooling
- Expected Years of Schooling
- Gross National Income (GNI) per Capita
- Human Development Index (HDI)

---

## 🤖 Machine Learning Workflow

- Load and preprocess the dataset
- Handle missing values
- Perform exploratory data analysis
- Generate visualizations
- Split the dataset into training and testing sets
- Train a Linear Regression model
- Evaluate model performance using R² Score
- Save the trained model as `hdi_model.pkl`

---

## 🌐 Web Application

The application includes:

### 🏠 Home Page
- Project overview
- Navigation to prediction page

### 📄 Prediction Page
Users provide:
- Country
- Life Expectancy
- Mean Years of Schooling
- Expected Years of Schooling
- GNI per Capita

### 📈 Result Page
Displays the predicted Human Development Index (HDI) score.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/likithareddy1/HDI_Prediction_with_MySQL.git
```

Navigate to the project folder:

```bash
cd HDI_Prediction_with_MySQL
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment:

**Windows**

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open your browser:

```text
http://127.0.0.1:5000
```

---

## 📦 Requirements

- Flask
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- mysql-connector-python

Install using:

```bash
pip install -r requirements.txt
```

---
## 🔮 Future Enhancements

- FastAPI integration
- MySQL database integration
- User authentication
- Prediction history
- REST API support
- Dashboard with analytics

---

## 👩‍💻 Author

**Likitha Kalluru**

B.Tech – Computer Science and Engineering (Artificial Intelligence & Machine Learning)

---

## 📄 License

This project is developed for educational and learning purposes.
