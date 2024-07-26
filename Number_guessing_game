import random
import math
lowernumber=int(input("enter the lower range number"))
uppernumber=int(input("enter the upper range number"))
randomnumber=random.randint(lowernumber,uppernumber)
totalchances = math.ceil(math.log(uppernumber - lowernumber + 1, 2))
print("\nYou've only ", totalchances, " chances to guess the integer!")
countchances = 0
flag = False
while countchances < totalchances:
    countchances += 1
    guessnumber = int(input("Guess a number:-"))
     if randomnumber == guessnumber:
        print("Congratulations you did it in ",countchances)
        flag = True
        break
     elif randomnumber > guessnumber:
        print("You guessed too small")
     elif randomnumber < guessnumber:
        print("You Guessed too high")

if not flag:
    print("\nThe number is ",randomnumber)
    

