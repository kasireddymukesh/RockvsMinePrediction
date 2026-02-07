# RockvsMinePrediction

---

## Rock vs Mine Prediction Using Sonar Data

### 📌 Project Overview

This project focuses on predicting whether an object detected by sonar signals is a **Rock (R)** or a **Mine (M)** using machine learning techniques. The classification is performed using **Logistic Regression**, a supervised learning algorithm suitable for binary classification problems.

Sonar systems emit sound waves and analyze the reflected signals. Different objects reflect sound differently, and these variations can be used as features for prediction.

---

### 📊 Dataset Description

* The dataset consists of **208 samples**.
* Each sample has **60 numerical features**, representing the energy of sonar signals at different frequencies.
* The **61st column** is the target label:

  * `M` → Mine
  * `R` → Rock
* The dataset contains **no missing values**.

---

### ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

### 🧠 Model Used

* **Logistic Regression**

  * Chosen for its simplicity and effectiveness in binary classification tasks.
  * Works well when the relationship between features and target is approximately linear.

---

### 🔄 Workflow

1. **Import Dependencies**
2. **Load the Dataset**
3. **Data Exploration & Processing**

   * Separate features (`X`) and target labels (`y`)
4. **Train-Test Split**

   * Data is split into training and testing sets
5. **Model Training**

   * Logistic Regression is trained on the training data
6. **Model Evaluation**

   * Accuracy score is used to measure model performance

---

### 📈 Evaluation Metric

* **Accuracy Score**

  * Measures how many predictions were correctly classified as Rock or Mine.

---

### ✅ Conclusion

This project demonstrates how machine learning can be applied to sonar signal data to accurately distinguish between rocks and mines. It highlights the complete ML pipeline—from data preprocessing to model evaluation—making it a great beginner-friendly classification project.
