# Career Compass

Career Compass is an AI-assisted career guidance platform for students. It combines an adaptive quiz, career roadmaps, one-to-one guidance chat, voice interaction, and account-based history.

## Tech Stack
- Vite
- React
- TypeScript
- Tailwind CSS
- FastAPI
- SQLite

## Frontend
Run locally:

```sh
npm install
npm run dev
```

## Backend
Run locally:

```powershell
cd backend
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
uvicorn main:app --reload --host 127.0.0.1 --port 8000
```

## Environment
Create a root `.env` file with:

```env
OPENAI_API_KEY=your_key_here
OPENAI_MODEL=gpt-5
VITE_AUTH_API_URL=http://127.0.0.1:8000
```
