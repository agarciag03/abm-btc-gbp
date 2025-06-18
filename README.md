# 🪙 Agent-Based Model: Bitcoin Trading Dynamics (BTC/GBP)

This project simulates Bitcoin trading dynamics against the British Pound (GBP) using an Agent-Based Modeling (ABM) approach. The model explores how heterogeneous trader behaviors and market interactions affect price evolution, volatility, and system-level outcomes in a simplified cryptocurrency market.

---

## 📌 Project Objectives

- Simulate the interactions between different types of agents (e.g., speculators, fundamentalists, trend followers).
- Observe how these behaviors influence BTC/GBP price fluctuations.
- Explore emergent phenomena such as bubbles, crashes, and volatility clustering.

---

## 🧠 Methodology

- **Model Type**: Agent-Based Model (ABM)
- **Agents**:
  - `FundamentalTraders`: Buy/sell based on perceived fair value.
  - `TrendFollowers`: Trade based on past price trends.
  - `NoiseTraders`: Add randomness and unpredictability.
- **Market Mechanism**: Order book simulation with matching engine.

---

## 🧰 Technologies Used

- Python  
- Matplotlib & Pandas for analysis and visualization

---

## 📊 Sample Visualizations

- BTC price over time
- Agent distribution by type and activity
- Volatility indicators

---

## 🧪 Model Assumptions & Limitations

This work aimed to simulate the BTC/GBP cryptocurrency market using an agent-based approach.  
The model was constructed using parameters derived from academic literature, simplified assumptions, and empirical data when available. While it offers valuable insights into trader behavior and emergent dynamics, it is important to acknowledge several modeling assumptions and their limitations:

- Agents place orders based on quantities, not specific bid/ask prices.
- Each agent can only make one order per day.
- Agents trade their full allocated wealth instead of choosing investment proportions.
- The agent population remains constant throughout the simulation.
- Exogenous shocks (e.g., a pandemic or geopolitical event) are not modeled.

These constraints simplify the implementation but reduce realism. Future improvements could include:

- Introducing a realistic order book with price-based bids and asks.
- Allowing multiple daily trades per agent.
- Enabling partial investment decisions based on agent strategy or risk appetite.
- Increasing agent diversity and population size.
- Incorporating real-world external events or news signals as exogenous variables.
