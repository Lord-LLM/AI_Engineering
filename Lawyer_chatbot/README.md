# Lawyer Chatbot

A conversational AI-powered lawyer chatbot designed to assist users with legal inquiries, powered by advanced natural language processing and machine learning techniques.

## Features

- Answers legal questions in a conversational manner
- Supports multi-turn context-aware conversations
- Extensible and configurable knowledge base
- Built with Python and TypeScript
- Frontend with TypeScript/HTML/CSS; backend in Python (FastAPI or Flask based)

## Directory Structure

```
Lawyer_chatbot/
├── backend/              # Python backend (FastAPI, Flask, etc.)
├── frontend/             # TypeScript, HTML, CSS app
├── notebooks/            # Jupyter Notebooks for experimentation
├── data/                 # Training/knowledge base data
├── requirements.txt      # Python dependencies
├── package.json          # Frontend dependencies
└── README.md             # This file
```

## Getting Started

### Prerequisites

- Python 3.8+
- Node.js (v16+ recommended) & npm

### 1. Setup Python Backend

Navigate to the Lawyer_chatbot directory:

```bash
cd Lawyer_chatbot
```

Create and activate a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate            # On Unix/macOS
# OR
venv\Scripts\activate               # On Windows
```

Install required Python packages:

```bash
pip install -r requirements.txt
```

Start the backend server:

```bash
cd backend
# If using FastAPI:
uvicorn main:app --reload
# If using Flask (replace 'app.py' with your main file):
python app.py
```

### 2. Setup Frontend

Open a new terminal, navigate to the frontend directory, and install dependencies:

```bash
cd frontend
npm install
```

Build and start the frontend app:

```bash
npm run build    # If applicable
npm start        # or: npm run dev
```

### 3. Accessing the Application

- Backend API will be running at: `http://localhost:8000` (FastAPI default)
- Frontend will be running at: `http://localhost:3000` (commonly for React/Vite apps)

Make sure to configure frontend to communicate with the backend API (see `.env` or config files as needed).

## Configuration

- Environment variables (API URLs, secrets) should be placed in `.env` files in backend and frontend directories.
- Knowledge base or data sources can be adjusted in the `data/` directory.

## Development

- Jupyter notebooks in `/notebooks` directory can be used for prototyping and experiments.
- Code follows standard Python and TypeScript best practices.

## License

[MIT License](../LICENSE)

## Contributing

Pull requests welcome! For major changes, please open an issue first to discuss what you would like to change.
