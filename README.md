# AI-chatbot
Project Description: AI Chatbot Using NLP
This project involves developing an AI chatbot that utilizes Natural Language Processing (NLP) techniques to interact with users through textual queries. The chatbot is designed to provide predefined responses to specific user inputs, making it simple yet effective for answering common questions.

Key Features:
Text Tokenization:

Breaks user input into individual words for analysis using NLTK’s word_tokenize method.
Stopword Removal:

Filters out common words like "is", "the", "and", etc., to focus on meaningful keywords.
Keyword Matching:

Matches user input keywords to predefined responses stored in a dictionary.
Default Response:

Provides a generic fallback response if the user query doesn’t match any predefined keywords.
Interactive Loop:

Allows continuous interaction with the chatbot until the user types "exit".

How It Works:
The chatbot processes user input by:
Converting it to lowercase.
Tokenizing the input into words.
Removing stopwords to focus on essential keywords.
It checks if any of the filtered keywords match the keys in the response dictionary.
If a match is found, the corresponding response is returned.
If no match is found, the chatbot provides a default response, asking the user to rephrase their query.

Technologies Used:
Python: The primary programming language for implementation.
NLTK (Natural Language Toolkit):
For tokenizing user input and removing stopwords.
Terminal or Console: For interactive communication.

Example Use Case:
User Query: "Hello, how are you?"
Bot Response: "Hi there! How can I help you?"
User Query: "What is your name?"
Bot Response: "I am your friendly chatbot created using NLTK!"
User Query: "Tell me the weather."
Bot Response: "I'm sorry, I can't give weather updates right now."
User Query: "Goodbye."
Bot Response: "Goodbye! Have a nice day!"

Applications:
Customer support for basic inquiries.
Educational tools for learning about NLP.
Entertainment or hobby projects.

Advantages:
Lightweight and Simple: Easy to implement and extend.
Customizable: New responses and features can be added to improve functionality.
Interactive: Provides real-time responses to user inputs.
