# 🤖 MITS AI-Powered FAQ + Career Chatbot

This is a smart, AI-driven chatbot built for the **MITS Medium-Level Internship Project**.  
It uses real **Natural Language Processing (NLP)** to understand and respond to questions about:

- 📚 Internships
- 📂 Project submission
- 🎓 Certificates
- 🧭 Career guidance

Built with Python and Gradio, this chatbot goes beyond simple Q&A — it uses **TF-IDF vectorization** and **cosine similarity** to match user input with relevant answers, even if the question isn't typed exactly.

---

## 🚀 Features

- 🧠 **TF-IDF + Cosine Similarity** for NLP-based matching  
- 🗂️ Handles both internship-related and career-oriented questions  
- 💬 Clean, responsive **Gradio chat UI**  
- 📱 Works on mobile & desktop (Colab-deployable)  
- 🔁 Easily expandable with more FAQs

---


---

## 🧠 Technologies Used

- **Python 3**
- **Gradio** (for chat interface)
- **Scikit-learn** (TF-IDF vectorizer & cosine similarity)


---

## 🧩 How It Works

1. The bot stores a list of predefined FAQ questions and answers.
2. It converts all known questions into **TF-IDF vectors**.
3. When a user types a question, it also gets vectorized and compared.
4. The most similar question is found using **cosine similarity**.
5. If the similarity score is above the confidence threshold, it responds.
6. If not — a fallback "Sorry bro" message is shown.

---


## ✅ Deployment Instructions

1. Open the `.ipynb` file in Google Colab
2. Run all cells
3. Click the Gradio link to start chatting
4. Ask anything related to your internship or career

