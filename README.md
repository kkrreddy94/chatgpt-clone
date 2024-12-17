# ChatGPT Clone Application

This is a minimal **ChatGPT-like application** built with:

- **Backend**: FastAPI (Python)
- **Frontend**: React.js
- **Model**: OpenAI GPT-4 API
- **Deployment**: Docker & Docker Compose

## Features:
- User can send messages to the chatbot.
- Chatbot responds using the GPT-4 model.

## Setup and Run:

### 1. Clone the repository:
```bash
git clone <repository-url>
cd chatgpt-clone
```

### 2. Update the OpenAI API Key:
Replace `OPENAI_API_KEY` in `docker-compose.yml`.

### 3. Run the application:
```bash
docker-compose up --build
```

- Backend: `http://localhost:8000`
- Frontend: `http://localhost:3000`

## Requirements:
- Docker & Docker Compose
- OpenAI API Key