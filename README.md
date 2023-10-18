# Risk-Averse-Preview-Based-Q-Learning-Algorithm
## A Risk-Averse Preview-Based Q-Learning Algorithm: Application to Highway Driving of Autonomous Vehicles

### [Link to paper](https://ieeexplore.ieee.org/abstract/document/10056416)

#### Authors: [Majid Mazouchi](https://majid-mazouchi.github.io/), Subramanya P. Nageshrao, Hamidreza Modares
### Abstract
A risk-averse preview-based Q -learning planner is presented for navigation of autonomous vehicles (AVs). To this end, the multilane road ahead of a vehicle is represented by a finite-state nonstationary Markov decision process (MDP). A risk assessment unit module is then presented, which leverages the preview information provided by sensors along with a stochastic reachability module to assign reward values to the MDP states and update them as scenarios develop. A sampling-based risk-averse preview-based Q -learning algorithm is finally developed, which generates samples using the preview information and reward function to learn risk-averse optimal planning strategies without actual interaction with the environment. The risk factor is imposed on the objective function to avoid fluctuation of the Q values, which can jeopardize the vehicle’s safety and/or performance. The overall hybrid automaton model of the system is leveraged to develop a feasibility check unit module that detects unfeasible plans and enables the planner system to react proactively to the changes of the environment. Finally, to verify the efficiency of the presented algorithm, its implementation on two highway driving scenarios of an AV in a varying traffic density is considered.

### Overview figure
![1st paper](https://github.com/majid-mazouchi/majid-mazouchi.github.io/blob/main/assets/img/RiskQProj.png)
