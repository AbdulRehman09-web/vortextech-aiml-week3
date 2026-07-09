# 🏠 Regression and Clustering on Real Data

A complete Machine Learning project developed as part of the **AI & ML Internship - Week 3**. This project demonstrates both **Supervised Learning (Regression)** and **Unsupervised Learning (Clustering)** using real-world datasets and Python's Scikit-learn library.

---

## 📌 Project Overview

This project is divided into two main tasks:

### 1️⃣ Regression

Built regression models to predict **house prices** using housing-related features.

Models used:

- Linear Regression
- Random Forest Regressor

Performance was evaluated using:

- Root Mean Squared Error (RMSE)
- R² Score

---

### 2️⃣ Clustering

Performed customer segmentation using the **Mall Customer Dataset**.

Techniques used:

- StandardScaler
- K-Means Clustering
- Elbow Method

The identified customer groups were visualized using a scatter plot.

---

# 📂 Project Structure

```
vortextech-aiml-week3/
│
├── data/
│   ├── Housing.csv
│   └── Mall_Customers.csv
│
├── notebook/
│   └── Regression_and_Clustering.ipynb
│
├── images/
│   ├── elbow method.png
│   ├── customer segmentation.png
│   └── actual vs predicted.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 📊 Datasets

## Housing Price Dataset

Used for the regression task.

Target Variable:

```
price
```

Features include:

- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road
- Guest Room
- Basement
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

---

## Mall Customer Dataset

Used for customer segmentation.

Features used:

- Annual Income (k$)
- Spending Score (1–100)

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/vortextech-aiml-week3.git
```

Move into the project folder:

```bash
cd vortextech-aiml-week3
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Regression_and_Clustering.ipynb
```

Run all cells.

---

# 📈 Regression Workflow

The following steps were performed:

- Data Loading
- Data Cleaning
- Feature Encoding
- Train-Test Split (80/20)
- Model Training
- Prediction
- Performance Evaluation

### Models

- Linear Regression
- Random Forest Regressor

### Evaluation Metrics

- RMSE
- R² Score

---

# 📊 Clustering Workflow

The following steps were completed:

- Data Loading
- Feature Selection
- Feature Scaling
- Elbow Method
- K-Means Clustering
- Cluster Visualization

---

# 📉 Visualizations

The notebook includes the following visualizations:

- Actual vs Predicted House Prices
- Elbow Method Plot
- Customer Segmentation Scatter Plot

---

# 📋 Results

## Regression

Both Linear Regression and Random Forest Regressor were trained to predict house prices.

Performance was evaluated using RMSE and R² Score to compare model accuracy.

---

## Clustering

The Elbow Method identified an appropriate number of clusters.

K-Means successfully grouped customers based on their:

- Annual Income
- Spending Score

These clusters represent different customer purchasing behaviors that can be useful for business decision-making.

---

# 🚀 Skills Demonstrated

- Data Preprocessing
- Feature Engineering
- One-Hot Encoding
- Train-Test Split
- Linear Regression
- Random Forest Regression
- RMSE & R² Evaluation
- Standardization
- K-Means Clustering
- Elbow Method
- Data Visualization
- Exploratory Data Analysis (EDA)

---

# 📚 Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 📄 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

Example `requirements.txt`:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 🎯 Learning Outcomes

After completing this project, the following concepts were applied:

- Supervised Learning
- Unsupervised Learning
- Regression Analysis
- Customer Segmentation
- Model Evaluation
- Data Scaling
- Feature Encoding
- Machine Learning Pipeline

---

# 👨‍💻 Author

**Abdul Rehman**

Bachelor of Artificial Intelligence  
SZABIST University, Islamabad, Pakistan

AI & ML Internship Track – Week 3

---

# 📜 License

This project is created for educational and internship purposes.

Feel free to use, modify, and learn from this repository.