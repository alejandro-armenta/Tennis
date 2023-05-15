
## Learning Algorithm
I did a lot of things, I changed the replay buffer to be shared across agents, I also changed the OUNoise for the one in the MADDPG code. I also added Noise decay, that really helped me with the results.


created two DDPG agents, they are totally indendent, they have independent replay buffers and independent actor and critic networks, they are trained and I compute the mean score across 100 episodes.

The neural network for the actor has 1 hidden layer and it uses tanh function for outputting values between -1 and 1.

The critic has as input the state and actions, actions are input in the second layer.
And it has only one output.

I modified some hyperparameters such as the weight decay (regularizaton) no regularization. And the critic's learning rate to 1e-3.

## Plot of Rewards:

The environment hasn't been solved. I need for help to know how to solve the problem.

<img width="394" alt="Score_3" src="https://github.com/alejandro-armenta/Tennis/assets/81542828/0a5f3015-e1bf-4d35-8d96-9f9cde8bd827">



## Ideas for Future Work
I don't know how to solve the problem. Could you help me?
