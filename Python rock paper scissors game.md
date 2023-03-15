# Python-Rock-Paper-Scissors-Game
A game that I made with python compiler, I have recently started coding in python so I am a complete beginner to it, Feel free to suggest any improvements such as ways to shorten or tidy up the code

import random
print("rock papers scissors?")
random_list = ["rock", "paper", "scissors"]
a = input()
random_value = random.choice(random_list)

if random_value == a:
    print(random_value + "\n" + "It's a draw, try again")
elif a == "scissors" and random_value == "paper":
    print(random_value + "\n" + "you win this time")
elif a == "scissors" and random_value == "rock":
    print(random_value + "\n" + "you lose this time")
elif a == "paper" and random_value == "scissors":
    print(random_value + "\n" + "you lose this time")
elif a == "paper" and random_value == "rock":
    print(random_value + "\n" + "you win this time")
elif a == "rock" and random_value == "paper":
    print(random_value + "\n" + "you lose this time")
elif a == "rock" and random_value == "scissors":
    print(random_value + "\n" + "you win this time")
elif a != "rock" or "paper" or "scissors":
    print("You have not entered a valid input") 
