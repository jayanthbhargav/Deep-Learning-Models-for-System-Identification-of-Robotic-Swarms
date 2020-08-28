--------Simulation Parameters--------- 
MAX_ITER = 250000 # total number of iterations to simulate, no stability formed in this time span
STEP_SIZE = 0.0001 # each step in Euler's method
AGENT_COUNT = 10
SAMPLING_RATE = 1000 # This means there are 1000 data points
COUPLING_STRENGTH = 0.25

-------------Description--------------
- This simulates a swarm of 10 self-propelled agents.
- It's a second order system with white gaussian noise ~ N(0,100)
- No time lag
- Each file has a different set of initial conditions, all randomly chosen within 10 x 10 square
- 53 files