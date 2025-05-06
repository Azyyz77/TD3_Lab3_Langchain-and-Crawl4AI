# 🧠 LangChain + Groq Agent Project Requirements

This project uses LangChain, Groq's LLaMA-3 model, and agent tools to create a structured AI assistant capable of:
- Math calculations
- Web searches
- Pydantic output parsing

---

## 📦 Required Python Packages

| Package                | Purpose                                                                |
|------------------------|------------------------------------------------------------------------|
| `langchain`            | Core framework for chaining LLMs and tools                             |
| `langchain_community`  | Access to community-contributed tools like DuckDuckGoSearchRun         |
| `langchain_groq`       | Integration of Groq's LLaMA-3 model with LangChain                     |
| `pydantic`             | Structured schema parsing with Pydantic models                         |
| `python-dotenv`        | Load API keys and environment variables securely                       |
| `duckduckgo-search`    | Used internally for the DuckDuckGo tool (search engine interface)      |

---

## 🛠️ Installation

Install all required packages using `pip`:

```bash
pip install langchain langchain_community langchain_groq pydantic python-dotenv duckduckgo-search
