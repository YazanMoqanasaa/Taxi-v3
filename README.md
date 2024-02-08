# AI Project
This Project to handle highD data files using Python.

## Dataset

Please move the data file to the project file so that the program can read it  ```AI-Project/data```

## Run Locally

Clone the project

```bash
  git clone 
```

Go to the project directory

```bash
  cd AI-Project
```

## Deployment
To deploy this project run
- install code editor i recommend (VS Code)
- install python from [here](https://www.python.org/)
- in this point we will use pandas library to read csv files [docs](https://pandas.pydata.org/docs/)
- you can download anaconda [Anaconda](https://www.anaconda.com)

## Initial Code
To read all csv files from data folder and store into data array
```bashimport gym
import random
import numpy as np
#Red — 0 , Green — 1, Yellow — 2, and Blue — 3 for pick up
streets = gym.make("Taxi-v3").env #New versions keep getting released; if -v3 
doesn't work, try -v2 or -v4
##Red — 0 , Green — 1, Yellow — 2, and Blue — 3 for pick up
#Each state is defined by a 4 entries tuple: （taxi_row, taxi_col, 
passenger_location, destination)
initial_state = streets.encode(2, 3, 2, 0)
streets.s = initial_state
streets.render()

```

## Guideline for submitting the task:

- Reinforcement learning (RL) has an underlying Markov Decision Process (MDP), and the goal of RL is to solve this MDP by deriving an optimal policy. Due to the lack of knowledge of the transition function T and the reward function R, agents must learn the optimal policy through online trial-by- error rather than pure offline computation.
Q-Learning is a model-free learning where it learns the optimal policy directly through trial and error with q-value iteration updates.

Q-Learning sample-based Q-value iteration:
 


- Using Python, read all the files that are labeled as "Taxi-v3" as one dataframe.
