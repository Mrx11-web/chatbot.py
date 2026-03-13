import random

responses = {
    "hello": ["Hi!", "Hello!", "Hey there!"],
    "how are you": ["I am fine!", "Doing great!", "All good!"],
    "your name": ["I am a simple AI chatbot."],
    "bye": ["Goodbye!", "See you later!"]
}

print("AI Chatbot: Hello! Type 'bye' to exit.")

while True:
    user_input = input("You: ").lower()

    if user_input == "bye":
        print("AI Chatbot: Goodbye!")
        break

    found = False
    for key in responses:
        if key in user_input:
            print("AI Chatbot:", random.choice(responses[key]))
            found = True
            break

    if not found:
        print("AI Chatbot: I don't understand that yet.")
