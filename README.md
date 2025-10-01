# 🛫 Reinforcement Learning at 30,000 Feet: Managing Airports During Wartime

📖 **Read the full blog here**: [Medium Blog](https://medium.com/@atharvhkulkarni/reinforcement-learning-at-30-000-feet-managing-airports-during-wartime-cbde10b62e0f)  

This project simulates airport operations using **Reinforcement Learning (RL)** to manage increased air traffic during a hypothetical **India–Pakistan wartime scenario in 2025**. It demonstrates how intelligent agents can optimize gate assignments, prioritize military flights, and minimize delays.

## 🎯 Objective

To build a custom RL environment where an agent learns to:
- Handle increased wartime air traffic
- Prioritize military over civilian flights
- Optimize gate allocation and reduce wait times

## 📁 Dataset

- Simulated flight schedules with dynamic categories (military vs civilian)
- Custom environment reflecting airport resource constraints

## 🧠 Technologies Used

- **Python**
- **Gym** (custom environment)
- **NumPy**, **Pandas**
- **Matplotlib** for visualization
- **Deep Q-Learning (DQN)** for training

## 📌 Key Features

- Custom RL environment simulating airport gates and queues
- Real-time priority handling for military aircraft
- Learning-based decision-making vs baseline random policy
- Performance metrics: average reward, gate utilization, wait time

## 📈 Results & Insights

- DQN agent showed significant improvement over naive policies
- Efficient management of congestion during simulated wartime surges
- RL agent learned to adapt dynamically to changing flight priorities

## 🚀 Future Work

- Introduce **weather conditions** and **emergency landings**
- Apply **Multi-Agent RL** for handling multiple terminals
- Deploy visualization via **Streamlit dashboard**

## 📎 Repository Structure

```
📦 RL_Airport_Management/
 ┣ 📄 Reinforcement_Learning_at_30_000_Feet.ipynb
 ┣ 📄 README.md
 ┗ 📁 Env/  (custom environment and configurations)
```
