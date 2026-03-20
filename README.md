# Trade API 🚀

## 📌 Overview
This project is a FastAPI-based backend that analyzes market data and provides trade opportunities for different sectors.

## ⚙️ Features
- Sector-based analysis
- AI-powered insights (Gemini API)
- Markdown report generation (.md file)
- Rate limiting & security
- Clean architecture

## 🔗 Endpoint
GET /analyze/{sector}

Example:
GET /analyze/pharmaceuticals
GET /analyze/technology

## 📂 Output
After running the API, the analysis is stored as a Markdown file.

Example:
technology_analysis.md

## 📝 Markdown File
The generated file includes:
- Key trends
- Market sentiment
- Trade opportunities
- Risk factors

## 🛠️ Tech Stack
- FastAPI
- Gemini API
- Python

## ▶️ Run Locally
```bash
pip install -r requirements.txt
uvicorn server:app --reload
