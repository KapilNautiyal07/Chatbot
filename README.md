<img width="1919" height="872" alt="Screenshot 2025-10-29 005826" src="https://github.com/user-attachments/assets/15fe8a4c-fc37-4a2a-b8f0-eab160e0f372" />
🧠 AI Chatbot using LangGraph & LangChain

This project is a multi-tool conversational AI chatbot built using LangGraph and LangChain, capable of performing web searches, fetching stock data, and handling basic arithmetic operations — all in a single interactive workflow.

🚀 Features

🦆 DuckDuckGo Search Integration
Perform real-time web searches and return summarized answers using DuckDuckGo API.

📈 Stock Market Data
Fetch live or recent stock information for any ticker symbol (e.g., AAPL, TSLA).

➕ Arithmetic Calculator
Perform basic math operations such as addition, subtraction, multiplication, and division.

🔁 Modular Tool Integration
Each tool (Search, Stock, Calculator) is connected via LangGraph nodes and managed through LangChain’s Tool abstraction layer.

🧩 Customizable Workflow
Built using LangGraph’s flow-based design, allowing easy extension with additional tools (e.g., Email, Weather, etc.).

🛠️ Tech Stack
Component          	Description
LangGraph	          For defining and executing the chatbot’s tool-based workflow.
LangChain	          For LLM orchestration and tool management.
DuckDuckGo          Search Tool	Provides real-time web search capabilities.
Stock Tool        	Retrieves stock prices using APIs like Yahoo Finance or Alpha Vantage.
Calculator Tool    	Handles user arithmetic queries directly.
OpenAI API        	Backend LLM used to interpret user intent.



