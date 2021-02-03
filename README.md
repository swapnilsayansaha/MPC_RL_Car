# MaP, CaP, RaLly! Hybrid Architecture for Planning and Control of UGV in Stochastic Environments
Assignment and Course Project Repository for ECE239AS (Reinforcement Learning), Spring 2020. Instructor: Dr. Lin Yang. (c) 2020 Swapnil Sayan Saha (NESL, Dept. of ECE, UCLA), Nathaniel Snyder (Dept. of MAE, UCLA) and Brian Wang (NESL, Dept. of CS, UCLA)

With the advent and commercialization of unmanned ground vehicles (UGV), handling stochasticity safely but optimally in the operating environment in realtime entails computational and implementation complexities. In this paper, we benchmark the performance of a low-latency hybrid UGV controller that combines long-term goal convergence guarantees from control algorithms with the shortterm robustness of reinforcement learning (RL) to safely guide an UGV to avoid dynamic obstacles while following near-optimal trajectories. Accelerated through imitation learning via stochastic online oracles, our evaluations show that the hybrid controller, using model-predictive-control (MPC) and deep Q-network (DQN), has superlative performance metrics over formal methods and RL frameworks working alone, with the potential of paving the way to Level-5 UGV controllers.

![Device_Image](Course%20Project/controller.jpg)


Video demo: https://youtu.be/nSMOpdZxkNM
