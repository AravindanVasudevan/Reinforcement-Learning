# Inverting a pendulum using Q-Learning

This project is an implementation of the Q-learning algorithm for inverting a pendulum, a classic problem in the field of control engineering. The goal of the project is to demonstrate the effectiveness of reinforcement learning techniques in solving complex control problems.

The Q-learning algorithm is a model-free reinforcement learning algorithm that learns an optimal policy by directly approximating the Q-function, which measures the expected reward of taking a particular action in a particular state. The Value function and policy are as follows:
<img width="406" alt="Screenshot 2023-05-10 000639" src="https://github.com/AravindanVasudevan/Reinforcement-Learning/assets/57245944/29357c83-4777-4637-9921-d43eb5a8123b">
<img width="411" alt="Screenshot 2023-05-10 000912" src="https://github.com/AravindanVasudevan/Reinforcement-Learning/assets/57245944/6c1075d5-b3e6-4fad-bddb-56e5fe902e02">

During training, the Q-learning algorithm gradually updates the Q-values using the Bellman equation, which is used to find the optimal value function and policy table. By iteratively adjusting the policy and value function, the algorithm successfully learned to invert the pendulum and keep it stable in the upright position. 

The plot below shows the loss per episode:
<img width="413" alt="Screenshot 2023-05-10 001117" src="https://github.com/AravindanVasudevan/Reinforcement-Learning/assets/57245944/f40279b4-2c95-4010-b234-6173edbaf6f0">
