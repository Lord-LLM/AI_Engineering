# Bilingual RAG Chatbot on Constitution of Kenya

A bilingual AI chatbot leveraging Retrieval Augmented Generation (RAG) to answer questions about the Constitution of Kenya in both English and Swahili. This project combines state-of-the-art natural language processing with search to provide informed, context-aware, and accessible legal assistance.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

The Bilingual RAG Chatbot enables users to interactively explore and query the Constitution of Kenya. Users can ask questions in English or Swahili, and the chatbot responds with contextually grounded, accurate information sourced from the official text of the Constitution.

---

## Features

- **Bilingual Support:** Asks and answers in both English and Swahili.
- **Retrieval Augmented Generation (RAG):** Combines search with generative AI for accurate, source-grounded answers.
- **Legal Contexts:** Specifically focused on Kenya’s Constitution and legal context.
- **User-friendly Web Interface:** Modern, interactive frontend for easy use.
- **Extensible:** Modular codebase for adding new documents or languages.

---

## Tech Stack

- **AI & Backend:**
  - Python (FastAPI, LangChain, or custom RAG pipeline)
  - Document retriever (OpenAI, HuggingFace Transformers, or similar)
- **Frontend:**
  - TypeScript, HTML, CSS
  - React or other framework for UI
- **Data:**
  - Official Constitution of Kenya (preprocessed for retrieval)
  - Swahili/English translation resources
- **Other:**
  - Jupyter Notebooks (experimentation, documentation)
  - Jac (experimental workflows or knowledge graph)

---

## Getting Started

### Prerequisites

- Python 3.9+
- Node.js & npm
- (Optional) GPU for faster inference
- Clone the repository

```bash
git clone https://github.com/Lord-LLM/AI_Engineering.git
cd AI_Engineering/Bilingual-RAG-Chatbot-on-Constitution-of-Kenya
```

### Backend Setup

1. (Optional) Create and activate a Python virtual environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Preprocess data and initialize the knowledge base (see `/notebooks` or `/data`).

4. Run the API server:

```bash
python app.py
```

### Frontend Setup

1. Navigate to the `frontend` directory (if applicable):

```bash
cd frontend
npm install
npm start
```

---

## Usage

- Open the frontend in your browser (`http://localhost:3000` or specified port).
- Ask questions about the Constitution in English or Swahili.
- The chatbot retrieves relevant sections, generates an answer, and provides source references.

---

## Project Structure

```
Bilingual-RAG-Chatbot-on-Constitution-of-Kenya/
│
├── app.py                 # Main backend API/app
├── requirements.txt       # Python dependencies
├── frontend/              # Web UI (TypeScript/React)
├── data/                  # Constitution text and processed chunks
├── notebooks/             # Jupyter Notebooks (experiments/preprocessing)
├── jac/                   # Jac scripts (workflows/knowledge management)
├── README.md
└── ...
```

---

## Contributing

Contributions are welcome! Please open issues, submit pull requests, or suggest features. For major changes, please open an issue first to discuss your ideas.

---

## License

[MIT License](../LICENSE) — see the LICENSE file for details.

---

## Acknowledgments

This project is inspired by open-source RAG architectures and aims to enhance legal literacy in Kenya. Special thanks to contributors of open-source AI frameworks and the Kenyan legal community.
