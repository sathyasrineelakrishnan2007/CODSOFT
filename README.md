print("Welcome to AI Chatbot")
print("Type 'exit' to stop")

while True:

    message = input("You: ")

    # Greeting
    if "hello" in message or "hi" in message:
        print("Bot: Hi! Nice to meet you.")

    # Asking about chatbot
    elif "name" in message:
        print("Bot: I am AI Chatbot.")

    # Asking time
    elif "time" in message:
        print("Bot: Sorry, I cannot show real time now.")

    # Bye message
    elif "bye" in message or "exit" in message:
        print("Bot: Goodbye!")
        break

    # Default response
    else:
        print("Bot: Please ask another question.")
