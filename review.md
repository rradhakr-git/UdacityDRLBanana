Dear Udacian,

The project is very well implemented and meets the specifications!
Impressive work spending time to understand and implementing DQN to
solve the Navigation environment! Congratulations on completing the
project. The agent performs well and solves the environment by achieving
an average score of +15.04 (over 100 episodes) in 947 episodes. The
model seems to be very efficient with three hidden layers. Good work
using relu activation in the hidden layers. A very good submission
overall!

As next step, please go through the resource: [[human-like robot hand
trained to manipulate physical objects with unprecedented
dexterity]{.underline}](https://blog.openai.com/learning-dexterity/).

All the best for the next projects! 

**Training Code**

**The repository (or zip file) includes functional, well-documented, and
organized code for training the agent.**

The submission contains Navigation.ipynb notebook, code files, readme,
and project report. The code is functional.\
The implemented Deep Q Network looks good!

You should definitely check the following resources to progress with the
learning further:

[[Speeding up DQN on PyTorch: how to solve Pong in 30
minutes]{.underline}](https://medium.com/mlreview/speeding-up-dqn-on-pytorch-solving-pong-in-30-minutes-81a1bd2dff55)

[[Advanced DQNs: Playing Pac-man with Deep Reinforcement Learning by
mapping pixel images to Q
values]{.underline}](https://towardsdatascience.com/advanced-dqns-playing-pac-man-with-deep-reinforcement-learning-3ffbd99e0814)

**The code is written in PyTorch and Python 3.**

The code is written in pytorch and python3.

-   A good read: [[PyTorch vs TensorFlow --- spotting the
    difference]{.underline}](https://towardsdatascience.com/pytorch-vs-tensorflow-spotting-the-difference-25c75777377b)

**The submission includes the saved model weights of the successful
agent.**

Thanks for including the saved model weights of the successful agent.
The weights are saved as checkpoint.pth.

**README**

**The GitHub (or zip file) submission includes a README.md file in the
root of the repository.**

Submission includes README file for the project.

**The README describes the the project environment details (i.e., the
state and action spaces, and when the environment is considered
solved).**

Awesome work providing the project environment details in
the Introduction section of the README.\
State space, action space, reward function and when the environment is
considered solved is specified very informatively.

**The README has instructions for installing dependencies or downloading
needed files.**

Proper instructions have been specified in the Getting Started section
of the README to download the necessary files.

**The README describes how to run the code in the repository, to train
the agent. For additional resources on creating READMEs or using
Markdown,
see [here](https://www.udacity.com/courses/ud777) and [here](https://guides.github.com/features/mastering-markdown/).**

README file contains the instructions to train the agent
using Navigation.ipynb file.

**Report**

**The submission includes a file in the root of the GitHub repository or
zip file (one of Report.md, Report.ipynb, or Report.pdf) that provides a
description of the implementation.**

Report has been included in the root of the github repository.

**The report clearly describes the learning algorithm, along with the
chosen hyperparameters. It also describes the model architectures for
any neural networks.**

The report is rather informative providing insight on every aspect of
the project which includes implementation, model architectures,
hyperparameters, rewards, future works.

-   Good implementation of the agent for Deep Q Network.

-   Good work keeping three hidden layers with 128, 128, and 64 units,
    respectively, in the network.

-   Good work using relu activation in both the hidden layers.

-   Correct decoupling of the parameters being updated from the ones
    that are using a target network to produce target values.

-   Perfect implementation of The Epsilon-greedy action selection to
    encourage exploratory behavior in the agent.

-   Good use of tau parameter to perform soft-update. It helps to
    prevent variance into the process due to individual batches.

-   Good use of the replay memory to store and recall experience tuples.

-   The implementation is easy to debug and easily extensible.

**A plot of rewards per episode is included to illustrate that the agent
is able to receive an average reward (over 100 episodes) of at least
+13. The submission reports the number of episodes needed to solve the
environment.**

**Awesome**

-   The agent seems to perform very well!

-   The agent is able to achieve an average score of +15.04 over last
    100 episodes in just 947 episodes!

-   The submission discusses the rewards plot obtained clearly.

**The submission has concrete future ideas for improving the agent\'s
performance.**

Great job providing the ideas to experiment more in future with the
project by trying the following:

-   Double DQN

-   Duelling DQN

-   Prioritized Experience Replay

-   Rainbow algorithm

**Suggestions**

As pointed in the report, you should try implementing Prioritized
Experience Replay also. It helps to improve the performance and
significantly reduces the training time. A fast implementation of
Prioritized Experience Replay is possible using a special data structure
called Sum Tree. I found a [good implementation
here](https://github.com/rlcode/per).

I would like to point you to the following resources:

[[Rainbow: Combining Improvements in Deep Reinforcement
Learning]{.underline}](https://arxiv.org/abs/1710.02298)

[[Conquering OpenAI Retro Contest 2: Demystifying Rainbow
Baseline]{.underline}](https://medium.com/intelligentunit/conquering-openai-retro-contest-2-demystifying-rainbow-baseline-9d8dd258e74b)

As a next step, I highly suggest you to use the same algorithm to train
an agent on an environment just by taking the screen pixels as the
input. This would be more complicated and would require to use a more
powerful convolutional neural network. As an example, you can
check [Using Keras and Deep Q-Network to Play
FlappyBird](https://yanpanlau.github.io/2016/07/10/FlappyBird-Keras.html).
