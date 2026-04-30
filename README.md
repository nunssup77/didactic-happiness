# On-chain Smart Money & Arbitrage Tracker (built with SurfAI)
## 1. Project Overview
**Zombie Revival Scanner** is an AI-built on-chain tracking tool that detects bottom-accumulation signals of Smart Money. It tracks accumulation across major networks (ETH, SOL, BSC, AVAX, ARB) to discover undervalued tokens and analyzes macro indicators like BTC Dominance to find the optimal entry timing.
## 2. Core Prompt / Logic
*   **Workflow:** Data Fetching -> Smart Money Filtering -> Arbitrage Gap Calculation -> Alert Generation
*   **AI Prompt Base:** "Track wallets with high win rates over the last 30 days. Alert when these wallets accumulate tokens with a market cap under $10M that have been flat for over a year..."
## 3. Deployed Demo
*   **Link:** https://top-zombie-revival-projects-8bd3b1.surf.computer/
## 4. The Limitation & Why Arcium is Needed
While this tool perfectly calculates arbitrage opportunities, executing these strategies on public mempools leaves users vulnerable to MEV bots. If the execution path is exposed, the user's alpha strategy is immediately front-run.
This is exactly why the **Arcium Private DeFi** and **Confidential Computing** infrastructure is necessary. By encrypting the smart contract execution, Arcium acts as an essential shield to protect this AI-generated trading logic from being exploited.
