# Agentic AI class

Notebooks and code for the class, one folder per lecture under `classes/`.

## Setup

1. Create and activate a virtual environment:

   ```
   python3 -m venv .venv
   source .venv/bin/activate
   ```

2. Install the packages for the lecture you are working on. Each lecture folder has its own `requirements.txt`, for example:

   ```
   pip install -r classes/08-rag/requirements.txt
   ```

3. Copy `.env.example` to `.env` in the project root and fill in your own values:

   ```
   cp .env.example .env
   ```

   `.env` holds your API key. It is git-ignored. Never commit it.

4. Open a notebook in VS Code and pick the `.venv` kernel. Restart the kernel after you change `.env`.
