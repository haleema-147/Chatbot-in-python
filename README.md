# Chatbot-in-python
def basic_chatbot():
    print("Welcome to ChatBot! Type 'bye' to exit.")

    while True:
        user_input = input("You: ").lower()

        if user_input == "hello" or user_input == "hi":
            print("Bot: Hi!")
        elif user_input == "how are you" or user_input == "how r u":
            print("Bot: I'm fine, thanks!")
        elif user_input == "bye" or user_input == "exit":
            print("Bot: Goodbye!")
            break
        else:
            print("Bot: I didn't understand that.")


basic_chatbot()
