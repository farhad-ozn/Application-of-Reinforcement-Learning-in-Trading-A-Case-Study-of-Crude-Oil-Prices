# Application of Reinforcement Learning in Trading: A Case Study of Crude Oil Prices

We explore the application of the **reinforcement learning (RL)** technique in developing intelligent and adaptive trading strategies for volatile energy markets such as crude oil. Given the complexity and high-frequency fluctuations driven by geopolitical and seasonal factors, energy markets offer a rich environment for sequential decision-making.  

In this work, we review the fundamentals of Reinforcement Learning and build algorithms that, when implemented, earn more profit. We propose an RL approach to the energy stock market from scratch, developing an agent-environment interface, and compare the performance of RL agents, including **Deep Q-Network (DQN)** and **Policy Gradient (PG)**, against classical momentum-based baseline techniques, namely **Moving Average Convergence Divergence (MACD)** indicator, and **Simple Moving Average (SMA) crossover**.  

Unlike other works that use broad sets of stocks across different asset classes, in this work we only focus on one energy asset (**Brent crude oil futures**) to investigate more deeply and derive meaningful insights. The training period was from **2010–2023**, and we tested the algorithm from **2023 to July 2025**. Test results showed RL algorithms are capable of deciding what to do at each moment to reach the highest profit possible.  

For RL methods, our approach considers **discrete action spaces** and uses **ATR position sizing** to dynamically adjust the size of positions based on current market conditions. The study involved training **DQN agents** and a **Policy Gradient method (REINFORCE) agent** to maximise long-term returns while accounting for real-world constraints like transaction costs and risk management.  

In our study, **SMA** and **MACD** provided interpretable but flat performance, while RL agents, particularly **DQN**, demonstrated superior adaptability to changing market regimes. **DQN dominated both classical benchmarks and PG** in cumulative P&L, drawdown control, and terminal wealth, establishing it as the strongest candidate strategy within our experimental framework.  

**Keywords:** Reinforcement learning, DQN, Policy Gradient RL, SMA Crossover, MACD indicator, Algorithmic trading
