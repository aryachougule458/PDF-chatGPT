# PDF-ChatGPT

An Enterprise Document Intelligence and Retrieval-Augmented Generation (RAG) web application running locally with Ollama.

## Project Structure

```
pdf-chatgpt/
├── app.js               # Frontend client logic & streaming chat UI
├── document-library.js  # Document indexing, embedding & chunk search
├── favicon.svg          # Application icon
├── index.html           # Main frontend layout
├── package.json         # Project metadata and dependencies
├── package-lock.json    # Lockfile for reproducible installs
├── server.js            # Express backend & Ollama streaming API
├── style.css            # Stylesheet (dark/light themes)
├── data/                # Stored uploaded PDFs and document index
└── node_modules/        # Installed Node.js dependencies
```

## Prerequisites

1. **Node.js** (v18 or higher recommended)
2. **Ollama** installed and running on your system:
   - Make sure Ollama is started:
     ```bash
     ollama serve
     ```
   - Pull the required LLM and embedding models:
     ```bash
     ollama pull llama3.2
     ollama pull nomic-embed-text
     ```

## How to Run

1. Open PowerShell or Command Prompt.
2. Navigate to this project directory:
   ```bash
   cd C:\Users\sutar\pdf-chatgpt
   ```
3. (Optional) Reinstall or update dependencies if needed:
   ```bash
   npm install
   ```
4. Start the server:
   ```bash
   npm start
   ```
   *(or `node server.js`)*
5. Open your web browser and go to:
   ```
   http://localhost:4173
   ```

