# Rule-Based-AI-Chatbot
Overview:
DecodeLabs Logic Engine is a simple, rule-based chatbot built in Python. It demonstrates core programming concepts like control flow, string preprocessing, and dictionary-based lookups to simulate conversational responses — without relying on any external AI/ML libraries.

🎯 Purpose:
This project is designed as a learning exercise to show how a chatbot's "logic core" works before adding real AI/LLM capabilities. It highlights the difference between a deterministic rule-based system and a probabilistic AI model.

🧠 How It Works:
Input Preprocessing – User input is lowercased, stripped of punctuation, and trimmed using _preprocess_input().
Response Lookup – The cleaned input is matched against a dictionary of predefined keyword-response pairs.
Fallback Handling – If no match is found, a default "not programmed for that" response is returned.
Interactive Loop – The run() method starts a console-based chat loop that continues until the user types exit.

 Tech Stack:
Language: Python 3
Libraries Used: string, sys (standard library only — no external dependencies)

Features:
Lightweight, dependency-free chatbot engine
Clean input preprocessing (case-insensitive, punctuation-stripped)
Easily extendable response dictionary
Graceful handling of unexpected session termination (EOF)
Simple CLI-based interaction loop

Future Improvements:
Expand the response dictionary with more topics
Add fuzzy matching for input that doesn't exactly match a keyword
Integrate a real LLM backend with guardrails for open-ended questions
Add unit tests for _preprocess_input() and get_response()


![image alt](https://github.com/R56053/Rule-Based-AI-Chatbot/blob/25ec3d7bc40d3847e760469fb467f564ec3947ca/chatbot.png)
