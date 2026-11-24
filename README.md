# AI Travel Planner — RAG + Streamlit

Lightweight AI Travel Planner scaffold using RAG (LangChain), ChromaDB embeddings, and a Streamlit frontend.

Quick start

1. Create a `.env` with your API keys (Google Generative AI key named `GOOGLE_API_KEY`, SMTP creds, etc.).
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:

```bash
streamlit run travel_planner_project/app.py
```

Files

- `travel_planner_project/app.py`: Streamlit frontend
- `travel_planner_project/agent.py`: RAG agent and planning logic
- `travel_planner_project/tools.py`: Weather, geocoding, currency, email helpers
- `travel_planner_project/utils.py`: Document loaders and chunking utilities

Notes

- Replace the placeholder API key locations with your keys. The Google Generative AI key can be obtained at https://aistudio.google.com/apikey
- This scaffold is intended as a clear, easy-to-understand starting point.