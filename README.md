# BhashaSetu — SIH26042 Multilingual Vernacular Pedagogy Platform

This repository contains the complete Smart India Hackathon 2026 prototype for problem statement **SIH26042 (BhashaSetu)**. The platform helps primary-school teachers teach children in their mother tongue (focusing on Santali/Santhali, Ho, and Mundari) using AI translation, speech processing, and offline-first curriculum content.

## Project Structure
- `backend/`: FastAPI Python backend for database management, user auth, syncing, and translation fallbacks.
- `frontend/`: React + TypeScript + Vite + Tailwind CSS frontend application.
- `ml/`: Model wrapping scripts and evaluation code for ASR, Translation, and TTS.
- `data/`: Dictionaries, glossaries, and seeded curriculum data.
- `docs/`: Technical specifications, guides, and architectures.

## Setup Instructions

### Backend Setup
1. Navigate to the `backend/` directory.
2. Create a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Create a `.env` file from the template and start the FastAPI dev server:
   ```bash
   uvicorn app.main:app --reload
   ```

### Frontend Setup
1. Navigate to the `frontend/` directory.
2. Install npm dependencies:
   ```bash
   npm install
   ```
3. Run the Vite development server:
   ```bash
   npm run dev
   ```
