# 🦜 LangChain Lab

A hands-on learning repository where I explored **LangChain v1** from the ground up — covering model integrations, tools, structured outputs, middleware, and more — using Jupyter notebooks.

---

## 📓 Notebooks Overview

| # | Notebook | What I Learned |
|---|---|---|
| 1 | `1-langchainintro.ipynb` | LangChain basics, basic agents |
| 2 | `2-modelintegration.ipynb` | OpenAI, Google Gemini & Groq integration, Streaming, Batch processing |
| 3 | `3-tools.ipynb` | Tool creation with `@tool`, binding tools to models, Tool Execution Loops |
| 3 | `3-dataparsingdoc.ipynb` | Word document processing and parsing |
| 4 | `4-messages.ipynb` | Message types — System, Human, AI, Tool messages |
| 5 | `5-structuredoutput.ipynb` | Structured output using Pydantic, TypedDict, and DataClasses |
| 5 | `5-jsonparsing.ipynb` | JSON parsing and processing strategies |
| 6 | `6-middleware.ipynb` | Middleware — logging, summarization, human-in-the-loop, guardrails |
| 6 | `6-databaseparsing.ipynb` | SQL database content extraction |

---

## 🛠️ Tech Stack

- **Framework:** [LangChain](https://www.langchain.com/) v1
- **LLMs:** OpenAI, Google Gemini, Groq
- **Schema Validation:** Pydantic, TypedDict, DataClasses
- **Environment:** Jupyter Notebooks
- **Python:** 3.13+

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/langchain-lab.git
cd langchain-lab
```

### 2. Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate        # Mac/Linux
.venv\Scripts\activate           # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set up environment variables

Create a `.env` file in the root directory:

```
OPENAI_API_KEY=your_openai_key_here
GROQ_API_KEY=your_groq_key_here
GOOGLE_API_KEY=your_google_api_key_here
```

> 🔑 Get your keys from [OpenAI](https://platform.openai.com/), [Groq](https://console.groq.com/), and [Google AI Studio](https://aistudio.google.com/)

### 5. Launch Jupyter

```bash
jupyter notebook
```

---

## 📁 Project Structure

```
langchain-lab/
├── 1-langchainintro.ipynb
├── 2-modelintegration.ipynb
├── 3-tools.ipynb
├── 3-dataparsingdoc.ipynb
├── 4-messages.ipynb
├── 5-structuredoutput.ipynb
├── 5-jsonparsing.ipynb
├── 6-middleware.ipynb
├── 6-databaseparsing.ipynb
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

---

## 📦 Dependencies

```
langchain
langchain_community
langchain-openai
langchain-groq
langchain-google-genai
python-dotenv
```

---

## 🔐 Security Note

Never commit your `.env` file. Add it to `.gitignore` and share a `.env.example` with dummy values instead:

```
OPENAI_API_KEY=your_openai_key_here
GROQ_API_KEY=your_groq_key_here
GOOGLE_API_KEY=your_google_api_key_here
```

---

## 📚 Learning Resources

- [LangChain Docs](https://docs.langchain.com/)
- [LangChain Conceptual Guide](https://docs.langchain.com/docs/concepts/)
- [OpenAI API Docs](https://platform.openai.com/docs/)
- [Groq Console](https://console.groq.com/)
- [Google AI Studio](https://aistudio.google.com/)

---

## 👤 Author

**Venkatesh**
[GitHub](https://github.com/your-username) • [LinkedIn](https://linkedin.com/in/your-profile)

---

## 📄 License

MIT License — feel free to use this as a reference for your own LangChain learning journey!
