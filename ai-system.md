# AI system

Pipeline:

User question → intent detection → authorized memory retrieval → grounded context → LLM (if configured) → safe response.

If no records match, MEMORA replies: "I don't have that information in your memories yet."

The model is instructed never to invent memories, relationships, or medical advice. Without an API key, MEMORA still answers from retrieved SQLite records using a grounded fallback so the demo remains usable.
