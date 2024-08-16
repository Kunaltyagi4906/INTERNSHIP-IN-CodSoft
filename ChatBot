#code 

import datetime


def jls_extract_def():
    return "ohh! its a famous  street food in maharashtra."


def AI_CHATBOT(user_input):
   

    user_input = user_input.lower()

    

    if any(greeting in user_input for greeting in ["hello", "hi", "hey"]):

        return "Hello! How can I assist you today?"
    
    
    elif "pao bhazi" in user_input:
    
         return "its a famous street food in maharasthra."
        
        

   

    elif "weather" in user_input:

        return "I'm sorry, I don't have access to real-time weather information."

   
    elif "time" in user_input:

        current_time = datetime.datetime.now().strftime("%H:%M:%S")

        return f"The current time is: {current_time}."



    elif any(emotion in user_input for emotion in ["sad", "happy"]):

        return "I'm here to chat and support you."
    

    elif "bored" in user_input:

        return"ohh! do your favourite work."

    

    elif any(farewell in user_input for farewell in ["bye", "goodbye", "see you"]):

        return "Goodbye! Feel free to come back anytime."
    else:

        return "I'm not sure how to respond to that. Please ask me something else."



while True:

    user_input = input("You: ")

    if user_input.lower() == "exit":

        print("AIBOT: Goodbye!")

        break


    response =AI_CHATBOT(user_input)

    print("AIBOT:", response)
