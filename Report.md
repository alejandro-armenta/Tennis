
## Learning Algorithm
I have one shared critic, one replay buffer that is shared across agents and one actor network also shared across agents, so basically is one DDPG agent playing but with different noises.

## Plot of Rewards:
<img width="414" alt="Score_13" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/ac5edd6b-9595-47f1-8b0e-d862f7a3239e">

## Ideas for Future Work
I could try adding PER (Prioritized Experience Replay) to make less frequent but important transitions more repeatable and learn from them.
