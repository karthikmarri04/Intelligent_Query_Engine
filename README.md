# 📚 Intelligent Query Engine

✨ An intelligent semantic search system powered by FAISS that retrieves relevant information from a custom knowledge base using meaning-based search instead of keyword matching.

---

## 🚀 Overview

The **Intelligent Query Engine** is designed to perform fast and accurate searches across documents like PDFs and text files.  
It converts text into vector embeddings and uses FAISS (Facebook AI Similarity Search) for high-speed similarity matching.

---

## 🧠 Key Features

🔍 Semantic search (understands meaning, not just keywords)  
⚡ Fast retrieval using FAISS indexing  
📄 Supports PDF and text knowledge sources  
🖥️ Interactive UI using Streamlit  
🧩 Modular backend design  

---

## 🏗️ System Workflow

➡️ Data Collection (PDF / TXT files)  
➡️ Text Preprocessing  
➡️ Convert text → embeddings  
➡️ Store embeddings in FAISS  
➡️ User enters query  
➡️ Query → embedding  
➡️ Similarity search  
➡️ 📊 Relevant results displayed  

---

## 📂 Project Structure
Intelligent_Query_Engine/
│
├── backend/                  ⚙️ Core logic
│   ├── create_index.py
│   ├── create_tables.py
│   ├── main.py
│   └── requirements.txt
│
├── frontend/                 🖥️ UI (Streamlit)
│   └── app.py
│
├── knowledge_base/           📚 Input data
│   ├── oops_java.pdf
│   └── webscraping.txt
│
├── faiss_index/              📦 Generated index
│   ├── index.faiss
│   └── index.pkl
│
└── pip_installs.txt          📌 Setup commands


---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
git clone https://github.com/your-username/Intelligent_Query_Engine.git

cd Intelligent_Query_Engine


### 2️⃣ Install Dependencies
pip install -r backend/requirements.txt


### 3️⃣ Create FAISS Index

python backend/create_index.py


### 4️⃣ Run Backend

python backend/main.py


### 5️⃣ Run Frontend

streamlit run frontend/app.py
---

## 🖥️ How It Works

💡 Documents → converted into vectors  
💡 Query → converted into vector  
💡 FAISS → finds closest matches  
💡 🎯 Output → most relevant results  

---

## 🛠️ Technologies Used

🐍 Python  
⚡ FAISS  
🧠 NLP / Embeddings  
🖥️ Streamlit  

---

## 📌 Applications

📚 Document search engines  
🤖 AI chatbots  
🔎 Research tools  
📊 Knowledge retrieval systems  

---

## 📈 Future Improvements

🚀 Advanced NLP models (Transformers)  
🎨 Better UI/UX  
☁️ Cloud deployment  
🌍 Multi-language support  

