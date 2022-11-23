### Lewis Signaling Results from Naturalistic Model

### Motivation
Examining the performance of Lewis Signaling model under Naturalistic Conditions. This helps us examine whether the success of Lewis Signaling model is due to its assumptions or does it fare well even under the introduced naturalistic conditions.

### Data 
Two models have been equipped for this reearch. Model 1 serves as a tool to examine traditional conditions while Model 2 to test for Naturalistic Conditions.  <br>
Data was then  generated from the following model and its Naturalstic extension. The model can be found here: <a href="https://ccl.northwestern.edu/netlogo/models/SignalingGame"> here</a>.

### Evaluation Model 1
Model 1 is evaluated by comparing the traditional Lewis Signaling model's (Model 1) results with past literature. This helps us establish confidence in our Lewis model while transitioning the model to naturalistic conditions.

### Evaluation Model 2
For Model 2, we will examine how the performance of the model varies as we vary certain naturalistic parameters. As a result, the study provide a comparitive analysis of the model's performance under different conditions.<br>
**To check whether optimisation of Singalling system occurs; we will be looking at two parameters namely:
- Sucessful number of games: Games where convention was established
- Average number of interactions/games: For the convention to be established

For evaluation check:  402Analysis.ipynb 

### Data Features Model 1
Traditional Variables:

- Number of Agents (num-agents): # of agents on the grid
- Number of Signals (num-signals): # of signals sender possess
- Number of States (num-states): # of signals world states

### Data Features Model 2
Other than the Traditional Variables, the Naturalistic Variables were included:
- Movement: Allows agents to switch between directed and random movement
- Eavesdropping: Other than the traditional context, this model enables us to allow eavesdroppers to eavesdrop as well as play the signaling game in the next rounds.

- Number of Agents (num-agents): # of agents on the grid
- Number of Signals (num-signals): # of signals sender possess
- Number of States (num-states): # of signals world states

### Used Libraries 
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

 ```
 ### Conclusion
1. As expected, biased movement outperformes Random Movement when it comes establishing signaling systems.
2. Random movement may be used a succesful tactic to reach convention with more number of agents and lesser space. 
3. Eavesdroppers when allowed to play the Signaling game (in the subsequent rounds) can optimise the game in all conditions (traditional and asymmetric) in two ways: 
 -> By increasing the chances of reaching convention
 -> By decreasing the number of interactions it takes among agents to reach convention
 
