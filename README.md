# Tennis
These are two DDPGS learning to play tennis collaborately. They have to bounce a ball over the net.

## Reward System:
If an agent hits the ball over the net, it receives a reward of +0.1
If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.

## Observation Space:

There are 24 variables in the state space corresponfing to position and velocity of the ball and racket. Each agent receives its own local observation. 

## Action Space:

Two continuous actions, corresponding to movement toward or away from the net and jumping.

## Solution of the environment:
The environment is considered solved for an average score over 100 episodes of +0.5.

NOTE: I used Udacity's workspace so I don't know which dependencies are needed!
NOTE: You can download the files and put them into a jupyter notebook, but you still need the dependencies!

## Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name drlnd python=3.6
	source activate drlnd
	```
	- __Windows__: 
	```bash
	conda create --name drlnd python=3.6 
	activate drlnd
	```
	
2. If running in **Windows**, ensure you have the "Build Tools for Visual Studio 2019" installed from this [site](https://visualstudio.microsoft.com/downloads/).  This [article](https://towardsdatascience.com/how-to-install-openai-gym-in-a-windows-environment-338969e24d30) may also be very helpful.  This was confirmed to work in Windows 10 Home.  

3. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.  
	- Next, install the **classic control** environment group by following the instructions [here](https://github.com/openai/gym#classic-control).
	- Then, install the **box2d** environment group by following the instructions [here](https://github.com/openai/gym#box2d).
	
4. Clone the repository (if you haven't already!), and navigate to the `python/` folder.  Then, install several dependencies.  
    ```bash
    git clone https://github.com/udacity/deep-reinforcement-learning.git
    cd deep-reinforcement-learning/python
    pip install .
    ```

5. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drlnd` environment.    
    ```bash
    python -m ipykernel install --user --name drlnd --display-name "drlnd"
    ```

6. Before running code in a notebook, change the kernel to match the `drlnd` environment by using the drop-down `Kernel` menu. 

![Kernel][image2]
