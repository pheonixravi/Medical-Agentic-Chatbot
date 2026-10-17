# Medical-Agentic-Chatbot
 Build an End-to-End Agentic AI Medical Chatbot with LangGraph, Pinecone, Tavily, FastAPI, Voice &amp; Vision.
# Requirements
Python 3.11 or 3.12; OpenAI, Pinecone, and Tavily API keys; 

# Step 1:
- create venv 
>python -m venv .medical-agenticai-chatbot
- activate venv
>.medical-agenticai-chatbot\Scripts\activate
- install dependencies
>pip install -r requirements.txt

- run main app
uvicorn app.main:app --reload --host 127.0.0.1 --port 8000
