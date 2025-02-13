# 🧠 Machine Learning with SVM: Social Network Ads Analysis

## 📊 Project Overview
In this project, we use a **Support Vector Machine (SVM)** model to predict whether users will purchase a product based on age and estimated salary. The dataset consists of social network ads, and we implement data preprocessing, model training, prediction, and performance evaluation.

## ⚙️ Project Workflow

### 1. 🛠️ Importing Libraries and Dataset
We start by importing essential Python libraries like **Pandas**, **NumPy**, and **Matplotlib**. The dataset is read into a DataFrame, and features (**X**) and target labels (**y**) are extracted.

### 2. 🧪 Data Preprocessing
To prepare the data, we:
- Split it into training and test sets (75%-25%).
- Apply **Feature Scaling** using `StandardScaler` to standardize the features.

### 3. 🎨 Data Visualization
- We visualize the **training set** before scaling to understand the distribution.
- After scaling, we plot the data to observe potential patterns.

### 4. 🤖 Model Training
We train a **Support Vector Machine (SVM)** classifier with a linear kernel to predict user purchase behavior.

### 5. 🔍 Model Evaluation
- Predictions are made on the test set.
- We use a **Confusion Matrix** to evaluate the model's performance.
- The **accuracy score** provides a clear metric for success.

### 6. 📈 Visualizing Results
- **Decision boundaries** are plotted for both training and test sets.
- Data points are color-coded to distinguish between classes.

## 🚀 Key Insights
- SVM effectively separates the data into purchase and non-purchase classes.
- Feature scaling significantly improves model performance.
- Visualization of decision boundaries provides intuitive insights into the model's behavior.

## 🧩 Tech Stack
- **Python** 🐍
- **Pandas** 🐼
- **NumPy** 🔢
- **Matplotlib** 📊
- **scikit-learn** 🤖

## 🎯 Results
The model demonstrates a strong ability to distinguish between users who are likely to make a purchase and those who aren't, making it a valuable tool for targeted marketing campaigns.

> **"Data is the new oil. Machine learning helps us refine it."** 💡

---

### 🧠 Mathematical Formulations

The SVM model finds the hyperplane that best separates the classes by maximizing the margin. The equation of the hyperplane is:

$$ w \cdot x + b = 0 $$

The decision function is defined as:

$$ f(x) = \text{sign}(w \cdot x + b) $$

The objective of the SVM optimization is to minimize:

$$ \frac{1}{2}||w||^2 $$

subject to the constraint:

$$ y_i(w \cdot x_i + b) \geq 1 $$

Feel free to check out the code in the repository and reach out for any questions or collaborations! 🚀

