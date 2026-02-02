# Solana AI Agent Market Maker 

This agent showcases an ai market maker agent on Raydium, Orca, Meteora, OpeenBook, Drift, Manifest. The agent guides the user to setup basic two-sided quotes on markets.
This agent also can be extended with more functionality 

<img width="799" height="694" alt="image" src="https://github.com/user-attachments/assets/17b99d12-7fd6-4bc5-b8a5-89f5816a7bf2" />

## Supported DEXs
-Orca:
 - orcaOpenCenteredPositionWithLiquidity
 - orcaOpenSingleSidedPosition
 - orcaClosePosition
 - orcaCreateCLMM
   
-Raydium:
 - raydiumCreateAmmV4
 - raydiumCreateClmm
 - raydiumCreateCpmm

-Meteora:
 - createMeteoraDlmmPool
 - createMeteoraDynamicAMMPool

-OpenBook:
 - openbookCreateMarket

-Drift (Perpetuals & Spot):
 - driftPerpTrade
 - swapSpotToken
 - depositIntoDriftVault

-OKX DEX (Aggregator):
 - executeSwap
 - getQuote

## Key Features

- Market selection and configuration (pair, tick size, lot size)
- Quote parameters (spread, size, max inventory, refresh cadence)
- Wallet and keypair setup
- Risk constraints and order lifecycle management (replace, cancel, rebalance)
- The agent continuously monitors:
- Order book state (OpenBook / Drift / Manifest)
- AMM pool state and price curves (Raydium, Orca, Meteora)
- Position inventory and PnL
- Latency, failed transactions, and on-chain confirmations
- The architecture is modular and extensible, allowing additional functionality such as:
- Volatility-adaptive or ML-based spread models
- Cross-venue arbitrage detection and execution
- Inventory-aware skewing and hedging
- Dynamic fee and slippage optimization
- Automated risk shutdowns and circuit breakers
- Strategy plugins for different market regimes


