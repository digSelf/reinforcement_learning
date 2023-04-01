# reinforcement_learning
## 01. Monte-Carlo

Objective: Write code to teach an agent to play Balck-jack.



Monte Carlo prediction is initially implemented to estimate the action-value function for a policy. 

There are three components in each state:

* the player's current sum - `state[0]`
* the dealer's face up card - `state[1]`
* whether or not the player has a usable ace - `state[3]`
  * 0 = no
  * 1 = yes

