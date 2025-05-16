# 🧠 Multi-Agent System for Optimization with Q-Learning

> A cooperative reinforcement-driven multi-agent system using Genetic Algorithm, Tabu Search, and Simulated Annealing.

---

## 📌 Key Features

- 🔁 **Genetic Algorithm** agent with crossover and Q-guided local mutation  
- 🧊 **Simulated Annealing** agent using probabilistic acceptance of worse solutions  
- ⛔ **Tabu Search** agent with adaptive memory-based exploration  
- 🧠 **Q-Learning** reinforcement guiding agent behavior over time  
- 📊 Visual performance tracking and reward heatmaps  
- 👥 Agents can cooperate or compete based on configurable strategies  

---

## 🚀 Getting Started

### 🔧 Prerequisites

Make sure Python 3.8+ is installed. Then install the required packages:

```bash
pip install matplotlib numpy
```

### ▶️ Run the Notebook

```bash
jupyter notebook multi_agent_system.ipynb
```

---

## 🧠 How It Works

Each agent explores the solution space with its own search strategy:

- **GA Agent** evolves populations using crossover and Q-guided mutation  
- **SA Agent** performs stochastic descent with simulated annealing acceptance  
- **Tabu Agent** uses a memory list to avoid revisiting previous solutions  

Each agent learns the best moves using a Q-table based on reward feedback from fitness gains.

---

## 📚 Future Improvements

- [ ] Add interactive GUI  
- [ ] Extend to real-world datasets  
- [ ] Add new agents (e.g., Ant Colony, PSO)  
- [ ] Add asynchronous multi-agent communication  

---

## 🤝 Contributing

Contributions are welcome! Please fork this repo and submit a pull request.  
For major changes, open an issue to discuss your idea.

---

## 📄 License

Distributed under the MIT License.

---

## ✨ Acknowledgments

Inspired by hybrid optimization and reinforcement learning research.  
Thanks to the academic community for resources and open-source support!
