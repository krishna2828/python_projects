

[college chatbot.py](https://github.com/user-attachments/files/33833988/college.chatbot.py)
# python_projects
The College FAQ Chatbot is a simple Python-based chatbot developed as part of my Artificial Intelligence internship at CodeAlpha. It answers frequently asked questions about college by matching user queries with predefined questions and answers.
The chatbot uses Python’s built-in difflib library to find similar questions and provide appropriate responses. This project helped me understand the basics of chatbot development, text similarity matching, and Python programming.
🎯 Features
• 💬 Answers frequently asked college-related questions.
• 🔍 Matches user questions with predefined FAQs using text similarity.
• 🐍 Developed using Python.
• 🔡 Converts user input to lowercase and removes extra spaces.
• ⚡ Provides instant responses.
• 🚪 Allows users to exit the chatbot by typing exit.
• ❓ Displays a fallback message when no suitable answer is found.
🛠️ Technologies Used
• Programming Language: Python
• Library: difflib
• Concepts: Dictionaries, loops, conditional statements, user input, and string handling.
⚙️ How It Works
1. The chatbot stores predefined questions and answers in a Python dictionary.
2. The user enters a question.
3. The chatbot compares the input with stored questions using difflib.get_close_matches().
4. If a matching question is found, the chatbot displays its corresponding answer.
5. If no suitable match is found, it displays a message saying it does not know the answer.
6. The chatbot continues until the user types exit.
💻 Installation and Setup
Prerequisites
• Python 3 installed on your computer.
• A code editor such as Visual Studio Code.
