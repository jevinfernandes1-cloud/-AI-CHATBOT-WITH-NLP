# AI-CHATBOT-WITH-NLP

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: JEVIN PAWAN FERNANDES

*INTERN ID*: CT04DZ1493

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

**Project Description

For this project, I wanted to explore the world of chatbots and see how we can build one using Natural Language Processing (NLP). Chatbots are everywhere today — from customer support on websites to personal assistants like Siri or Alexa. The idea behind my project was to build a simple AI chatbot that can understand user queries in text form and reply with meaningful answers.

What I Used

I developed the chatbot in Python, using Visual Studio Code (VS Code) as my coding environment. For the NLP part, I chose the NLTK (Natural Language Toolkit) library because it provides useful tools for tokenization, lemmatization, and preprocessing text.

The main tools and libraries I used were:

Python 3.x – the programming language.

NLTK – for tokenizing sentences and cleaning up text.

Random module – to make responses less repetitive.

VS Code – for development and testing.

How It Works

The chatbot works in a few simple steps:

User Input
The chatbot waits for the user to type something, like “hello” or “what’s your name?”.

Preprocessing with NLP
The input is converted to lowercase, tokenized into words, and cleaned up. For example, “How are you?” becomes [‘how’, ‘are’, ‘you’]. Using lemmatization, words like running or ran get reduced to their base form (run). This helps the chatbot understand different variations of the same query.

Matching Queries
I created a small dictionary of common queries like:

“hello” → ["Hi there!", "Hello!", "Hey! How can I help you?"]

“how are you” → ["I'm doing great, thanks for asking!", "All good here, what about you?"]

“name” → ["I'm an AI chatbot created with NLTK.", "You can call me ChatBuddy!"]

The script checks if any of the tokens from the user input match a keyword in the dictionary.

Generating a Response
If a match is found, the chatbot picks a random response from the list (so it doesn’t always reply with the exact same sentence). If no match is found, the chatbot replies with something like: “I’m not sure how to respond to that. Could you rephrase?”

Chat Loop
This continues until the user types “bye”, at which point the chatbot ends the conversation.

Why This is Useful

This project is a simple version of what real-world chatbots do. While mine is rule-based, it shows the foundation of:

NLP preprocessing (cleaning and understanding text).

Pattern matching (detecting keywords in queries).

Generating replies (producing human-like answers).

Such chatbots are widely used in:

Customer Support – answering FAQs.

Education – providing quick information to students.

Personal Assistance – like digital helpers for tasks.

My Experience

I really enjoyed this project because it felt interactive. Unlike other programs where you just see numbers or graphs, here I could actually chat with my code. At first, I struggled a bit with cleaning the user input and making sure the chatbot could handle variations of the same question. But once I used lemmatization and tokenization from NLTK, it became more reliable.

Testing it in VS Code was fun too — I typed in different things like “hello”, “what’s your name?”, and “weather” and got nice responses back. Even though it’s not as advanced as Siri or Alexa, it felt cool to build a chatbot from scratch.

Conclusion

In summary, this project is about creating a basic AI chatbot using NLP. It can understand simple text queries, process them with NLTK, and respond with appropriate answers. While it’s rule-based and limited to the responses I defined, it lays the foundation for more advanced chatbots that could use machine learning or deep learning for smarter responses.

The project gave me a clear idea of how chatbots actually work behind the scenes, and it motivated me to learn more about building intelligent conversational systems. In the future, I’d like to extend this by integrating it with an FAQ dataset, or even making it voice-enabled.**

#OUTPUT

<img width="788" height="317" alt="Output task3" src="https://github.com/user-attachments/assets/00c3c76b-b7a2-41c7-8363-052482b3901d" />
