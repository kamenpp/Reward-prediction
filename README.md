# Reward-prediction
Regression on reinforcement learning generated data

## Work in progress
I wanted to address some difficulties my reinforcement learning agent is having and I thought about doing some basic supervised learning on data generated from that (DQN) agent over the period of a training cycle.

I thought that the size of the molecular fingerprint (a bit vector that represents the molecule) may be very influential and impact how the agent takes decisions. It turned out here that this was actually not the case and the different parameters for fingerprinting essentially don't mattter and this is also suggested by data not shown here from training the agent on different fingerprints.

