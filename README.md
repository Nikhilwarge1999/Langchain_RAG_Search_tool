LangChain + Groq Agent with Search Tools 🔍🚀
This notebook demonstrates how to build an intelligent AI agent using LangChain, Groq LLMs, and various search tools like Wikipedia, ArXiv, and a custom RAG-based search.

✨ Features
LangChain Agents using create_openai_tools_agent

Groq Llama 3-70B Model integration (langchain_groq)

Wikipedia Tool for general knowledge search

ArXiv Tool for academic paper search

Custom RAG Tool using:

Hugging Face Embeddings for document encoding

FAISS for vector similarity search

LangChain Hub for standardized prompt templates

⚙️ How It Works
The agent pulls a system prompt from LangChain Hub.

Based on the user's query, it selects the right tool:

If the query is general knowledge ➔ searches Wikipedia.

If the query is research-focused ➔ searches ArXiv.

If private knowledge retrieval is needed ➔ queries Custom RAG.

The agent uses the Groq Llama 3-70B model to reason, choose the tool, retrieve information, and generate a final response.

📦 Tech Stack
Python 🐍

LangChain 🛠

Groq LLMs (via langchain_groq) 🧠

Hugging Face Embeddings 🤗

FAISS for Vector Search ⚡

LangChain Hub 🌐

Wikipedia / ArXiv APIs 📚 / Custome Tool RAG pipline

📋 Installation
Clone the repository and install required packages:

git clone https://github.com/Nikhilwarge1999/Langchain_RAG_Search_tool/edit/main
cd langchain-groq-agent-search
Make sure you have a .env file with your GROQ_API_KEY:

GROQ_API_KEY=your_groq_api_key_here
🚀 Running the Notebook
Simply run the Langchain_search_tools.ipynb notebook step-by-step to see the agent in action!

📄 Example Query

Q: "Find me the latest research on Quantum Computing."
The agent checks ArXiv papers and returns a summary.

Q: "Tell me about the history of Artificial Intelligence."
The agent uses Wikipedia to find and summarize the answer.

Q: "What internal guidelines should we follow for AI development?"
The agent retrieves from your private knowledge base via RAG.

🛡 Disclaimer
This project is for educational and experimental purposes only. 🚀
For production use, additional security, authentication, and API handling improvements would be necessary.

🤝 Connect
Feel free to connect with me on LinkedIn if you want to collaborate or discuss Generative AI innovations! 🚀

#LangChain #Groq #FAISS #HuggingFace #Python #GenerativeAI #RAG #Agents #Retrieval #Arxiv #Wikipedia #AIResearch

✅ Done!
Would you also like me to quickly give you a sample requirements.txt file to go with this GitHub repo? (Just say “requirements too!”) 📦
