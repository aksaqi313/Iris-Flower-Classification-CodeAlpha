# 🌸 Iris Flower Classification

## 📌 CodeAlpha Machine Learning Project

This project is developed as part of the **CodeAlpha Machine Learning Internship/Task**. The objective is to build a machine learning model that can classify Iris flowers into different species based on their physical measurements.

---

## 🎯 Project Objective

The goal of this project is to classify Iris flowers into one of the following three species:

* **Iris-setosa**
* **Iris-versicolor**
* **Iris-virginica**

The classification is performed using four flower measurements:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

---

## 📂 Dataset

The project uses the well-known **Iris Flower Dataset**.

The dataset contains:

* **150 observations**
* **4 input features**
* **3 flower species**

### Features

| Feature       | Description                        |
| ------------- | ---------------------------------- |
| SepalLengthCm | Length of the sepal in centimeters |
| SepalWidthCm  | Width of the sepal in centimeters  |
| PetalLengthCm | Length of the petal in centimeters |
| PetalWidthCm  | Width of the petal in centimeters  |
| Species       | Iris flower species                |

Each species contains approximately **50 samples**.

---

## 🛠️ Technologies and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Kaggle Notebook
* GitHub

---

## 🔍 Project Workflow

The following steps were performed in this project:

1. Import required Python libraries.
2. Load the Iris dataset.
3. Explore the dataset.
4. Check data types and missing values.
5. Analyze the distribution of flower species.
6. Visualize relationships between flower measurements.
7. Select input features and target variable.
8. Split the dataset into training and testing sets.
9. Standardize the input features.
10. Train a **Logistic Regression** classification model.
11. Make predictions on the test dataset.
12. Evaluate model performance.
13. Generate a confusion matrix.
14. Generate a classification report.
15. Predict the species of a new Iris flower.

---

## 🤖 Machine Learning Model

The classification model used in this project is:

### Logistic Regression

The data was divided into:

* **80% Training Data**
* **20% Testing Data**

Feature scaling was performed using:

```python
StandardScaler()
```

The classifier was created using:

```python
LogisticRegression(max_iter=200)
```

---

## 📊 Model Evaluation

The performance of the model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Classification Report

The Logistic Regression model achieved approximately **93% classification accuracy** using the selected train-test split and random state.

---

## 📈 Data Visualization

Several visualizations were created to better understand the dataset, including:

* Species count plot
* Petal Length vs Petal Width scatter plot
* Pairplot
* Confusion matrix heatmap

These visualizations help show the differences among the three Iris flower species.

---

## 📁 Repository Structure

```text
Iris-Flower-Classification
│
├── Iris.csv
├── iris_flower_classification.ipynb
└── README.md
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Iris-Flower-Classification.git
```

### 2. Open the project

You can run the notebook using:

* Kaggle
* Jupyter Notebook
* JupyterLab
* Google Colab

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Run the notebook

Open:

```text
iris_flower_classification.ipynb
```

Run all cells sequentially to reproduce the analysis and machine learning results.

---

## 🌺 Example Prediction

A new flower with the following measurements can be provided to the trained model:

```text
Sepal Length = 5.1 cm
Sepal Width  = 3.5 cm
Petal Length = 1.4 cm
Petal Width  = 0.2 cm
```

The model predicts the flower as:

```text
Iris-setosa
```

---

## ✅ Conclusion

This project demonstrates the basic machine learning classification workflow using the Iris dataset. A Logistic Regression model was successfully trained using flower measurements to distinguish between **Setosa, Versicolor, and Virginica** species.

The project covers data exploration, visualization, preprocessing, model training, prediction, and performance evaluation using **Scikit-learn**.

---

## 👨‍💻 CodeAlpha Task

**Task 1: Iris Flower Classification**

This project was completed as part of the **CodeAlpha Machine Learning project/task**.

---

## ⭐ Acknowledgement

Thanks to **CodeAlpha** for providing the opportunity to practice machine learning concepts through this project.
