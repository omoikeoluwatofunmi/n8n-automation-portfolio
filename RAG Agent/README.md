# 🤖 RAG Assistant – Gmail + Pinecone

This automation builds a Retrieval-Augmented Generation (RAG) pipeline using Gmail and Pinecone, allowing smart and context-aware responses based on previously received emails.

---

### 🎯 Goal
Automatically respond to Gmail messages using relevant context retrieved from historical email data stored in Pinecone.

---

### 🔧 Tools Used
- **n8n** – workflow automation platform  
- **Gmail API** – for reading/sending emails  
- **Pinecone** – vector database for similarity search  
- **Google Gemini** – for intelligent response generation  

---

### 🧠 How It Works
1. **Trigger:** New email received in Gmail  
2. **Embed:** Email is embedded using Google Gemini 
3. **Retrieve:** Pinecone fetches similar past emails  
4. **Generate:** GPT composes a context-rich reply  
5. **Respond:** Reply sent via Gmail

---

### 📌 Key Features
- Retrieval-Augmented pipeline with real-time embedding  
- Gmail integration for seamless inbox automation  
- Context-aware AI responses using vector memory  
- Modular and easily customizable

---

### 📎 How to Use
1. Import the `.json` into your n8n instance  
2. Set up credentials for Gmail, OpenAI, and Pinecone  
3. Adjust the prompt or retrieval logic as needed  
4. Activate and test with a sample email  

---

### 💡 Use Case Examples
- AI email assistants with memory  
- Smart support ticket responders  
- Contextual business communication automation  

---

