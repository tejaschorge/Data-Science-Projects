# 🤖 End to End Chatbot 

This project presents a fully functional, end-to-end chatbot built using Python, Natural Language Processing (NLP), and Machine Learning. The chatbot is capable of handling multiple user queries and delivering appropriate responses based on predefined intents. It uses TF-IDF Vectorization to transform user input into numerical features and a Logistic Regression model to classify the input into the most probable intent. Once classified, it selects a random response associated with that intent to simulate human-like conversation.

The intent data is defined in a structured JSON-like format, where each tag includes multiple user input patterns and potential responses. The system is trained to recognize a variety of common conversational topics such as greetings, gratitude, farewells, help inquiries, credit score questions, weather queries, and more. The model is trained with high iteration count to ensure accurate intent prediction. The chatbot also demonstrates real-time interaction through a while loop that continuously accepts user input from the terminal.

**Key features include:**

  - Text classification using Logistic Regression

  - Feature extraction using TF-IDF Vectorizer

  - Context-free response selection using a tagged intent-response system

  - Handling multiple conversational flows such as greetings, help, weather, budgeting, credit score, and more

  - Capable of returning fallback responses when no intent matches (no_answer tag)

This project showcases fundamental NLP techniques, machine learning workflows, and serves as a solid foundation for building more advanced AI-powered conversational agents.
