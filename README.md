# Reinforcement-Learning

Python Code to Apply Reinforcement Learning Concepts on AWS Deep Racer.

https://aws.amazon.com/deepracer/

# Functions Used:

__init__ : Constructor defined to set number of episodes (Here we have set steps to 30 which can be changed)

get_observation : Returns a zero vector

get_actions : Returns either 0 or 1 on basis of actions done.

For Agent's Class in beginning reward is zero and then it understands the environment, makes decision on whatever it has understand, gives its decision to the environment and atlast gets the reward on basis of above steps.