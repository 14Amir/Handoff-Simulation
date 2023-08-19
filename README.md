# Handoff-Simulation
Handoff simulation based on Received Signal Strength (RSS)  
This program computes 1 set of 4 RSS from each of the four BS  
The Overall steps:
1. Implement the handoff algorithms that use RSS1,2,3,4 as inputs
2. Include a loop so that you can have 100 sets of the 4 RSS
(point: RSS of different sets only differ due to the random variable of shadow fading)
3. In the loop store variable data between iterations that will be used to make the final histograms/PDFs
