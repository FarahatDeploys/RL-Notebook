# Introduction
RL can be defined as the science of decision-making, and how to make the best sequence of decisions, this makes RL intersection between different fields (optimal control, economics, neuroscience, etc..)

## What makes RL different from other Machine Learning Paradigms?
the major difference between RL and other paradigms is 
- there is no supervision but direct rewards signal from the environment.
- Feedback is delayed with respect to time, not instantaneous
- Time matters, having an early reward is not equivalent to late rewards.
  


## Applications 

-Flying Helicopter <br>
-Defeating the world champion in the go game. <br>
-Investment portfolio. <br>
-Power Plant Control. <br> 

## RL Problem and Definitions 
Reinforcement learning relies on the assumption that any goal can be achieved by increasing the cumulative reward, and the agent's role will be to maximize the cumulative reward.
for example, an agent controlling a power plant will receive a positive reward for generating power and a negative reward for exceeding the safety threshold.


in summary, we can say that the agent will be **receiving observation and reward** from the environment but producing **actions** at **every time step**.<br>

**History** can be defined as a sequence of actions, observations, and rewards, our goal given the history is to build a mapping algorithm between the History and Actions.<br>
**State** is defined as the information used to determine what to do next, we can say that state is a function of history.<br>

