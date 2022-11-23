### Lewis Signaling Results from Naturalistic Model

### Motivation
Examining the performance of Lewis Signaling model under Naturalistic Conditions. This helps us examine whether the success of Lewis Signaling model is due to its assumptions or does it fare well even under the introduced naturalistic conditions.

### Data 
Two models have been equipped for this reearch. Model 1 serves as a tool to examine traditional conditions while Model 2 to test for Naturalistic Conditions.  <br>
Data was then  generated from the following model and its Naturalstic extension. The model can be found here: <a href="https://ccl.northwestern.edu/netlogo/models/SignalingGame"> here</a>.

### Evaluation Model 1
Model 1 is evaluated by comparing the traditional Lewis Signaling model's (Model 1) results with past literature. This helps us establish confidence in our Lewis model while transitioning the model to naturalistic conditions.

### Evaluation Model 2
Model 1 is evaluated by comparing the traditional Lewis Signaling model's (Model 1) results with past literature. This helps us establish confidence in our Lewis model while transitioning the model to naturalistic conditions.

**After training the RandomForestRegressor model following was performed:
 - Hypyterparameter tuning
 - Feature importance
 - Mean Absolute Error
 - RMSE

For evaluation check:  402Analysis.ipynb 

### Data Features
Kaggle (author of the dataset) has provided data dictionary detailing all of the features of the dataset. To view click <a href="https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data">here</a>. 

### Used Libraries and Pre-Defined Metrics/Models
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

 ```
 ### Conclusion
1. As expected, biased movement outperformes Random Movement.
2. Random movement may be used a succesful tactic to reach convention with a high number of agents and lower space. 
3. Eavesdroppers when allowed to play the Signaling game in the next rounds can optimise the game in all conditions (traditional and asymmetric) in two ways: 
 - By increasing the chances of reaching convention
 - By decreasing the number of interactions it takes among agents to reach convention
 ```
