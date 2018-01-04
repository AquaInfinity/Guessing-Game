# Guessing-Game
#A very simple guess-the-number game. My first thing I have ever made :D

#This controls what is your name.
name = input("What is your name? ")
#This should stay as 0, yet 5 is the number you have to guess. Don't question it :P
my_number = 0
#while(text here): is a loop which makes the game repeat if you guess wrongly.
while(my_number != 5):
    my_number = input("Hello "+name+"! "+"Pick a number between 1 and 20! ")
#This just makes the number you guess turn to a matematical form.
    my_number = int(my_number)

    if(my_number < 1):
        print("This number is too small! ")

    if(my_number > 20):
        print("This number is too large! ")

    if(my_number >= 1 and my_number <= 20 and my_number != 5):
        print("Keep on trying!")

    if(my_number == 5):
        print("YOU WON!")
        
#Rest is self explanatory.
