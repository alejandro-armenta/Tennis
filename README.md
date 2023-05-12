# Tennis
These are two DDPGS learning to play tennis collaborately. They have to bounce a ball over the net.

## Reward System:
If an agent hits the ball over the net, it receives a reward of +0.1
If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.

## Observation Space:

There are 24 variables in the state space corresponfing to position and velocity of the ball and racket. Each agent receives its own local observation. 

## Action Space:

Two continuous actions, corresponding to movement toward or away from the net and jumping.



This is the reward after 2000 episodes:

<img width="401" alt="Score_1" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/f271164b-5a3f-4f4e-addb-6e84eaad7697">
