📰 News Article Reader using LangChain, OpenAI & FAISS
A smart, interactive Streamlit-based application that lets you process and query news articles with the help of powerful LLMs. Load URLs or upload a list, and ask context-based questions to get summarized answers with source references.

🚀 Features
🔗 Load news article URLs manually or upload a .txt file with multiple links

🧠 Fetch and process content via LangChain’s UnstructuredURLLoader

📚 Generate semantic embeddings using OpenAI’s Embedding API

⚡ Store and retrieve information efficiently with FAISS (Facebook AI Similarity Search)

💬 Ask natural language queries and receive answers with relevant source URLs

🛠️ Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Ghara9021/news_article_reader.git
Navigate to the project directory:

bash
Copy
Edit
cd news_article_reader
Install required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Set up your OpenAI API key:
Create a .env file in the project root and add the following line:

ini
Copy
Edit
OPENAI_API_KEY=your_api_key_here
▶️ Usage
Run the app:

bash
Copy
Edit
streamlit run main.py
How it works:

Input one or more URLs on the sidebar or upload a .txt file with links

Click on "Process URLs" to:

Fetch article content

Split and embed text

Store vectors using FAISS for fast similarity search

Ask a question in the input box and receive an answer based on article content

The system also shows source links relevant to your query

📰 Sample URLs for Testing
Tata Motors, Mahindra gain certificates for production-linked payouts

Tata Motors launches Punch iCNG; price starts at ₹7.1 lakh

Buy Tata Motors, Target ₹743: KR Choksey

📁 Project Structure
bash
Copy
Edit
news_article_reader/
├── main.py                  # Streamlit application
├── requirements.txt         # List of dependencies
├── faiss_store_openai.pkl   # Saved FAISS index file
├── .env                     # Environment file with API key
📌 Credits
Built with ❤️ using:

LangChain

OpenAI Embeddings

FAISS

Streamlit
