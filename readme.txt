# 🚢 Titanic Exploratory Data Analysis & Feature Engineering

## 📌 Project Overview

This project is an end-to-end Exploratory Data Analysis (EDA) of the Titanic dataset using Python. The objective is to understand passenger demographics, travel patterns, and important factors that may influence survival.

Instead of directly building a machine learning model, this project focuses on understanding the dataset through data preprocessing, feature engineering, statistical analysis, and meaningful visualizations.

---

## 🎯 Objectives

- Explore the Titanic dataset.
- Clean and preprocess the data.
- Handle missing values.
- Perform feature engineering.
- Analyze passenger characteristics.
- Visualize patterns using different plots.
- Draw meaningful insights from the data.

---

## 📂 Dataset

The dataset contains information about Titanic passengers, including:

- Passenger Class
- Gender
- Age
- Ticket
- Fare
- Embarked Port
- Family Details
- Survival Status

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📋 Project Workflow

### 1. Data Loading
- Imported the Titanic dataset.
- Explored dataset structure.
- Checked data types and shape.

### 2. Data Cleaning
- Handled missing values.
- Removed unnecessary columns.
- Renamed categorical values for better readability.

### 3. Feature Engineering
Created several meaningful features such as:

- Family Count
- Number of Passengers Sharing the Same Ticket
- Companion Type (Solo, Family, Friends)
- Age Category
- Social Status

Also adjusted the fare per passenger for passengers sharing the same ticket.

### 4. Exploratory Data Analysis (EDA)

Performed statistical analysis using:

- describe()
- value_counts()
- unique()
- Sorting
- Frequency Analysis

### 5. Data Visualization

Created different visualizations including:

- Count Plot
- Pie Chart
- Bivariate Count Plot
- Category-wise Comparisons

These visualizations helped understand passenger distribution, age groups, travel companions, gender distribution, and passenger classes.

---

## 📊 Key Insights

- Most passengers traveled alone.
- Adult passengers formed the largest age group.
- Male passengers were more than female passengers.
- Third-class passengers were the highest in number.
- Many passengers shared the same ticket, indicating family or group travel.
- Feature engineering provided additional insights beyond the original dataset.

---

## 📁 Project Structure

```
Titanic-Exploratory-Data-Analysis/
│
├── Titanic_Data-Analytics.ipynb
├── Titanic.csv
├── README.md
└── images/
```

---

## 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/yourusername/Titanic-Exploratory-Data-Analysis.git
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook.

```bash
jupyter notebook
```

4. Run all the cells.

---

## 📈 Future Improvements

- Build predictive machine learning models.
- Perform correlation analysis.
- Apply feature selection techniques.
- Compare different classification algorithms.
- Deploy the project using Streamlit.

---

## 👨‍💻 Author

**Bandhavya K. S.**

Computer Science Engineer | Python Developer | Data Science Enthusiast

---

⭐ If you found this project useful, consider giving it a star!