
## Learning Algorithm
I have two DDPG agents, I changed the replay buffer to be shared across agents, I also changed the OUNoise for the one in the MADDPG code. I increased OUNoise's parameters to explore more. I removed grad normalizer to add density to the rewards.

## Plot of Rewards:
<img width="385" alt="Score_6" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/7bb98e9b-7760-4cec-bedf-3f5593e726f4">

## Ideas for Future Work
I could try adding PER (Prioritized Experience Replay) to make less frequent but important transitions more repeatable and learn from them.
