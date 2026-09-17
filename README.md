# 🛍️ Product Reviews Classification

A machine learning project for **classifying product reviews based on their textual content**. The project covers the complete NLP workflow, including **exploratory data analysis, text preprocessing, feature extraction, dimensionality reduction, model training, evaluation, and sentiment prediction on new reviews**.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mariamAboujenane/product-review-classification/blob/main/product_review_classification.ipynb)

---

## 📌 Project Overview

Customer reviews contain valuable information about user experiences, product quality, and customer satisfaction. However, manually analyzing large volumes of reviews can be time-consuming.

This project applies **Natural Language Processing (NLP) and Machine Learning** techniques to automatically classify product reviews into predefined categories.

### Key Objectives

* Analyze and understand the review dataset.
* Perform exploratory data analysis (EDA).
* Clean and preprocess textual data.
* Convert text into numerical features suitable for machine learning.
* Train a classification model on product reviews.
* Evaluate the model's performance.
* Visualize the feature space using **Principal Component Analysis (PCA)**.
* Predict the sentiment/category of previously unseen reviews.

---

## 🧠 Machine Learning Workflow

The project follows an end-to-end machine learning pipeline:

```text
Raw Product Reviews
        ↓
Data Exploration & EDA
        ↓
Text Preprocessing
        ↓
Feature Extraction
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Model Evaluation
        ↓
PCA Visualization
        ↓
Prediction on New Reviews
```

---

## 🔍 Exploratory Data Analysis

The dataset is explored to understand patterns and distributions within the reviews.

The EDA includes visualizations that help analyze the underlying structure of the data and understand the distribution of review categories/sentiments.

![EDA 1](https://github.com/mariamAboujenane/product-review-classification/assets/106840796/d6863b56-6ea8-4f88-8aa4-695d74ae6142)

![EDA 2](https://github.com/mariamAboujenane/product-review-classification/assets/106840796/04854f0f-692d-4dd5-86f9-f7d0ebd4c697)

![EDA 3](https://github.com/mariamAboujenane/product-review-classification/assets/106840796/67d0f61f-7a1d-40ef-93bb-5949093b9465)

---

## 🤖 Model Development

A machine learning classification model is trained to identify the category/sentiment of product reviews.

The notebook contains the implementation for:

* Data preprocessing
* Feature engineering
* Model training
* Model evaluation
* Prediction on unseen reviews

The model configuration and hyperparameters are defined directly in the Jupyter notebook.

![Model](https://github.com/mariamAboujenane/product-review-classification/assets/106840796/c5602ec7-277e-4ff2-98c4-fe3e68c2f3ec)

---

## 📊 PCA Visualization

**Principal Component Analysis (PCA)** is used to reduce the dimensionality of the feature space and visualize how the different review categories are distributed.

These visualizations provide an intuitive view of the relationships between review representations in the reduced feature space.

![PCA Visualization 1](https://github.com/mariamAboujenane/product-review-classification/assets/106840796/f0ad7213-3d2d-4d38-87d8-a41c6bdaacbd)

![PCA Visualization 2](https://github.com/mariamAboujenane/product-review-classification/assets/106840796/208caf77-082c-4aba-8547-7945db5bf8f6)

![PCA Visualization 3](https://github.com/mariamAboujenane/product-review-classification/assets/106840796/8a3cb103-ab0b-402a-abed-2d8f7ab869f8)

---

## 💬 Predicting Sentiment in New Reviews

After training the model, it can be used to classify new, previously unseen product reviews.

This demonstrates how the trained NLP pipeline can be applied to real-world customer feedback.

![Sentiment Prediction](https://github.com/mariamAboujenane/product-review-classification/assets/106840796/9dd638c6-efda-4947-be4f-2319cfab4f39)

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**
* **Natural Language Processing (NLP)**
* **Principal Component Analysis (PCA)**

---

## 📂 Project Structure

```text
product-review-classification/
│
├── product_review_classification.ipynb
├── requirements.txt
└── README.md
```

### Files

| File                                  | Description                                                                                           |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| `product_review_classification.ipynb` | Main notebook containing data analysis, preprocessing, model development, evaluation, and predictions |
| `requirements.txt`                    | Python dependencies required to run the project                                                       |
| `README.md`                           | Project documentation                                                                                 |

---

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/mariamAboujenane/product-review-classification.git
```

### 2. Navigate to the Project Directory

```bash
cd product-review-classification
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
product_review_classification.ipynb
```

Alternatively, you can run the project directly in **Google Colab** using the button at the top of this README.

---

## 📈 Results

The notebook provides visual and quantitative evaluation of the classification workflow, along with predictions for new product reviews.

For detailed implementation and results, refer to the complete Jupyter notebook.

---

## 🔮 Future Improvements

Potential improvements to the project include:

* Experimenting with multiple classification algorithms.
* Hyperparameter tuning for improved model performance.
* Using advanced NLP techniques such as **TF-IDF, word embeddings, or transformer-based models**.
* Adding cross-validation for more robust evaluation.
* Deploying the trained model as a REST API or web application.
* Creating an interactive dashboard for real-time review classification.

---

## 👨‍💻 Author

**Gaurav Kumar Panjiyar**

This project demonstrates practical implementation of **Machine Learning, NLP, text classification, and data visualization** for analyzing customer reviews.
