# Project
#Dice Simulator
from random import *

while True:
    print(randint(1,6));
    a=input("do you want to roll the dice again press [y] for yes and [n] for NO\n");
    if (a.lower()=="y"):
        continue;
    else:
        break;
