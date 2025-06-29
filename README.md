# 📰 News Article Reader

A smart, interactive Streamlit-based application that lets you process and query news articles with the help of powerful LLMs. Load URLs or upload a list, and ask context-based questions to get summarized answers with source references.

---

## 🚀 Features

- 🔗 Load news article URLs manually or upload a `.txt` file with multiple links  
- 🧠 Fetch and process content via **LangChain’s `UnstructuredURLLoader`**  
- 📚 Generate semantic embeddings using **OpenAI’s Embedding API**  
- ⚡ Store and retrieve information efficiently with **FAISS (Facebook AI Similarity Search)**  
- 💬 Ask natural language queries and receive answers with relevant source URLs  

---

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Ghara9021/news_article_reader.git

2. **Navigate to the project directory**:
   ```bash
   cd news_article_reader
3. **Install required dependencies**:
   ```bash
   pip install -r requirements.txt
4. **Set up your OpenAI API key**:
   ```bash
   OPENAI_API_KEY=your_api_key_here

---

## Usage

1.**Run the Streamlit app by executing**:
   ```bash
   streamlit run main.py
   ```
---

## Project Structure

- `main.py`: The main Streamlit application script.
- `requirements.txt`: List of required Python packages.
- `faiss_store_openai.pkl`: Pickle file storing the FAISS vector index.
- `.env`: Stores your OpenAI API key and other environment variables.



