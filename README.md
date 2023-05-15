# Tennis
These are two DDPGS learning to play tennis collaborately. They have to bounce a ball over the net.

## Reward System:
If an agent hits the ball over the net, it receives a reward of +0.1
If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.

## Observation Space:

There are 24 variables in the state space corresponfing to position and velocity of the ball and racket. Each agent receives its own local observation. 

## Action Space:

Two continuous actions, corresponding to movement toward or away from the net and jumping.

## Solution of the environment:
The environment is considered solved for an average score over 100 episodes of +0.5.
