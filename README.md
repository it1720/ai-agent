# Developer Tools Research Agent
Developer Tools Research Agent je nástroj pro vyhledávání, analýzu a porovnávání vývojářských nástrojů za využití LangGraph a přístupu RAG (Retrieval-Augmented Generation). Kombinuje scraping (Firecrawl) a jazykový model (OpenAI), aby vývojářům poskytl rychlá a přehledná doporučení.

.
├── main.py               # Vstupní bod aplikace
├── src/
│   ├── workflow.py       # Definice LangGraph workflow (extrakce → research → analýza → doporučení)
│   ├── models.py         # Pydantic modely pro reprezentaci stavu, informací o firmách a analýz
│   ├── prompts.py        # Sada promptů pro LLM – extrakce nástrojů, analýza obsahu, doporučení
│   └── firecrawl.py      # Integrace se službou Firecrawl (vyhledávání a scraping webu)

