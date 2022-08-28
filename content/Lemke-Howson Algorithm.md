---
title: "Lemke-Howson Algorithm"
alias: Lemke-Howson
---
> [!SUMMARY]+
> A particular algorithm that computes a [[Nash equilibrium]] for a [[Games#Normal form|Normal form game]] 

$$

\begin{aligned}

\sum_{k \in A_2} u_1 \left( a^j_1, a^k_2 \right) \cdot s^k_2 + r^j_1 &= U^*_1 & \forall j &\in A_1\\

\sum_{j \in A_1} u_1 \left( a^j_1, a^k_2 \right) \cdot s^k_2 + r^j_1 &= U^*_1 & \forall k &\in A_2 \\

\sum_{j \in A_1} s^j_1 = 1, \sum_{k \in A^2} s^k_2 &= 1 \\

s^j_1 \geq 0, s^k_2 &\geq 0 & \forall j \in A_1, \forall k &\in A_2\\

r^j_1 \geq 0, r^k_2 &\geq 0 & \forall j \in A_1, \forall k &\in A_2\\

r^j_1 \cdot s^j_1 = 0, r^j_2 \cdot s^j_2 &= 0 & \forall j \in A_1, \forall k &\in A_2

\end{aligned}

$$
- $s$ is the probability of a player taking a particular action
	- $s^j_1$ is the probability player 1 plays action $j$
- $r$ is the amount of [[Utility]] that the player is not gaining from a particular strategy
	- $r^j_1$ is the amount of [[utility]] player 1 is missing from their maximum by playing strategy $j$
- $U^*$ is the maximum [[utility]] that can be gained by a player

---
- Index:: [[_Game Theory]]
- Related:: [[Nash equilibrium]]
---