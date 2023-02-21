## Banana picker - Technical report
-------------------------------------------

Ramaiah Radhakrishnan
Feb 20 2023

-----------------------------

### Learning Algorithm

Standard Deep Q-Network (DQN) Algorithm is used following the same approach used in the class exercise as well as the paper titled Human-level control through deep reinforcement
learning

I had to make minor modification to exercise with respect to adjust to the new environment. I first made it to work and then adjusted the neural network architecture that I will articulate below

###  Model Architecture

I tried originally with 2 hidden layers one with 64 nodes, another with 32 nodes. Both  where passed through RELU activation functions  and finally the output layer to convert to the 4 action space.
The initial episodes were not showing much improvement on the score. My attempt with two hidden layers with 128 nodes showed good progress as I could achieve the 13+ in 530 episodes. But from 13 to 15, the progress was either slow or stayed at the same 13 or 14 scores with oscilation

but I really wanted to reach atleast 15, so I just added one more hidden layer with 64 nodes and I could reach my self imposed target of 15 within 950 episodes. 

### Plot of the scores (Results)




### Hyperparameters

BUFFER_SIZE = int(1e5)  # replay buffer size
BATCH_SIZE = 64         # minibatch size
GAMMA = 0.99            # discount factor
TAU = 1e-3              # for soft update of target parameters
LR = 5e-4               # learning rate 
UPDATE_EVERY = 4        # how often to update the network
n_episodes=1700.        # Number of episodes
eps_start=1.0.          
eps_end=0.01
eps_decay=0.995

### Future Work

The other algorithms from the lecture can be tried to train and test - Double DQN, Prioritized expereince, Dueling DQN. I am also curious about the Rainbow algorithm from Google DeepMind


