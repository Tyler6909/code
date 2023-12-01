# python projects

welcome to my portfolio, this will look at the python projects that i have created this year;

## PIG GAME
Code from pig game;
```python
from random import *





p1 = input("player 1 enter in your name: ")
p2 = input("player 2 enter in your name: ")
randomgo = (randint(1,2))
if randomgo == 1:
    print(f"{p1} goes first")
else:
    print(f"{p2} goes first")


score = 0

choice = "Y"
while choice == "Y":

   
    roll = (randint(1,6))
    if roll == 1:
        score = 0
    else:
        score += roll
    print(roll)
    choice = input("do you want to keep rolling Y/N").upper() 
print(score)
#unfinished 
```
### output 

![outcome of saying N](images/outcomeN.png)
![outcome of saying Y](images/outcomeY.png)


[calculator program](calculator.md)