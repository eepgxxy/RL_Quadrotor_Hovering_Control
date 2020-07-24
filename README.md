# RL_Quadrotor_Velocity_Control (四轴飞行器悬浮控制)
Using reinforcement learning algorithm TD3 from Parl to solve quadrotor hovering control based on RLSchool  environment.

[RLSchool](https://github.com/PaddlePaddle/RLSchool) is a group of reinforcement learning simulation environments。


This repository includes the user-friendly jupyter notebook version of the solution.
The code is written using [PaddlePaddle](https://github.com/PaddlePaddle). The TD3 algorithm form [PARL](https://github.com/PaddlePaddle/PARL) is used. 

After training for 1.2e6 steps, an average score of 9000 is achieved, which far more better than the DDPG version with the same hyperparameters.

![DDPG train rewards](https://github.com/eepgxxy/RL_Quadrotor_Hovering_Control/blob/master/ddpg_train.png)

![TD3 train rewards](https://github.com/eepgxxy/RL_Quadrotor_Hovering_Control/blob/master/td3_train.png)

![DDPG eval rewards](https://github.com/eepgxxy/RL_Quadrotor_Hovering_Control/blob/master/ddpg_eval.png)

![TD3 eval rewards](https://github.com/eepgxxy/RL_Quadrotor_Hovering_Control/blob/master/td3_eval.png)