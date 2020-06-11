# deep-Q-networks-cartpole
This repo is a simplified version of deep Q networks produced by DeepMind. I used multilayer neural networks to represent the policy network, which takes the 4-dimensional environment state as input and generate the corresponding action. a memory buffer is used to decorrelate the ```(state, action, reward)``` tuples to make the data distribution more individual independent in order to stablize the training procedure. According to the original [DQN paper](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf), target network is used in order to lower the update frequency of the evaluating process to alleviate the 'chasing moving target' phonomenon.
## Requirements:
- Python 3.7.3
- Pytorch 1.3.0
- OpenAI Gym 0.15.7
