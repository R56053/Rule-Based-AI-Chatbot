# Rule-Based-AI-Chatbot
Overview
The Rule-Based AI Chatbot is a deterministic, lightweight conversational framework built using Python. Unlike complex probabilistic models, this engine operates on predefined logic and pattern-matching rules, ensuring predictable, consistent, and safe responses for specific technical interactions. This project was developed by Rahul Kumar to demonstrate efficient control flow and logic implementation.

Key Features
Deterministic Logic: Provides exact, reliable responses based on user input, making it ideal for support scenarios where accuracy is paramount.

Python-Powered: Built with clean, modular Python code, utilizing object-oriented principles for maintainability.

Robust Input Normalization: Includes a cleaning pipeline that removes punctuation and normalizes casing to ensure accurate pattern matching regardless of user formatting.

Safe Interaction: Eliminates the risk of "hallucinations" by restricting the bot's output exclusively to approved, hardcoded knowledge.

Low Latency: Optimized for rapid execution, providing near-instant responses.

Technical Approach
The engine utilizes a dictionary-based mapping system to link normalized user intents to predefined responses. By decoupling the input cleaning logic from the response retrieval mechanism, the system is both easy to maintain and straightforward to audit.

Developer
Developed by: Rahul Kumar

Getting Started
To integrate this engine, initialize the ChatbotEngine class and invoke the run() method. Responses can be easily modified or extended by updating the internal response dictionary.

Built with passion by Rahul Kumar.
![image alt] (https://github.com/R56053/Rule-Based-AI-Chatbot/blob/02e5e136330acb4042520846294b706bf4b553df/chatbot.png)
