
## Learning Algorithm
I have two DDPG agents, I changed the replay buffer to be shared across agents, I also changed the OUNoise for the one in the MADDPG code. I increased OUNoise's parameters to explore more.

## Plot of Rewards:

<img width="392" alt="Score_5" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/e1fbf8af-b971-453a-9db4-4e80eb6eb89a">

## Ideas for Future Work
I could try adding PER (Prioritized Experience Replay) to make less frequent but important transitions more repeatable and learn from them.
