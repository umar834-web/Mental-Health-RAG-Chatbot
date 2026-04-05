# 🧠 Mental Health Chatbot with Controlled Hallucination

A Retrieval-Augmented Generation (RAG) based chatbot designed to provide safe, empathetic, and context-aware mental health support.

---

## 🚀 Features

- 🤖 Empathetic conversational AI
- 📚 Retrieval-Augmented Generation (RAG)
- 🧠 Hallucination reduction using context retrieval
- 🛡️ Safety layer for crisis detection
- 💾 Vector databases (FAISS + Chroma)
- 🔍 Semantic search using embeddings
- 📊 Evaluation (BLEU, ROUGE)
- 🌐 Streamlit-based UI

---

## 🏗️ Tech Stack

- Python
- LangChain
- HuggingFace Transformers
- FAISS (Vector DB)
- ChromaDB (Vector DB)
- Sentence Transformers
- Streamlit

---

## ⚙️ System Architecture

User Query → Retriever → Context → LLM → Response

---

## 📂 Project Structure


mental-health-chatbot/
│── Mental_Health_RAG_Assignment.ipynb
│── app.py
│── README.md
│── requirements.txt
│── data/


---

## ▶️ How to Run

### 1. Install dependencies


pip install -r requirements.txt


### 2. Run Notebook

Open:

Mental_Health_RAG_Assignment.ipynb


### 3. Run UI


streamlit run app.py


---

## 🧪 Evaluation

- BLEU Score (text similarity)
- ROUGE Score (overlap evaluation)
- Qualitative analysis (empathy, safety)

---

## 🛡️ Safety Features

- Detects high-risk queries (self-harm, distress)
- Provides safe fallback responses
- Suggests helpline support

---

## 📞 Helpline (India)

- AASRA: 9152987821

---

## ⚠️ Disclaimer

This chatbot is NOT a substitute for professional medical advice.  
Please consult a licensed professional for serious mental health concerns.

---

## 👨‍💻 Author

Umar

---

🔧 Fine-Tuning (Assignment-2)

This project includes fine-tuning of an LLM using QLoRA (PEFT).



🧠 Key Features:

Instruction-based dataset

LoRA adapters

8-bit quantization

Efficient training on Colab


📊 Results

| Model            | Performance       |
| ---------------- | ----------------- |
| Base Model       | Generic responses |
| Fine-Tuned Model | Empathetic + safe |


🚀 How to Run Fine-Tuning

pip install transformers datasets peft bitsandbytes accelerate

python finetuning.py
