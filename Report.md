
## Learning Algorithm
I have two critics, one replay buffer that is shared across agents and one actor network also shared across agents, I changed hyperparamters and I also changed the OUNoise for the one in the MADDPG code. I increased OUNoise's parameters to explore more. It actually got to 0.8 reward!

## Plot of Rewards:
<img width="388" alt="Score_8" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/d9454618-9944-4719-b4ab-642e5e1e9f6a">

## Ideas for Future Work
I could try adding PER (Prioritized Experience Replay) to make less frequent but important transitions more repeatable and learn from them.
