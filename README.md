# Reinforcement Learning
Reinforcement learning (RL) is a type of machine learning paradigm where an agent learns to make decisions by interacting with an environment. The agent takes actions in the environment, receives feedback in the form of rewards or penalties, and uses this feedback to learn a strategy or policy that maximizes the cumulative reward over time.

Key components of reinforcement learning:

**Agent:** The entity that takes actions in the environment based on its current knowledge or policy.

**Environment:** The external system with which the agent interacts. It responds to the actions taken by the agent and provides feedback in the form of rewards or penalties.

**State:** A representation of the current situation or configuration of the environment. The state provides information to the agent about its current condition.

**Action:** The set of possible moves or decisions that the agent can take in a given state.

**Reward**: A numerical value that the environment provides to the agent as feedback after it takes an action. The goal of the agent is typically to maximize the cumulative reward over time.

**Policy:** A strategy or mapping from states to actions that the agent uses to make decisions.

The learning process in reinforcement learning involves the agent exploring the environment, learning from the feedback, and refining its policy to improve decision-making. Common algorithms in reinforcement learning include Q-learning, Deep Q Network (DQN), and Policy Gradient methods.

Reinforcement learning has applications in various domains, including robotics, gaming, finance, and natural language processing. It has gained popularity for solving problems where explicit programming or supervised learning may be challenging or impractical.

Within this repository, my emphasis revolves around Q-learning algorithms applied to queue management, specifically in dynamically changing arrival environments. The primary objective is to determine the optimal number of servers for efficient queue handling.


<a href="https://github.com/burcuozek/ReinforcementLearning/blob/main/RL.ipynb">RL.ipynb</a> implements Q-learning for the FrozenLake environment, a built-in environment.

In <a href="https://github.com/burcuozek/ReinforcementLearning/blob/main/RL_Queue.ipynb">RL_Queue.ipynb</a> file, Q-learning is applied to Queue Management. The project involves a queue, and the Q-learning algorithm determines the optimal number of servers based on arrivals. This scenario could represent various queues, such as a hospital admission queue, where RL decides the number of beds considering patient arrivals. The reward function incorporates queue lengths, waiting times, and server utilizations.

<a href="https://github.com/burcuozek/ReinforcementLearning/blob/main/DeepQLearning.ipynb">DeepQLearning.ipynb</a> file delves into the theory of deep reinforcement learning, comparing it with regular Q-learning and adapting the algorithm accordingly.

