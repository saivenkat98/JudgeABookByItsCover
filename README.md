# Judge A Book By Its Cover 👨🏽‍⚖️📚📔

## 🎯 Project Objective

Many readers struggle to continue their reading habit because finding the *right* book after finishing a good one becomes difficult. This project aims to **predict the genre of a book based on its title and cover image**, helping users discover similar books aligned with their tastes — much like trying to *relive a great reading experience*.

---

## 🧠 Solution Approach

The project uses both **Natural Language Processing (NLP)** and **Computer Vision (CV)** to classify book genres. Initially, it classifies based on **titles**, and then scales up to include **cover images** using deep learning.

### 📝 Text-Based Pipeline

- **Tokenization & Word Count**: Each book title is tokenized, and a count of each word’s frequency is created.
- **Vectorization**: Using CountVectorizer or similar, each title is converted into a feature vector.
- **Label Encoding**: Genre labels (target variable) are vectorized for supervised learning.

### 🖼️ Image-Based Pipeline

- Trained a **deep learning model** using Python and frameworks like **NumPy**, **Pandas**, and **Matplotlib** to predict genres based on **book cover images**.
- Dataset: 32,600 book cover images.
- Achieved **80% accuracy after 20 epochs**, with **peak metrics**:
  - **Precision**: 97%
  - **Recall**: 95%
  - **F1 Score**: 93%

---

## 🔧 Machine Learning Models Implemented

For title-based genre prediction:

1. **Logistic Regression**
2. **Multinomial Naïve Bayes**
3. **Multi-Layer Perceptron (MLP)**
4. **XGBoost**

These models were trained on vectorized title data and evaluated using the **F1 Score** metric.

---

## 🔄 Neural Network Architecture

For both title and image-based models:

- **Input Layer**: Accepts either vectorized text or image pixels.
- **Hidden Layer(s)**: Perform transformations using activation functions (e.g., ReLU) and feature extraction.
- **Output Layer**: Predicts the genre from predefined categories.

---

## 🚀 Advanced Models

To capture sequential patterns and improve title-based predictions:

- **Recurrent Neural Networks (RNN)**
- **Long Short-Term Memory (LSTM)** networks

These architectures enhance genre prediction accuracy by leveraging word order and contextual dependencies.

---

## 📊 Evaluation Metrics

- **F1 Score** used for all classical models.
- For deep learning (image-based):
  - **Accuracy over Epochs**
  - **Precision**, **Recall**, and **F1 Score** as key indicators of performance.
