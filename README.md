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

These are the rewards after 2000 episodes:

<img width="389" alt="Score_2" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/26145e52-317d-467e-b38b-7111232b107b">

