# rock-paper-scissors
from random import randint
from time import sleep
player = input('rock(r) ,paper(p) or scissor(s) ?')
print (player,'vs',end = ' ')
sleep(1)
computer= randint(1,3)
if computer == 1:
    choosen = 'r'
elif computer == 2:
    choosen = 'p'
else:
    choosen = 's'
print (choosen)
if player == choosen :
    sleep(1)
    print('draw!')
elif player == 'r' and choosen =='s':
    sleep(1)
    print('player wins')
elif player == 's' and choosen =='r':
    sleep(1)
    print('computer wins')
elif player == 'r' and choosen == 'p':
    sleep(1)
    print('player looses')
elif player =='p' and choosen =='r':
    sleep(1)
    print('player wins')
elif player == 's' and choosen == 'p':
     sleep(1)
     print('player wins')
else:
    sleep(1)
    print('player looses')
