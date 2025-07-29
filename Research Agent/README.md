# 🧠 Research Assistant Agent

**Goal**: Automatically performs research on any topic and delivers a summarized answer directly to Telegram. The agent gathers live content from Wikipedia and Hacker News, then uses OpenAI to summarize the findings.

---

## 🔧 Tools Used
- OpenAI Chat Model
- Wikipedia API
- Hacker News API
- Telegram Bot (for final delivery only)

---

## 📌 Key Features
- Gathers live information from trusted public sources  
- Uses OpenAI to generate insightful summaries  
- Sends the final results to users via Telegram  

---

## ⚙️ How It Works
1. A backend trigger (e.g., schedule, keyword, or prompt) starts the process  
2. The agent fetches information from:
   - **Wikipedia** (for factual grounding)  
   - **Hacker News** (for recent discussions or opinions)  
3. All collected content is passed to OpenAI for a concise, context-rich summary  
4. The Telegram bot sends this final response to the user  

---

## 📎 How to Use
1. Import the `.json` into your n8n workspace  
2. Configure your API keys:
   - OpenAI  
   - Telegram Bot  
3. Trigger the agent (manually or through a connected source)  
4. Get the summarized research in your Telegram inbox  

---

## 📸 Optional Improvements
- Add a keyword filtering step for better accuracy  
- Store summaries in Notion or Google Sheets  
- Include source links in the Telegram message  
