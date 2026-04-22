# AI Backend (Gemini)

## Quick Setup (Railway)

1. Upload this folder to Railway (or GitHub → Railway)
2. In Railway → Variables, set:
   GEMINI_API_KEY = your actual API key
3. Click Deploy
4. Copy your Railway URL

## Test
POST /generate
Body:
{
  "prompt": "Hello"
}

## Notes
- Do NOT expose your API key in your frontend
- Replace baseUrl in your Flutter app with your Railway URL
