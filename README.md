
# 🚗 Autonomous Navigation in CARLA Using Reinforcement Learning

### 👨‍💻 Project by:
- **Srinivas Peri**  
- **Srimathnath Thejasvi Vondivillu**

---

## 📝 Project Overview
The objective of this project is to design, implement, and train a **reinforcement learning (RL)** agent capable of autonomously navigating a vehicle through diverse urban scenarios in the **CARLA simulator**. The RL agent will make real-time decisions to:
- Avoid obstacles.
- Adhere to traffic regulations.

This project demonstrates the feasibility and effectiveness of **RL techniques** in solving complex navigation problems within simulated environments that closely mimic real-world conditions.

---

## 🌟 Background
Autonomous Vehicles (AVs) represent a breakthrough in transportation technology, promising to enhance safety, efficiency, and accessibility. However, navigating complex urban environments is a significant challenge, requiring:
- Intelligent decision-making based on sensory input.
- Adaptability to varying traffic and weather conditions.

**Reinforcement Learning (RL)** offers a promising approach to tackle these challenges by allowing agents to learn optimal policies through interactions with the environment. By leveraging advanced RL algorithms, we aim to create a robust AV navigation system within CARLA.

---

## 🔧 Approach
### **1. CARLA Simulator**
We utilize the **CARLA Simulator**, an open-source platform designed for autonomous driving research. CARLA provides:
- Realistic urban environments.
- Dynamic weather conditions.
- Day/night cycles.
- Pedestrian and vehicle traffic scenarios.

### **2. Reinforcement Learning Framework**
- **Libraries**: The project employs RL libraries such as **Stable Baselines3** or **RLlib**, offering advanced RL algorithm implementations.
- **Algorithms**: We start with algorithms like:
  - **DQN (Deep Q-Network)**: Balances simplicity and effectiveness.
  - **PPO (Proximal Policy Optimization)**: Robust for dynamic environments.

### **3. Evaluation and Testing**
- Agents are tested on predefined routes to assess their ability to:
  - Avoid collisions.
  - Follow traffic rules.
  - Navigate efficiently to their destination.
- Metrics: Success rate, collision rate, and route completion time.

### **4. Optimization and Tuning**
Based on testing results, we fine-tune the RL model and hyperparameters to improve robustness across varied scenarios.

---

## 📚 Related Work
The following research inspired and guided this project:
1. **Hossain, J. (2023).** Autonomous Driving with Deep Reinforcement Learning in CARLA Simulation. [ArXiv](https://arxiv.org/abs/2306.11217).
2. **Perez-Gill et al. (2021).** Deep Reinforcement Learning-Based Control Algorithms: Training and Validation Using the ROS Framework in CARLA Simulator. [IEEE IV](https://doi.org/10.1109/IV48863.2021.9575616).
3. **Gutiérrez-Moreno et al. (2022).** Reinforcement Learning-Based Autonomous Driving at Intersections in CARLA Simulator. [MDPI Sensors](https://doi.org/10.3390/s22218373).

---

## 🛠 Tools and Technologies
- **Simulation**: CARLA
- **Programming Languages**: Python
- **Frameworks**: TensorFlow, PyTorch
