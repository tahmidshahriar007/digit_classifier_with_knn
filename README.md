## 🔢 Handwritten Digit Classification using KNN & PCA

> **Executive Summary:** A machine learning pipeline designed to recognize and classify handwritten digits ($0$–$9$) from the MNIST benchmark dataset using $k$-Nearest Neighbors ($k$-NN) accelerated with Principal Component Analysis (PCA). This project demonstrates end-to-end data loading, feature transformation, dimensionality reduction, and multi-class classification.

---

## 📌 Project Highlights

* **Data Ingestion & Exploration:** Loaded the standard $28 \times 28$ pixel grayscale MNIST dataset directly from TensorFlow/Keras ($60,000$ training / $10,000$ testing samples) and visualized digit samples across classes.
* **Feature Processing & Dimensionality Reduction:** Flattened $28 \times 28$ image arrays into $784$-dimensional vectors and applied Principal Component Analysis (PCA) to compress feature space while retaining key variance.
* **Model Training & Evaluation:** Implemented Scikit-Learn’s `KNeighborsClassifier` to perform digit recognition and evaluated classification performance using confusion matrices and classification reports.

---

## 🛠️ Tools & Libraries Used
* **Python** | **Scikit-Learn** (`KNeighborsClassifier`, `PCA`) | **TensorFlow / Keras** | **NumPy** | **Matplotlib** | **Seaborn**

---

## 📂 View the Notebook
👉 **[Click here to open the Project](./Digit_classifier_using_knn.ipynb)
