# WIDS - Reinforcement Learning in Trading

Welcome to the **Winter in Data Science (WIDS) - RL in Trading** repository. This project contains a collection of notebooks, assignments, and implementations designed to build a strong foundation in Reinforcement Learning (RL) and its application to trading and decision-making problems.

## 📂 Repository Structure & Curriculum

The content is organized into a 4-week curriculum, progressing from data manipulation tools to core RL algorithms, environment modeling, and finally, a full trading agent implementation.

### 🔹 Week 1: Data Science Foundations
*Focus: Mastering the Python data stack essential for Quant/RL workflows.*
- **Numpy:** Vectorization, array manipulation, and broadcasting.
- **Pandas:** Data loading, cleaning, filtering, and analysis.
- **Matplotlib:** Data visualization and plotting trends.
- **Files:** `Numpy_assignment.ipynb`, `Pandas_and_Matplotlib.ipynb`

### 🔹 Week 2: The Bandit Problem
*Focus: Solving the Exploration vs. Exploitation dilemma.*
- Introduction to the Multi-Armed Bandit problem.
- Implementation of key agents:
  - **Greedy Agent:** Pure exploitation.
  - **$\epsilon$-Greedy Agent:** Balancing random exploration with exploitation.
  - **Optimistic Initial Values:** Encouraging early exploration.
  - **Upper Confidence Bound (UCB):** Measuring uncertainty to guide decisions.
- **Files:** `work_on_bandits.ipynb`

### 🔹 Week 3: Markov Decision Processes (MDPs)
*Focus: Modeling the world and defining the rules of the game.*
- Formalizing RL problems using **States (S)**, **Actions (A)**, **Rewards (R)**, and **Transitions (P)**.
- Manual construction of MDP dictionaries for custom environments:
  - **Bandit Walk:** Deterministic transitions.
  - **Slippery Walk:** Stochastic transitions with probability distributions.
  - **Frozen Lake:** Grid-world dynamics with boundary checks and slippery movement.
- **Files:** `Assignment_3.ipynb`

### 🔹 Week 4: Q-Learning Trading Agent (Final Project)
*Focus: Applying tabular RL to real-world financial markets.*
- **Custom Environment:** Building a `TradingEnv` class to simulate stock trading logic (Buy, Sell, Hold).
- **Q-Learning Algorithm:** Implementing the full Q-Learning update loop using the Bellman equation.
- **Market Data:** Fetching real historical data (e.g., AAPL) using `yfinance` to train the agent.
- **Evaluation & Benchmarking:** Testing the trained agent without exploration and comparing its ROI against a standard "Buy and Hold" baseline.
- **Files:** `Final_Project.ipynb`

---

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Hani-237/WIDS---RL-in-Trading.git](https://github.com/Hani-237/WIDS---RL-in-Trading.git)
