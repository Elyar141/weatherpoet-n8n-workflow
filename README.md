# 🌦 WeatherPoet — An AI Agent for Weather-Inspired Poetry

This is an n8n workflow that sends poetic quotes based on the weather in Berlin.

Every morning at 9 am, the agent:
- Checks the current weather (via WeatherAPI)
- Uses OpenAI to fetch a real poetic quote based on sun or rain
- Sends the quote to a Telegram chat automatically

### 🛠 How to Use
1. Import this `.json` into your n8n instance
2. Replace `YOUR_API_KEY`, `YOUR_TELEGRAM_CREDENTIALS`, and `YOUR_OPENAI_CREDENTIALS`
3. Activate the workflow
---

### ✨ Built by [@azadielshan](https://www.linkedin.com/in/azadielshan)  
Let me know if you try it!
