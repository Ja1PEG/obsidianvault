# [[Research Methodology 3]] Blackjack
**BlackJack** would be a sample for now:

Hit or Stand - Until Score comes to 21, if over 21 then bust, if score lower than the dealer then bust again.

1. Skill Floor: Simple Addition and Luck
    
2. Skill Ceiling: Card-Counting (Plays into the deterministic nature of the game), Doubling, Splitting, Surrendering as optional rules
    
3. No House Rules
    
4. 2-7 Players on the table, not including the dealer
    
5. Cost Per Play is nominal
    
6. Replayability is endless 
    
7. Round-Duration is very brief but the game is technically endless - quick games are possible
    
8. The sensation of regret and joy depends on the player’s results
    

  

How these metrics add on to each other:

$$Enjoyability(X)= a_{1}*x_{1}+a_{2}*x_{2}+\dots+a_{n}*x_{n}$$

Where $a_{n},x_{n}\in(0,10)$
For the case of blackjack:
$a_{1}=$ Skill-Floor = 0.3
$a_{2}=$ Skill-Ceiling = 0.05
$a_3=$ Cost-Per-Play = 0.15
$a_4=$ Duration of Game = 0.15
$a_5=$ Repeatability = 0.3

Finding out the average duration (in the terms of turns taken to take hits) of a round of blackjack
1. Factor in Doubling, Splitting and Surrendering
	1. Splitting the river allows for additional cards to be drawn at the risk of losing additional bets
	2. Doubling is making a bet equal to your initial wager after being dealt your first 2 cards
	3. Surrendering leads to half the bet being returned to you, rest being forfeit to the dealer
2. All Combinations can be 

2 2 2 2 3 3 3 A A A A- 11
10 J -2

Duration in terms of number of cards on the x-axis
Probability in the y-axis

(A,J) - (A,K) - (A, Q) * 2
(A, 2 ,8) * 6
(A, 3, 7) * 6
(A, 4, 6) * 6
(A, 5, 5) * 6
(A, 2, 7, A) * 4!/2!
(A, 3, 6, A) * 4!/2!
(A, 4, 5, A) * 2!
(A, 2, 2 , 6) * 4!/2!
(A, 2, 3, 5) * 4!/2!
(A, 2, 4, 4) * 4!/2!
(A, 3, 3, 4) * 4!/2!
(A, 3, 5, 2)

Probability Distribution - Only on the grounds of a Hit vs Probability 

