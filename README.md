# 🧠 Curriculum Learning for Deep Q-Networks (DQN)

> A research-oriented implementation of **Curriculum Learning** using **Deep Q-Networks (DQN)** in a GridWorld environment. This project demonstrates how progressively increasing task difficulty improves reinforcement learning performance compared to traditional baseline training.

---

## 📖 Overview

Reinforcement Learning agents often struggle when trained directly on complex environments. Curriculum Learning addresses this challenge by introducing tasks in an increasing order of difficulty, allowing the agent to gradually acquire knowledge before solving harder problems.

This project compares:

- 🔹 **Baseline DQN** – Trained directly on the hardest environment.
- 🔹 **Curriculum Learning DQN** – Trained progressively from easy to difficult environments.

The implementation is developed using **PyTorch** and evaluates learning performance through multiple experimental metrics.

---

## 🚀 Features

- ✅ Deep Q-Network (DQN) implementation
- ✅ Curriculum Learning strategy
- ✅ Custom GridWorld environment
- ✅ Reward Shaping
- ✅ Sparse Reward environment
- ✅ Obstacle-based maze navigation
- ✅ Performance comparison with Baseline DQN
- ✅ Visualization of training metrics

---

## 🏗️ Project Structure

```text
Curriculum-Learning-DQN/
│
├── Curriculum-Learning-DQN.ipynb
├── README.md
└── outputs/
    ├── Baseline_vs_Curriculum.png
    ├── Convergence.png
    ├── Stability.png
    └── Success_Rate.png
```

---

## 🧩 Curriculum Stages

The curriculum gradually increases the learning complexity through four stages:

| Stage | Environment | Description |
|--------|-------------|-------------|
| Stage 1 | Easy GridWorld | Reward Shaping |
| Stage 2 | Larger GridWorld | Reward Shaping |
| Stage 3 | Maze Environment | Reward Shaping + Obstacles |
| Stage 4 | Maze Environment | Sparse Rewards (Hardest Task) |

---

## 📊 Experimental Results

### 📈 Baseline vs Curriculum Learning

![Baseline vs Curriculum](outputs/Baseline_vs_Curriculum.png)

---

### 📉 Convergence Comparison

<img width="698" height="470" alt="image" src="https://github.com/user-attachments/assets/4979d155-642d-4aff-b659-6405309af119" />


---

### 📊 Training Stability

![Training Stability]<img width="695" height="470" alt="image" src="https://github.com/user-attachments/assets/6894df6f-b7fd-4806-9d13-395a10687991" />


---

### ✅ Success Rate Comparison

![Success Rate]<img width="536" height="451" alt="image" src="https://github.com/user-attachments/assets/e4284dd6-70b2-4cb3-adef-4e56e2675c66" />

---

## ⚙️ Technologies Used

- Python
- PyTorch
- NumPy
- Matplotlib

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/ShivanshuPauskar/Curriculum-Learning-DQN.git
cd Curriculum-Learning-DQN
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

### Jupyter Notebook

```bash
jupyter notebook Curriculum-Learning-DQN.ipynb
```

or execute all notebook cells.

---

## 📈 Performance Metrics

The project evaluates the learning performance using:

- Reward Comparison
- Convergence Analysis
- Training Stability
- Success Rate

These metrics demonstrate the effectiveness of Curriculum Learning over conventional DQN training.

---

## 🎯 Future Improvements

- Experience Replay Buffer
- Target Network
- Double DQN (DDQN)
- Prioritized Experience Replay
- Larger GridWorld environments
- Continuous action spaces
- Hyperparameter optimization

---

## 👥 Contributors

- **Shivanshu Pauskar**
- **Druthi Sai Medampudi**

---

## 📜 License

This project is developed for educational and research purposes.

---

⭐ If you found this project useful, consider giving the repository a **Star**.
