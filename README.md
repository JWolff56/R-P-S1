# R-P-S1
Quick Game of Roshambo Python 3.6.1

import random

userHand = input("Rock, Paper, Scissors:")
computerHand = random.random()

if computerHand <= .33:
    computerHand = "Rock"
elif computerHand <= .66:
    computerHand = "Paper"
else:
    computerHand = "Scissors"

def game(first,second):
    if first == second:
        print "You chose", first
        print "Computer chose", second
        print "It is a tie."
    elif first == "Rock":
        if second == "Scissors":
            print "You chose", first
            print "Computer chose", second
            print "You WIN!!"
        else:
            print "You chose", first
            print "Computer chose", second
            print "You Lose!!"
    elif first == "Paper":
        if second == "Rock":
            print "You chose", first
            print "Computer chose", second
            print "You WIN!!"
        else:
            print "You chose", first
            print "Computer chose", second
            print "You Lose!!"
    elif first == "Scissors":
        if second == "Paper":
            print "You chose", first
            print "Computer chose", second
            print "You WIN!!"
        else:
            print "You chose", first
            print "Computer chose", second
            print "You Lose!!"

game(userHand,computerHand)
Rock, Paper, Scissors: Rock

