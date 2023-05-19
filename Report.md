
## Learning Algorithm
I have two critics, one replay buffer that is shared across agents and one actor network also shared across agents, I changed hyperparamters and I also changed the OUNoise for the one in the MADDPG code. I increased OUNoise's parameters to explore more.

## Plot of Rewards:
<img width="371" alt="Score_10" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/5ccf9b9e-3132-41e1-955d-17ffcde01f1b">

## Ideas for Future Work
I could try adding PER (Prioritized Experience Replay) to make less frequent but important transitions more repeatable and learn from them.
