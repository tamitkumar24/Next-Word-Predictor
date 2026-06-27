# Next Word Prediction using LSTM 🧠

A Deep Learning based **Next Word Prediction** application built using **LSTM (Long Short-Term Memory)** and deployed with **Streamlit**.

The model predicts the next possible word based on the input sentence provided by the user.

---

## 🚀 Project Overview

Language models are used to predict the next word in a sequence of text.  
This project uses an **LSTM Neural Network** to learn patterns from text data and generate the most probable next word.

Example:

Input:I love machine


Prediction:

learning


---

## ✨ Features

- Predicts the next word from user input
- Built using LSTM Deep Learning model
- Uses NLP text preprocessing
- Interactive Streamlit web interface
- Fast prediction using saved trained model
- Simple and user-friendly UI

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- LSTM Neural Network
- Natural Language Processing (NLP)
- Streamlit
- NumPy
- Pickle

---

## 📂 Project Structure


Next-Word-Prediction/

│
├── app.py # Streamlit application
│
├── lstm_model.h5 # Trained LSTM model
│
├── tokenizer.pkl # Saved tokenizer
│
├── max_len.pkl # Maximum sequence length
│
├── requirements.txt # Required libraries
│
└── README.md


---

## ⚙️ Installation and Setup

### Clone the repository

```bash
git clone https://github.com/your-username/next-word-predictor.git

Go inside the project folder:

cd next-word-predictor
Install dependencies
pip install -r requirements.txt
▶️ Run Application

Start Streamlit:

streamlit run app.py
