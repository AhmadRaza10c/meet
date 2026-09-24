# openchat
- Frontend: Next.js 16,React 19, Typescript 7,Tailwind CSS 4, shadcn/ui
- Backend: FastAPI, Python 3.13, python uv, ruff, pytest
- AI: Ollama at localhost:11434, model gemma3:1b, Local AI APIs
- AI: OpenAI or Anthropic or Grok or GEmini Cloud AI APIs(fallback)
<!-- - Run everything: ./start.sh -->
- Start Frontend (port 3000)
cd frontend/
npm run dev
- Start Backend (port 8000)
cd backend/
uv run fastapi dev

- Install Backend dependancies: uv add <package_name>
- uv sync (if project clone)

- Install Froetend ependancies: npm install <package_name>

- Test: cd backend && pytest

# Rules 

- Never commit .env or API keys
- Run and tests after every change