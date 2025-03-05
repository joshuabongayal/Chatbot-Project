import nltk
from nltk.chat.util import Chat, reflections

# Define chatbot responses
pairs = [
    ["hi|hello|hey", ["Hello!", "Hey there!", "Hi, how can I help you?"]],
    ["how are you?", ["I'm just a bot, but I'm doing well!", "I'm fine, thank you!"]],
    ["what is your name?", ["I'm a chatbot!", "You can call me ChatBot."]],
    ["bye|goodbye", ["Goodbye!", "See you later!", "Bye, take care!"]],
]

# Create chatbot
chatbot = Chat(pairs, reflections)

# Start conversation
print("🤖 Simple Chatbot (type 'quit' to exit)")
chatbot.converse()
