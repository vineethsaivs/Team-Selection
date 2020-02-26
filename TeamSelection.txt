from random import choice
players =  ['messi', 'cristiano', 'neymar', 'aguero', 'dybala', 'kante','coutinho', 'iniesta','mats', 'virjil', 'umtiti','marcelo']
print (players)

teamA = []
teamB = []

while len(players)>0:
    playerA = choice(players)
    teamA.append(playerA)
    players.remove(playerA)
    
    if players == []:
        break

    playerB = choice(players)
    teamB.append(playerB)
    players.remove(playerB)
print('TeamA: ',teamA)
print('TeamB: ' ,teamB)
