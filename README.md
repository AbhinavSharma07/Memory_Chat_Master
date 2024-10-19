# 🧠 Memory_Chat_Master

**Memory_Chat_Master** is an interactive AI-powered chatbot that can answer your questions by **retrieving relevant information from a PDF document**. Powered by **OpenAI's GPT models**, **LangChain**, and **ChromaDB**, this bot remembers your conversation and gives detailed, context-aware responses. 📄💬

---

## 🎯 Key Features
- **PDF-based Q&A:** Ask questions based on a PDF document.
- **Conversational Memory:** The bot remembers past interactions to maintain context.
- **Embeddings with ChromaDB:** Efficient information retrieval from document chunks.
- **OpenAI GPT Integration:** Uses `gpt-3.5-turbo` for conversation.
- **Real-time Interaction:** Keep chatting until you’re satisfied (or type `exit` to quit!).

---

## 🚀 How It Works
1. **PDF Input:** The bot loads a PDF and splits it into chunks.
2. **Embedding Creation:** Text chunks are converted into numerical vectors.
3. **Memory-Powered Chat:** As you chat, the bot retrieves relevant content and maintains conversation history.
4. **Ask Anything:** Keep chatting—every response is tailored based on both your query and prior interactions!


 ''' text
 pip install langchain openai pypdf tiktoken chromadb
 '''
