
## Learning Algorithm
I have two DDPG agents, I changed the replay buffer to be shared across agents, I also changed the OUNoise for the one in the MADDPG code. I also added Noise decay, that really helped me with the results.

## Plot of Rewards:

<img width="394" alt="Score_3" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/0a5f3015-e1bf-4d35-8d96-9f9cde8bd827">

## Ideas for Future Work
I could try adding PER (Prioritized Experience Replay) to make less frequent but important transitions more repeatable and learn from them.
