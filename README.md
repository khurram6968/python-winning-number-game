# python-winning-number-game
#python winning number game
import random
GuessNumber=int(input("enter your number between 0 to 5:"))
WinningNumber=(random.randint(0,5))#genrating random numbers use random.randint()
if WinningNumber==GuessNumber:
    print("Winner")
else:
    print("Loser")
    pass
print(f"WinningNumber:{WinningNumber}")
