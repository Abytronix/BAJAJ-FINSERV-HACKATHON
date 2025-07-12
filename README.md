# 🤖 Bajaj Finserv AI Chatbot

A powerful AI chatbot designed to analyze **Bajaj Finserv’s stock price data** and **earnings call transcripts** to answer financial performance, strategic decisions, and digital marketing insights.

Built with Python and leveraging state-of-the-art AI models, this chatbot provides interactive financial analysis and business insights.

---

## 📊 Features

✅ **Stock Price Analysis**
- Get **highest**, **lowest**, or **average** stock prices for any period.
- Compare BFS performance across two different time periods.  
- Interactive charts with SMA (20/50/200), volatility, and RSI.

✅ **Earnings Call Transcript Insights**
- Search through quarterly PDFs to extract context on:
  - **Organic traffic & Bajaj Markets**
  - **Hero Partnership**
  - **BAGIC Motor Insurance headwinds**
  - **Allianz stake sale discussions**
- Context-aware answers from company transcripts.

✅ **CFO Commentary Generator**
- Draft ready-to-use CFO commentary for investor calls.

✅ **Modern Web Interface**
- Simple and interactive **Gradio UI** with tabs for:
  - Chatbot
  - Interactive Stock Chart

---

## 🛠️ Tech Stack

- **Language:** Python 3.13
- **AI Models:** Transformers (`phi-2`, CPU-friendly)
- **Libraries:**
  - `pandas`, `numpy`, `PyPDF2`, `matplotlib`, `plotly`
  - `gradio` for UI
- **Frontend:** Gradio (compatible with HuggingFace Spaces)

---

## 🚀 Setup & Run Locally

### 📥 Clone the Repository
```bash
git clone https://github.com/yourusername/bajaj-finserv-chatbot.git
cd bajaj-finserv-chatbot

