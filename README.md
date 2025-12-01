# MedAI, a Medical Q&A Chatbot 🧠

**A Retrieval-Augmented Medical Question-Answering System with LangChain, MongoDB, Hugging Face, and a Desktop GUI.**

# Overview 📘

**This project is a Medical AI Assistant that answers medical questions using real medical research stored inside a MongoDB database.**

**It uses:**

**• MongoDB → stores vector embeddings + medical text**

**• Sentence Transformers/HuggingFace embeddings → for encoding queries/documents**

**• Cosine similarity search → retrieves the most relevant medical context**

**• Hugging Face LLM → generates a final natural-language answer**

**• Tkinter GUI → user-friendly desktop interface**

**• The system follows a RAG pipeline to ensure answers are grounded in scientific content**

# Features 🚀
**1- Retrieval-Augmented Generation**

**2= Automatically retrieves the most relevant medical document using cosine similarity.**

**3- MongoDB Vector Database**

**4- Stores (embedding vectors + original text).**

**5- Local GUI Application**

**6- Dark-themed Tkinter interface:**

- Enter your question

- Click Ask AI

- See the final answer 

- Fast, clean, and lightweight

**7- Custom Prompting**

**8- Uses a structured medical prompt to ensure accurate and safe responses.**

**9- Batch Embedding Upload**

**10- Supports efficient embedding of thousands of documents using batching.**

# How to setup ⚙️
**1- Install the requirements.txt file (pip install -r requirements.txt)**

**2- Create a MongoDB account by following these instructions: https://www.youtube.com/shorts/pIHvoXkwmq4**

**Add your actual information in place of:**

client = MongoClient("Your MongoDB URL")

db = client["Your DB name"]

collection = db["Your collection name"]

**3- Run the entire notebook cells**

## The notbook includes detailed instructions, if you have further questions, feel free to reach out! 🤝
