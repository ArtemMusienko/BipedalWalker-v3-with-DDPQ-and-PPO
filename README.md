![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

# BipedalWalker-v3 with DDPQ and PPO

[![ru](https://img.shields.io/badge/README_на_русском-2A2C39?style=for-the-badge&logo=github&logoColor=white)](README.ru.md)  

This code implements two reinforcement learning (**RL**) methods, namely **DDPQ** and **PPO**.

## DDPG (Deep Deterministic Policy Gradient):

**DDPG** is an algorithm that uses a deterministic policy to work with continuous action spaces. It combines the ideas of Q-learning and policy gradient.

**Features**:

-  **Deterministic policy:** Direct mapping of states to actions.

-  **Exploration through noise addition:** Adding stochastic noise to actions to encourage exploration.

-  **Replay buffer:** Storing experience in a buffer and reusing it for learning.


## PPO (Proximal Policy Optimization):

**PPO** is an algorithm that limits policy updates to prevent sudden changes and ensure stable training.

 **Features**:

-  **Limited policy updates:** Using limited policy updates to stabilize training.

-  **Sample reuse:** Reusing samples to improve training efficiency.

-  **Stable optimization:** Ensuring stable policy optimization.

The results have been analyzed and compared using two methods based on the **BipedalWalker-v3** environment. The output and recommendations for improving the model have been written.

For a more detailed description of the code and code blocks, please refer to the **Google Colab Notebook** in this repository.

> I strongly recommend using the **T4 GPU accelerator** from
>  **Google Colab** to run this code!

<div  align="center">

![enter image description here](https://gymnasium.farama.org/_images/bipedal_walker.gif)

</div>