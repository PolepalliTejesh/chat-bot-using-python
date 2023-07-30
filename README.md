# chat-bot-using-python
Chat Bot Using Python

This code is a simple chatbot implementation that responds to user input based on predefined patterns. Here's an explanation of the code:

The code defines a function message_probability that calculates the certainty of the recognized words in the user's input message.

The check_all_messages function uses the message_probability function to check the user's input against a list of recognized words and their corresponding responses. It selects the best matching response based on the highest probability of recognized words.

The chatbot responses are defined as function calls in the check_all_messages function. The bot responds to greetings, goodbyes, inquiries about how it's doing, and expressions of gratitude. There are also longer responses for giving advice and asking about what the bot eats.

The get_response function takes user input, processes it into lowercase words, and then calls the check_all_messages function to find the appropriate
