# AI-NEXUS  
Transformer-Enhanced Stable Diffusion Interface

AI-NEXUS is a locally-hosted, text-to-image generation interface built on top of Stable Diffusion and Open WebUI. It integrates transformer-based language models to provide a seamless experience for developers, researchers, and creative professionals.

---

## Features

- Transformer-based language model integration for natural language input
- Stable Diffusion backend for high-quality image generation
- Simple and responsive user interface built with modern web technologies
- Local deployment for data privacy and speed
- Flexible codebase for easy customization and expansion

---

## Tech Stack

- Backend: Python, FastAPI
- Frontend: React.js, Tailwind CSS
- Image Generation: Stable Diffusion
- LLM Support: Integration with transformer-based models (e.g., Gemma 1B)

---

## Installation

### Prerequisites

- Python 3.10+
- Git
- Node.js and npm
- GPU (recommended for fast image generation)

### Clone the Repository

```bash
git clone https://github.com/prachidubeyyy/AI-NEXUS.git
cd AI-NEXUS
```

Set Up Backend
cd backend
pip install -r requirements.txt

Set Up Frontend
cd ../frontend
npm install
npm run dev

Start the Backend
cd ../backend
python main.py

Usage
1. Open your browser and go to http://localhost:3000
2. Enter your text prompt in the input box
3. Click "Generate" to view the AI-generated image
4. Customize settings like model type, prompt length, etc.

Project Structure
AI-NEXUS/
├── backend/             # FastAPI backend
│   ├── main.py
│   └── ...
├── frontend/            # React frontend
│   ├── src/
│   └── ...
├── README.md
└── requirements.txt
