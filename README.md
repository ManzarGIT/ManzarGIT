<<<<<<< HEAD
# GovIntel — Setup Guide (Windows)

## 1. Set up the backend

Open a terminal in the `govIntel/backend/` folder:

    python -m venv venv
    venv\Scripts\activate
    pip install -r requirements.txt

Paste your Anthropic API key into `.env`

Run the backend:

    uvicorn main:app --reload --port 8000

You should see: "Uvicorn running on http://127.0.0.1:8000"

## 2. Set up the frontend

Open a SECOND terminal in `govIntel/frontend/`:

    npm install
    npm run dev

You should see: "ready on http://localhost:3000"

## 3. Open the app

Go to http://localhost:3000 in your browser.
Upload a PDF or Excel file → click Analyze → see the dashboard!
=======
# Doc_To_Insight
AI-powered document intelligence platform that transforms PDFs, Excel files, JSON data, and reports into interactive dashboards, visual insights, and actionable analytics within seconds.  
>>>>>>> 1c505e3e4e62d3a8fd38752b908dea668e446925
