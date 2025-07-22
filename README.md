# Option-MarketMaking-in-stressed-Markets-
Master Thesis, Market Simulation

This repository contains the code and write-up for a Master’s thesis on high-frequency market-making under jump-diffusion dynamics.  The project integrates:

1. **A Least-Squares Monte Carlo (LSMC) PDE solver** (`DynamicPDE_LSMC`) for the zero-, first-, and second-order components of an optimal market-maker’s value function under diffusion and jump risk.  
2. **A suite of ABIDES agents** that plug in both jump-PDE–based and classical Avellaneda–Stoikov quoting rules into an agent-based limit-order-book simulation.  
3. **Benchmark agents** including zero-intelligence noise traders, mean-reverting value traders, momentum traders, and adaptive participation-of-volume liquidity providers.  
4. **A written Master’s thesis** (PDF) describing the mathematical derivations, numerical methods, simulation setup, and empirical results.
5. **Credit goes to** https://github.com/AlbertLin0327/Least-Square-Monte-Carlo.git, whose code for LSMC is used as a foundation to create the backward value function solver; furthermore ChatGPT that speeded up the code writing process.
Finally to https://github.com/jpmorganchase/abides-jpmc-public.git, whose framework was used to coduct the amrket simulation.
