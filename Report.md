
## Learning Algorithm
I created two DDPG agents, they are totally indendent, they have independent replay buffers and independent actor and critic networks, they are trained and I compute the mean score across 100 episodes.

I modified some hyperparameters such as the weight decay (regularizaton) no regularization. And the critic's learning rate to 1e-3.

## Plot of Rewards:
<img width="389" alt="Score_2" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/6fcf270b-f41c-41f5-b91d-23bd878494db">


## Ideas for Future Work
I tried changing the reward calculation using the max of both agents. And it did improved the score, but it does not solve the environment anyway.
