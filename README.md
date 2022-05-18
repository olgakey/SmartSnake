# SmartSnake
Smart Snake Game using Reinforcement learning
Description: Reinforcement Learning is an exciting and fast-growing field in Artificial Intelligence.
Reinforcement Learning involves an agent, an environment, a set of actions available to an agent,
and a reward/punishment function that rewards an agent for good actions and punishes it for the bad actions.
An agent, in the case of the snake game it is a snake that explores an environment, takes some steps,
and updates its parameters to maximize its expected reward. In this project, an environment will be nxn board.
Possible states of the domain will depend on where a snake is and where the reward (food) is.
The possible actions that a snake can take will be to turn left, right, up, and down the board.
Besides Reinforcement learning, we will explore and use Deep Q-Learning.
The idea behind it is that the Q-Learning function takes a current state as an input and calculates a vector
that contains expected rewards for each possible action. The snake should pick its activity based on this vector to maximize its reward.
Then the environment gets updated, and the snake gets its reward or punishment.
For weights, we will use the Bellman Equation that is often used with the Q-Learning function to generate losses and update the weights.  

To start the learning process, run Agent.py
