# Developer Tools Research Agent
Developer Tools Research Agent je nástroj pro vyhledávání, analýzu a porovnávání vývojářských nástrojů za využití LangGraph a přístupu RAG. Kombinuje scraping (Firecrawl) a OpenAI, aby vývojářům poskytl rychlá a přehledná doporučení.

## 📂 Struktura projektu

- **`main.py`** – vstupní bod aplikace
- **`src/`** – zdrojové soubory:  
  - **`workflow.py`** – definice LangGraph workflow (extrakce → research → analýza → doporučení).  
  - **`models.py`** – Pydantic modely pro reprezentaci stavu, informací o firmách a analýz.  
  - **`prompts.py`** – sada promptů pro LLM (extrakce nástrojů, analýza obsahu, doporučení).  
  - **`firecrawl.py`** – integrace se službou Firecrawl (vyhledávání a scraping webu).  

