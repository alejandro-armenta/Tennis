
## Learning Algorithm
I have two DDPG agents, I changed the replay buffer to be shared across agents, I also changed the OUNoise for the one in the MADDPG code. I also added Noise decay, that really helped me with the results.

## Plot of Rewards:

<img width="391" alt="Score_4" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/c012bbdb-45b8-4a06-8bff-7f3f74f80ae3">

## Ideas for Future Work
I could try adding PER (Prioritized Experience Replay) to make less frequent but important transitions more repeatable and learn from them.
