# Spring Capstone 2021 - Columbia DSI 
## Off-Policy Evaluation for Taxi Driver Repostioning Policies



##### Team: Danyang Han, Anita Pinto, Elizabeth Yum
##### Mentors: Prof Vineet Goyal, Dr Zhiwei (Tony) Qin


### Abstract



We propose a novel method to tackle the problem of driver repositioning on ride-hailing platforms through off-policy evaluation by the creation of an environment simulator. To create this environment simulator, we used historical data that stochastically generates uncensored demand, supply, passenger-driver matching and destination probability. We also used historical data on trip fare, trip duration between zones to estimate earnings and cost of trip(fuel). The environment simulator is leveraged to run iteratively for off-policy evaluation through Monte Carlo rollout. The simulations are run on different environment settings namely weekend/ weekday and shift time variants until the end of the shift hours which is typically around 11 hours from the start time of the shift. We used earnings gathered during a shift and used Monte Carlo roll out to estimate state values on a geographical and temporal space. Finally, we propose that a generalized policy iteration process may be applied for off-policy learning and be used for comparing different repositional policies.


Final Report explaining the project can be read here 

The main simulator to run a single iteration is <a href="https://github.com/eyy4/Spr-2021-DiDi-RL/blob/master/notebooks/Simulation%20-%20V2.ipynb " > here </a>

All files used for generating data, models, util functions are under the directory <a href="https://github.com/eyy4/Spr-2021-DiDi-RL/tree/master/notebooks"> notebooks</a>

For an overview of previous capstone project, visit <a href = "https://github.com/skyetim/didi-vehicle-repositioning-strategy"> here </a>
