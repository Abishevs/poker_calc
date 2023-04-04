# Poker Odds Calculator

## Calculate your hand odds against other players. 

Before using it you will need to pip install PhEvaluator:
```bash
pip install -r requirements.txt
```
For instructions run:
```bash 
py main.py 
```
or 
```
py main.py --help
```
You can easily give from 2-9 players.
if no -b argument is present then Pre-Flop odds are calculated.
Else if -b is 5 cards then it will simply give you who has the strongest hand (winner)
else if -b is between 3-4 cards then flop odds and respecetivly turn odds will be calculated.
After that you can either run arg mode version:
```bash
py main.py -p 8s9s -p ThQd -b 8h9sJh --fast
```
Or you could try interactive mode (with limitations- 2 players only and board cards are mandatory)
```bash
py main.py --interactive
```
