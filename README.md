
#  Snake AI – Reinforcement Learning Project

This project trains an AI agent to play the classic **Snake Game** using **Deep Q-Learning (DQN)**.

The agent learns through trial and error, improving its performance over time by maximizing rewards.

---

##  Features
- Reinforcement Learning using Deep Q-Network (DQN)
- Experience Replay
- Epsilon-Greedy Exploration
- Real-time training visualization
- Increasing score over episodes

---

##  How It Works
The agent:
- Observes the game state  
- Chooses actions (left, right, straight)  
- Receives rewards:
  - +10 for eating food  
  - -10 for collision  
- Learns optimal behavior using neural networks  

---

##  Training Behavior
During early training:
- Scores may fluctuate
- Sudden spikes (like score 17) are normal
- Stability improves with more episodes




