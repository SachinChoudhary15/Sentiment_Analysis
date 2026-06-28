# 😊 Sentiment Analysis using Machine Learning

## 📌 Project Overview

This project is a **Sentiment Analysis Web Application** built using **Machine Learning** and **Streamlit**. It predicts whether a given text expresses a **Positive** or **Negative** sentiment.

The application preprocesses the input text, transforms it into numerical features using TF-IDF Vectorization, and predicts the sentiment using a trained Machine Learning model.

---

## 🚀 Features

* Predicts Positive or Negative sentiment
* Text preprocessing using NLTK
* TF-IDF Vectorization
* Machine Learning based classification
* Interactive Streamlit Web Interface
* Simple and user-friendly UI

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Streamlit
* Joblib

---

## 📂 Project Structure

```text
Sentiment_analysis/
│
├── app.py
├── model_training.ipynb
├── requirements.txt
├── README.md
│── sentiment_model.pkl
└── tfidf_vectorizer.pkl
└── assets/
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Sentiment_analysis.git
```

Move to the project folder

```bash
cd Sentiment_analysis
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the virtual environment

### Windows

```bash
venv\Scripts\activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 📊 Workflow

1. Load Dataset
2. Data Cleaning
3. Text Preprocessing
4. TF-IDF Feature Extraction
5. Train Machine Learning Model
6. Save Model
7. Build Streamlit Web App
8. Predict Sentiment

---

## 📈 Model Performance

* Accuracy: **(Add your model accuracy here)**
* Algorithm: **(Example: Logistic Regression / Naive Bayes / Random Forest)**

---

## 💡 Example

**Input

```text
I really enjoyed this movie. It was amazing!
```

**Prediction

```text
Positive 😊
```

---

## 📌 Future Improvements

* Multi-class Sentiment Analysis
* Deep Learning (LSTM/BERT)
* Deploy on Streamlit Cloud or Render
* Add Confidence Score
* Support Multiple Languages

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork this repository and submit pull requests.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Sachin Choudhary

GitHub: [https://github.com/your-username](https://github.com/your-username)
