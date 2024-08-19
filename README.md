# 🎥 Movie Review Sentiment Classifier - ANN

![Python](https://img.shields.io/badge/python-3.7%2B-brightgreen.svg)

An artificial neural network (ANN) for sentiment analysis of movie reviews. This project classifies reviews as **positive** or **negative** using a deep learning model built with Keras and TensorFlow.

## 🚀 Features

- **Binary Sentiment Classification**: Positive or negative sentiment analysis for movie reviews.
- **Deep Learning Model**: Two hidden layers with ReLU activation and an output layer with sigmoid activation.
- **Efficient Preprocessing**: Text vectorization and data preprocessing for optimized performance.
- **Metrics Tracking**: Accuracy measurement for evaluating model performance.

## 🛠️ Tech Stack

- **Python 3.7+**
- **Keras & TensorFlow**
- **NumPy & Pandas**

## 📁 Project Structure

```plaintext
├── data/                # Dataset files (if any)
├── models/              # Saved models (optional)
├── Movie_Review_ANN.ipynb # Jupyter Notebook with model code
├── README.md            # Project README file
└── requirements.txt     # Dependencies
```

## 📦 Setup & Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Vamsi404/MovieReviewSentimentClassifier-ANN.git
   cd MovieReviewSentiment-ANN
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook:**

   ```bash
   jupyter notebook Movie_Review_ANN.ipynb
   ```

## 🧠 Model Overview

The model consists of:
- **Input Layer**: Processes 10,000 features.
- **Hidden Layers**: Two dense layers with 16 units each, using ReLU activation.
- **Output Layer**: Single unit with sigmoid activation for binary classification.

## 📊 Results & Evaluation

- **Loss Function**: Binary Crossentropy
- **Optimizer**: RMSprop
- **Performance Metrics**: Accuracy

The model is designed to effectively classify sentiment in movie reviews with high accuracy.

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue.