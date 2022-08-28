---
title: "Games" 
---
> [!SUMMARY]+
> 

Necessary components for a game:
- *Players*: who are the decision makers?
	- People
	- Governments
	- Companies
	- Employees, etc
- *Actions*: what can the players do?
	- Enter a bid in an auction?
	- Decide to end a strike?
	- Decide to sell a stock?
	- How to vote?
- *Payoffs*: what motivates the players?
	- Profits?
	- Other players?

There are two standard representations of a game:
1. **Normal form** (aka Matrix form, Strategic form) which lists the payoffs a player gets as a function of their actions
	- As if players moved simultaneously
	- Many possible strategies
2. **Extensive form** 
	- Players move sequentially, represented by a tree
		- Eg. chess where white player moves, then black player sees move and reacts
	- Keeps track of what each player knows when they make each decision
		- Eg. poker where each new card or bet affects the decision

### Normal form
- Finite, $n$-person game $\langle N,A,u \rangle$
- **Players**: $N = \{1, \dots, n\}$ is a finite set of $n$, indexed by $i$ (generic player)
- **Actions** for player $i$ $A_i$ 
	- Potential actions $i$ can take: $a = (a_1, \dots, a_n)$
	-  List of actions $i$ has taken = $A = A_1 \times \dots \times A_n$
	- $a = (a_1, \dots, a_n) \in A = A_1 \times \dots \times A_n$ 
- [[Utility function]] for $i: u_i: A \mapsto \mathbb{R}$ ($\mathbb{R}$ is the payoff for $i$)
	- $u = (u_1, \dots, u_n)$ is the list of [[Utility]] functions for all players

2 player games are represented as a matrix where player 1 is the "row player" and player 2 is the "column player". Hence the rows correspond to the actions $a_1 \in A_1$ and the columns correspond to $a_2 \in A_2$. The cells of the matrix show the payoff values for each player - the row player first and the column player second.


---
- Index:: [[_Game Theory]]
- Related:: 
---