# Deep Reinforcement Learning (DRL) Trading Framework 

(-- See file titled "Write Up" in this repo for a more detailed, easy to follow, walk through
of what the model achieves.) 

Reinforcement Learning - Q-learning 
Q-learning is a model-free reinforcement learning algorithm to learn the value of an action in a particular state. 
It does not require a model of the environment and can handle problems with stochastic transitions and rewards without 
requiring adaptations. 


DRL 
Combining Q Learning with Deep learning gives us the DQN (Deep Q Network) algorithm. 

There are 5 essential pieces to the framework model:
1.	Data Preparation
2.	Environment Setup
3.	Deep Reinforcement Learning Model
4.	Agent Training
5.	Evaluation


"""
This code provides a basic framework for implementing a DQN trading strategy. 
We can replace the data loading and preprocessing steps with your different data sets 
depending on the asset(s) of our preferred investment universe,
as well as define the reward logic and possible actions based on style and parameters of 
strategy. 



Note: Adjust hyperparameters across a range of values to customise, for stress testing and
to get a vision of boundary conditions.  

Performance Measurement:
To monitor the portfolio performance of the trading strategy, 
we can calculate various performance metrics based on the trading actions taken by the agent. 
This framework includes the ability to track and 
evaluate the core portfolio performance metrics (Sharpe etc) during the evaluation phase
"""
