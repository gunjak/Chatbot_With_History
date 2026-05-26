# LangChain Conversational Chatbot with Memory

- A conversational AI chatbot built using Streamlit, LangChain, and LangGraph that supports persistent chat memory and real-time streaming responses.

- This application demonstrates how to create an intelligent assistant powered by modern LLM frameworks while maintaining conversational context across interactions.

## Features
  - Interactive chatbot UI using Streamlit
  - Persistent conversation memory with LangGraph MemorySaver
  - Context-aware conversations using LangChain message history
  - Message trimming to optimize token usage
  - Streaming AI responses in real time

## Tech Stack
  - Python
  - Streamlit
  - LangChain
  - LangGraph
  - Groq API
  - dotenv

## 📦 Installation

Clone the repository:

```bash
git clone <https://github.com/gunjak/Chatbot_With_History/>
cd <Chatbot_With_History>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
```

Run the application:

```bash
streamlit run app.py
```

---

## Project Structure

```bash
├── app.py
├── requirements.txt
├── .env
└── README.md

