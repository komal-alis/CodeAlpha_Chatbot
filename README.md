# 🤖 CodeAlpha FAQ Chatbot

An intelligent **FAQ Chatbot** developed as part of the **CodeAlpha Artificial Intelligence Internship**. This project uses **Natural Language Processing (NLP)** techniques to understand user queries and provide the most relevant answers from a predefined FAQ dataset.

## ✨ Features

- 💬 Interactive chatbot interface
- 🧠 NLP-based text preprocessing
- 🔍 Finds the most relevant answer using **TF-IDF Vectorization**
- 📊 Uses **Cosine Similarity** for question matching
- ⚡ Fast and lightweight implementation
- 🛠️ Easy to customize with your own FAQs

## 🛠️ Technologies Used

- Python
- NLTK
- Scikit-learn
- Pandas
- NumPy

## 📂 Project Structure


CodeAlpha_FAQ_Chatbot/
│
├── faq_chatbot.py
├── FAQs.csv
├── requirements.txt
├── README.md
└── assets/


## 🚀 How It Works

1. Load the FAQ dataset containing questions and answers.
2. Preprocess the text using NLP techniques.
3. Convert the questions into numerical vectors using **TF-IDF**.
4. Compare the user's query with existing FAQs using **Cosine Similarity**.
5. Return the most relevant answer as the chatbot response.

## ⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/CodeAlpha_FAQ_Chatbot.git
cd CodeAlpha_FAQ_Chatbot


Install the required dependencies:


pip install -r requirements.txt


## ▶️ Usage

Run the chatbot using:

python faq_chatbot.py


Enter your questions in the terminal, and the chatbot will provide the best matching response.

Example:

You: What are your working hours?
Bot: Our support team is available from 9 AM to 6 PM, Monday to Friday.


## 📌 Future Enhancements

- Add a graphical user interface (GUI)
- Integrate voice-based interaction
- Connect with a database for dynamic FAQs
- Deploy as a web application using Flask or Streamlit

## 🎯 Internship Task

This project was developed to fulfill **Task 2: Chatbot for FAQs** under the **CodeAlpha Artificial Intelligence Internship Program**.

## 👨‍💻 Author

Komal Ojha

Artificial Intelligence Intern at **CodeAlpha**

## 📄 License

This project is intended for educational and learning purposes.
