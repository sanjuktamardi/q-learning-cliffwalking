# Q-Learning Cliff Walking

A reinforcement learning project implementing the **Q-learning algorithm** to solve the Cliff Walking problem using Gymnasium.

---

## 📌 Overview

This project demonstrates how an agent learns an optimal policy using **Q-learning**, a model-free reinforcement learning algorithm.
The environment is the classic **Cliff Walking gridworld**, where the agent must reach the goal while avoiding falling off the cliff.

---

## 🎯 Problem Statement

The objective is to train an agent to navigate from the start state to the goal state in a gridworld environment while avoiding the cliff, which results in a large negative reward.

---

## 🌍 Environment Details

* **Environment:** CliffWalking-v1
* **State Space:** Discrete grid positions
* **Action Space:** Up, Down, Left, Right
* **Reward Structure:**

  * -1 for each step
  * -100 for falling off the cliff
  * Goal: reach the destination with minimal penalty

---

## 🧠 Concepts Used

* Reinforcement Learning
* Q-Learning Algorithm
* Exploration vs Exploitation (Epsilon-Greedy Strategy)
* Reward Optimization
* Gridworld Environment

---

## ⚙️ Tech Stack

* Python
* NumPy
* Gymnasium

---

## 📂 Project Structure

```
├── q_learning.py
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/sanjuktamardi/q-learning-cliffwalking.git
cd q-learning-cliffwalking
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the program

```bash
python q_learning.py
```

---

## 📊 Output

* Initially, the agent frequently falls off the cliff
* Over multiple episodes, it learns safer paths
* Eventually converges to an optimal policy that avoids the cliff and minimizes penalties

---

## 🔧 Parameters

You can modify:

* Learning rate (`alpha`)
* Discount factor (`gamma`)
* Exploration rate (`epsilon`)
* Number of episodes

---

## 📈 Results

The agent gradually learns to:

* Minimize cumulative rewards (penalties)
* Avoid the cliff region
* Reach the goal efficiently using an optimal path

---

## 🛠️ Future Improvements

* Implement SARSA for comparison
* Add visualization of learning curves
* Tune hyperparameters for improved performance
* Introduce more complex environments

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.
