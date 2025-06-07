# 📰 News Article Reader (LLM-Powered)

This project is an intelligent News Article Reader that uses Large Language Models (LLMs) to retrieve and answer user queries based on the content of three news articles provided via URLs. It leverages OpenAI embeddings, FAISS vector search, and LangChain's Retrieval QA capabilities to ensure relevant, sourced answers.

---

## 🚀 Features

- 🔗 Accepts **3 news article URLs** as input  
- 📄 Extracts and processes raw content from each link  
- ✂️ Splits content into manageable text chunks  
- 🧠 Converts chunks to **vector embeddings** using OpenAI  
- 📚 Stores them in a **FAISS vector database**  
- ❓ Answers user questions via **Retrieval-based QA**  
- 🔍 Provides **source references** for each response  
