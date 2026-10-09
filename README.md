# 😊 Sentiment Analysis Using Machine Learning

A Machine Learning-powered web application that analyzes text and predicts whether the expressed sentiment is **Positive 😊 or Negative 😞**. Built using Python, NLP techniques, TF-IDF vectorization, and Streamlit.

[![Open Live App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://sentimentanalysis-hvpv3byhkp3wmqseug2azc.streamlit.app/)

## 🚀 Live Demo

**Try the application here:** [Sentiment Analysis Web App](https://sentimentanalysis-hvpv3byhkp3wmqseug2azc.streamlit.app/)

## 📌 Project Overview

Sentiment Analysis is an NLP task that identifies the emotional polarity expressed in text. This project uses a trained Machine Learning model to classify text as positive or negative.

The application preprocesses the input text, transforms it into numerical features using TF-IDF vectorization, and generates a sentiment prediction using a saved model.

## ✨ Features

* 😊 **Sentiment Prediction:** Classifies text as Positive or Negative.
* 🧹 **Text Preprocessing:** Processes input text using NLP techniques.
* 🔤 **TF-IDF Vectorization:** Converts text into numerical features.
* 🤖 **Machine Learning Classification:** Uses a trained model for prediction.
* ⚡ **Fast Inference:** Loads saved model artifacts for predictions.
* 🖥️ **Interactive Interface:** Simple and user-friendly Streamlit application.
* ☁️ **Cloud Deployment:** Accessible online through Streamlit Community Cloud.

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-learn
* **Natural Language Processing:** NLTK
* **Feature Extraction:** TF-IDF Vectorizer
* **Model Serialization:** Joblib
* **Web Framework:** Streamlit

## 📂 Project Structure

```text
Sentiment_Analysis/
│
├── app.py                  # Streamlit web application
├── model_training.ipynb    # Model training notebook
├── sentiment_model.pkl     # Saved trained model
├── tfidf_vectorizer.pkl    # Saved TF-IDF vectorizer
├── requirements.txt        # Project dependencies
├── assets/                 # Supporting project assets
└── README.md               # Project documentation
```

## ⚙️ Machine Learning Workflow

1. **Data Loading:** Load the sentiment dataset.
2. **Data Cleaning:** Prepare the dataset for analysis.
3. **Text Preprocessing:** Clean and normalize text using the implemented NLP pipeline.
4. **Feature Extraction:** Transform text into numerical features using TF-IDF.
5. **Model Training:** Train a supervised Machine Learning classifier.
6. **Model Saving:** Save the trained model and vectorizer.
7. **Web Application:** Build an interactive interface using Streamlit.
8. **Prediction:** Classify user-provided text as Positive or Negative.

## 💻 Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/SachinChoudhary15/Sentiment_Analysis.git
```

### 2. Navigate to the Project Directory

```bash
cd Sentiment_Analysis
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application Locally

```bash
streamlit run app.py
```

Once the application starts, open the local URL displayed in your terminal.

## 💡 Example Prediction

**Input:**

```text
I really enjoyed this movie. It was amazing!
```

**Expected sentiment:**

```text
Positive 😊
```

The prediction depends on the trained model and its preprocessing pipeline.

## 📊 Model Evaluation

Model performance can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

**Note:** Add the actual test-set accuracy and the classifier name after verifying them from your model training notebook. Avoid reporting unverified performance values.

## ☁️ Deployment

The application is deployed using **Streamlit Community Cloud**.

🔗 **Live Application:** [Open the Sentiment Analysis Web App](https://sentimentanalysis-hvpv3byhkp3wmqseug2azc.streamlit.app/)

## 🔮 Future Improvements

* Extend to multi-class sentiment classification.
* Explore advanced NLP models such as LSTM and BERT.
* Add prediction confidence where supported by the model.
* Support multiple languages.
* Improve text preprocessing and model evaluation.
* Add visualizations for sentiment distribution and model performance.

## 🤝 Contributing

Contributions and suggestions are welcome. Feel free to fork the repository and submit a pull request.

## 👨‍💻 Author

Sachin Choudhary

* GitHub: [SachinChoudhary15](https://github.com/SachinChoudhary15)

---

⭐ If you find this project useful, consider giving the repository a star!

*This project is intended for educational and demonstration purposes. Predictions may not always reflect the true sentiment of a text.*
