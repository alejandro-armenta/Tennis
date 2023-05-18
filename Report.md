
## Learning Algorithm
I have two critics, one replay buffer that is shared across agents and one actor network also shared across agents, I changed hyperparamters and I also changed the OUNoise for the one in the MADDPG code. I increased OUNoise's parameters to explore more. It actually got to 0.8 reward!

## Plot of Rewards:
<img width="374" alt="Score_9" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/fc279dd5-7bca-4d5e-b6da-4c1e19ef3606">

## Ideas for Future Work
I could try adding PER (Prioritized Experience Replay) to make less frequent but important transitions more repeatable and learn from them.
