---
tags:
  - research
  - mathematics
  - sem6
---
## [[Research Methodology 3]]
The aim is to model enjoyability of a **particular** game using one of the two main ideologies: Agent-Based modelling or Utility Theory. 

The game of choice is either Tic-Tac-Toe or Settlers of Catan (or the game I just purchased and am waiting to play-out). The choice will depend on whether I can handle the complexity of a more fleshed-out game like Settlers of Catan or the One that I just purchased)  

---

The prerequisite process would consist of: 
Familiarising myself with the rules of the game
Setting up questionnaires based on the Intrinsic Motivation Inventory guidelines
Creating a sampling frame of people to ask (Could be solely avid tabletop players, or a mixed bag)
Questioning them and based on findings, perform correlation analysis between a net-enjoyment of the game and certain factors. 

Then we proceed one of two ways, or both? Then Compare the findings?

The process for agent-based modelling would consist of:
1. Identifying Key Factors Affecting Enjoyment - Literature Review/Survey questionnaires
	Using Mixed-Method research techniques in order to quantify the coefficients and weights for the agents. 
		Player agent (Simulates the player behaviour) - Resource Agent (Production and collection) - Robber Agent (Blocking Production) - Game Board Agent (Facilitates the movement) 

2. Developing Agent-Enjoyment Functions: Define mathematical functions based on the factors affecting enjoyment in response to specific events, outcomes, etc.
	
3. Simulating Scenarios instead of whole play-through for longer games: Specific Risk-Reward Scenarios/Winning-Losing Sequences
	Observations: Have to conduct several simulations in order to assess the agent behaviour in this context. Explore the effects

4. Calibrate and Validate the Model: Optimise the enjoyment functions assigned to the agents, based upon findings from simulations
	The validity of the model at the end can also be checked alongside actual samples of people playing amongst each other based on the agent-functions assigned to the simulated players

---

The other approach we can take is Utility Theory, while I have not explored Utility Theory as much but here's what I have found so far:

We identify outcomes, experiences and collect information about all possible states that have an effect on enjoyment
	Construction of utility functions based on outcomes and experiences and associate them with numerical utility coefficients (based on our findings from literature reviews and surveys)surveys

From there, We can compute Expected Utility based on decisions and game state. We can also then explore avenues which allow for maximisation of utility for a certain person. This would also allow us to better understand the trade-offs in enjoyment based on game mechanics.

# Comments:
Define Clearly what kind of terminology used based on the game, be as specific as possible (Like State of the game, depends on game to game)

Player Enjoyability (Subjective - Actual Playing) vs Game Enjoyability (Objectivity - Mechanics)
3 - Act Structure

Look at Tic-Tac-Toe as a Case Study to establish the proposal
	Pilot the idea, look at the game and the player both

Gradual Transition from Deterministic to Stochastic 

Tic-Tac-Toe (Bias due to chance is very low -  Calculate Pay-Off in the Game - Show the Maths for the same)
	1. Positive Pay-Off: 
	2. Negative Pay-Off: 

Looking at Probability of occupation || Setting up a Pay-Off Points Table ||  

https://informatika.stei.itb.ac.id/~rinaldi.munir/Matdis/2021-2022/Makalah2021/Makalah-Matdis-2021%20(148).pdf

1. Win: Complete a three-in-a-row.
2. Block: Block the opponent from a three-in-a-row.
3. Fork: Create two possible three-in-a-rows.
4. Block Fork: Block opponent from making a fork.
5. Center: Play center if blank
6. Opposite Corner: Play the opposite corner of opponent.
7. Corner: Play corner if blank
8. Side: Play side if blank

In game theory, a game like tic-tac-toe that always results in a draw is called a futile game. Permits a draw or Tie

Minimum Turns required to complete a game would be 5 - With 3 X's and 2 O's
Using Combinatorics and the Sum Rule on Configurations possible under 5 to 9  turns (That tells us the number of winning Configurations)

If we only calculate the possibilities for the first player to win We can only measure Turns - 5, 7, 9
![[Pasted image 20240223101238.png]]

Board Game Convention in Mumbai - Surveying 
