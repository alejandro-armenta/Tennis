
## Learning Algorithm
I have one shared critic, one replay buffer that is shared across agents and one actor network also shared across agents, so basically is one DDPG agent playing but with different noises. The environment was solved in 624 episodes! I think reducing complexity is really important for learning, in that way exploring with hyperparameters is easier.

## Plot of Rewards:
<img width="380" alt="Score_12" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/5cb76b99-4d1f-492b-a355-1af8fcdc9191">

## Ideas for Future Work
I could try adding PER (Prioritized Experience Replay) to make less frequent but important transitions more repeatable and learn from them.
