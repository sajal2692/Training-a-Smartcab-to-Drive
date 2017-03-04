# Reinforcement Learning
## Project: Train a Smartcab How to Drive

This project was completed as a part of Udacity's Machine Learning Nanodegree.

### Introduction

In this project, we work towards constructing an optimized Q-Learning driving agent that will navigate a Smartcab through its environment towards a goal. Since the Smartcab is expected to drive passengers from one location to another, the driving agent will be evaluated on two very important metrics: Safety and Reliability. A driving agent that gets the Smartcab to its destination while running red lights or narrowly avoiding accidents would be considered unsafe. Similarly, a driving agent that frequently fails to reach the destination in time would be considered unreliable. Maximizing the driving agent's safety and reliability would ensure that Smartcabs have a permanent place in the transportation industry.

Note that, template code for the Smartcab's environment and other agents (cars) in the environment was already provided. Our job is to implement a learning algorithm so that the Smartcab behaves properly, following the rules and regulations, while moving towards its destination.

### [Analysis Notebook](https://github.com/sajal2692/Training-a-Smartcab-to-Drive/blob/master/smartcab.ipynb) 
Please visit the notebook linked above to check out a step-by-step analysis of the project at various stages, and to understand the project better.



### Install

This project requires **Python 2.7** with the [pygame](https://www.pygame.org/wiki/GettingStarted
) library installed.


### Run

In a terminal or command window, navigate to the top-level project directory `smartcab/` (that contains this README) and run one of the following commands:

```python smartcab/agent.py```  
```python -m smartcab.agent```

This will run the `agent.py` file and execute your agent code.

You might want to change the speed of the simulation in agent.py (simulation update delay) to make it go faster or slower, as per your need.
