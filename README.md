# 🤖 IntelliBot – Your AI-Powered Business Intelligence Chatbot

IntelliBot is a smart, LLM-powered chatbot designed to assist professionals with real-time competitive intelligence, persistent memory, and customizable tool integrations. This project is part of a hackathon submission and supports seamless interactions using frontend and backend APIs.

---

## 🛠️ Project Structure

- **Frontend**: Built with Python (CLI or web-based via `main.py`)
- **Backend**: FastAPI server integrating Google Gemini, Pinecone VectorDB, and custom tools

---

## 🚀 Getting Started

### ⚙️ Clone the Repository

bash
git clone https://github.com/your-username/intellibot.git
cd intellibot

💻 Running the Project
▶️ Frontend (CLI or Python UI)
python main.py
This starts the interactive chatbot frontend (CLI or basic UI) which connects with the FastAPI backend.


🌐 Backend (FastAPI Server)
Navigate to the backend directory:
cd backend

Start the FastAPI server:
uvicorn app.main:app --reload
Make sure your .env file contains your API keys (OpenAI/Gemini, Pinecone, etc.)

🧠 Key Features
✅ Long-Term Memory Support
Powered by Pinecone vector database to remember past conversations and context.

✅ Real-Time Competitive Intelligence
Retrieves latest market trends and competitor activities using live web APIs.

✅ Custom Tools Integration
Built-in tools for:

Competitor research

Financial trend analysis

Market positioning

✅ Embeddings via Gemini/Google API
Uses Google Gemini Pro for generating embeddings and responses.

✅ FastAPI Backend
Modular and scalable API setup using FastAPI for seamless LLM interactions.

✅ Chat History & Context Retention
ConversationMemory class maintains contextual relevance across sessions.

✅ Flexible UI
Frontend running via main.py (CLI/Terminal interface for now, can be extended to Streamlit/Gradio UI)

📁 Directory Structure

intellibot/
├── main.py                  # Frontend chatbot
├── backend/
│   ├── app/
│   │   ├── main.py          # FastAPI app entry point
│   │   ├── memory.py        # ConversationMemory class
│   │   ├── tools/           # Custom tools folder
│   │   └── ...
├── requirements.txt
└── README.md

📦 Installation
Python Requirements
pip install -r requirements.txt

Ensure you have environment variables set up in a .env file for:

GOOGLE_API_KEY

PINECONE_API_KEY

PINECONE_ENVIRONMENT

PINECONE_INDEX_NAME

OPENAI_API_KEY (optional fallback)

🌍 Deployment (Optional)
To deploy the backend:
uvicorn app.main:app --host 0.0.0.0 --port 8000

🤝 Contribution
Contributions are welcome! Feel free to open an issue or submit a pull request.

📜 License
MIT License © 2025 Ananya Donthoju

---

### 🔹 **3. Save the File**

Save the file after pasting.

---

### 🔹 **4. Add, Commit, and Push to GitHub**
Run these commands in your project folder to push the new `README.md` to GitHub:

```bash
git add README.md
git commit -m "Add project README with features and run instructions"
git push origin main

