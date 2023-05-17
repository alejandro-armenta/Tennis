
## Learning Algorithm
I have two critics, one replay buffer that is shared across agents and one actor network also shared across agents, I changed hyperparamters and I also changed the OUNoise for the one in the MADDPG code. I increased OUNoise's parameters to explore more.

## Plot of Rewards:
<img width="390" alt="Score_7" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/d9bf1334-e738-48a4-9a57-322fb4bd0f36">

## Ideas for Future Work
I could try adding PER (Prioritized Experience Replay) to make less frequent but important transitions more repeatable and learn from them.
