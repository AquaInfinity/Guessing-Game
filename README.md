# Guessing-Game
#A very simple guess-the-number game. My first thing I have ever made :D

name = input("What is your name? ")
 my_number = 0

while(my_number != 5):

    my_number = input("Hello "+name+"! "+"Pick a number between 1 and 20! ")
     my_number = int(my_number)

    if(my_number < 1):
        print("This number is too small! ")

    if(my_number > 20):
        print("This number is too large! ")

    if(my_number >= 1 and my_number <= 20 and my_number != 5):
        print("Keep on trying!")

    if(my_number == 5):
        print("YOU WON!")
