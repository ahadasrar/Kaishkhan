aichatbot.py 1
.

question1.py 1 ·
C: > Users > asus > OneDrive > Desktop > python > 2 aichatbot.py > ...

1

def simple_chatbot(user_input):

2

user_input = user_input. lower()
# Convert input to lowercase for easier matching

4

if "hello" in user_input or "hi" in user_input:

5

return "Hello there! How can I help you today?"

6

elif "how are you" in user_input:

7

return "I'm a bot, so I don't have feelings, but I'm functioning perfectly!"

8

elif "your name" in user_input:
return "I am a simple chatbot created in Python."

10

elif "bye" in user_input or "goodbye" in user_input:

11

return "Goodbye! Have a great day!"

12

else:
return "I'm sorry, I don't understand that. Can you rephrase?"

14

S

15

print("Chatbot: Hi! Type 'bye' to exit.")

16

while True:

17

user_message = input("You: ")

18

if user_message. lower() == "bye":

19

print("Chatbot: Goodbye!")

20

break

21

response = simple_chatbot (user_message)

22

print(f"Chatbot: {response}")
