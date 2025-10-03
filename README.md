ClientConnect AI – Generative Cold Email Automation Tool

🚀 ClientConnect AI is a Generative AI-powered tool that automates the creation of personalized cold emails for business outreach.
It extracts job listings from company career pages and generates tailored emails that include relevant portfolio links, reducing repetitive manual drafting and enhancing business development efficiency.

🔑 Features

Scrapes job listings from company career pages (e.g., Nike, Apple).

Uses LangChain + Groq API to generate context-aware cold emails.

Integrates with ChromaDB vector store to embed and retrieve portfolio/project details.

Provides a Streamlit interface for easy interactive input and instant email generation.

Ensures professional, client-first tone with smart templates.

🛠️ Tech Stack

Python

LangChain

Groq API

Streamlit

ChromaDB

pandas (CSV-based portfolio management)

📌 Example Use Case

Imagine Nike is hiring a Principal Software Engineer. Instead of spending weeks on hiring, AtliQ can provide a dedicated engineer. Using this tool, a Business Development Executive can instantly generate a professional outreach email to Nike with relevant portfolio links.

⚙️ Setup Instructions

Clone the repo:

git clone https://github.com/yourusername/ClientConnect-AI.git
cd ClientConnect-AI


Install dependencies:

pip install -r requirements.txt


Add your GROQ_API_KEY inside app/.env:

GROQ_API_KEY=your_api_key_here


Run the app:

streamlit run app/main.py
