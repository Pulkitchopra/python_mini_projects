import random
def game(comp,player):
    if comp==player:
        return None
    elif comp=='r':
        if player=='p':
            return True
        if player=='s':
            return False

    elif comp=='p':
        if player=='s':
            return True
        if player=='r':
            return False

    elif comp=='s':
        if player=='r':
            return True
        if player=='p':
            return False

print("ROCK PAPER AND SCISSORS GAME")
print("Comp turn: Rock(r),Paper(p) and Scissor(s) ")
randno=random.randint(1,3)
if randno==1:
    comp='r'
elif randno==2:
    comp='p'
elif randno==3:
    comp='s'
player=input("Player's turn- What do you want to choose Rock(r),Paper(p) and Scissor(s) : ")

x=game(comp,player)

print(f"Comp chose {comp}")
print(f"Player chose {player}")
if x==None:
    print("There is a tie")
elif x:
    print("Player wins")
else:
    print("Computer wins")
