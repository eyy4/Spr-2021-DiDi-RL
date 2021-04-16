# Spring Capstone 2021 - Columbia DSI 
## Off-Policy Evaluation for Taxi Driver Repostioning Policies



##### Team: Danyang Han, Anita Pinto, Elizabeth Yum
##### Mentors: Prof Vineet Goyal, Dr Zhiwei (Tony) Qin

### Abstract

We propose a novel method to tackle the problem of driver repositioning on ride-hailing platforms through off-policy evaluation by the creation of an environment simulator. First, we propose to create an environment simulator using historical data that stochastically generates uncensored demand, supply, passenger-driver matching and destination probability. Next, the environment simulator is leveraged to run iteratively for off-policy evaluation through Monte Carlo rollout. Finally, we propose that a generalized policy iteration process may be applied for off-policy learning.


### Calculation of Probability Matching and Demand Estimation 
