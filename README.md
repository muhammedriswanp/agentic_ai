# agentic_ai

AI-powered blood work analysis using LangChain + Google Gemini.

## Setup

```powershell
uv venv
uv sync
```

## Environment

Copy `.env.example` to `.env` and add your Google API key:

```
GOOGLE_API_KEY=your_key_here
```

## Usage

Run the Streamlit app:

```powershell
uv run streamlit run streamlit_app/app.py
```

Upload a blood work text file or use the included sample (`notebook/blood_work.txt`) to get an AI-generated health analysis.
