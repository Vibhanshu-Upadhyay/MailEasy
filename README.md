# 📬 MailEasy – AI Email Assistant

MailEasy is an AI-powered Gmail assistant that:
- Fetches emails from the last 12 hours
- Classifies intent (ignore / read / action required)
- Summarizes emails
- Generates draft replies using LLaMA 3.1 (4-bit quantized)
- Runs fully on Google Colab
- Exposes a UI using Streamlit + Cloudflare Tunnel

## 🧠 Tech Stack
- Google Colab
- LLaMA 3.1 8B (4-bit via Unsloth)
- Hugging Face Transformers
- Gmail API (OAuth)
- Streamlit UI
- Cloudflare Tunnel

## 🚀 How to Run
1. Open `MailEasy.ipynb` in Google Colab
2. Upload `credentials.json`
3. Run cells top-to-bottom
4. Authenticate Gmail
5. Open the Streamlit URL provided by Cloudflare

## 🔒 Security
- No emails stored
- OAuth tokens ignored by git
- Session-based execution

## 📐 Architecture
See `Architecture.png`
