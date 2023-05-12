
## Learning Algorithm
I created two DDPG agents, they are totally indendent, they have independent replay buffers and independent actor and critic networks, they are trained and I compute the mean score across 100 episodes.

I modified some hyperparameters such as the weight decay (regularizaton) no regularization. And the critic's learning rate to 1e-3.

## Plot of Rewards:
<img width="401" alt="Score_1" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/fd1684fa-fc82-4bec-92ca-17ed9cf71c0e">

## Ideas for Future Work

So I tried with the hyperparameters but I could not reach the expected mean reward, I don't know what else to try. Is there something else I could try out?
