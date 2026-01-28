# Solana AI Market Maker Agent

This agent showcases an ai market maker agent on Raydium, Orca, Meteora, OpeenBook, Drift, Manifest. The agent guides the user to setup basic two-sided quotes on markets.

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

- **Automated Quoting**: The agent automatically refreshes quotes on an interval.
- **Reducing Complexity**: Designed to abstract away parameters for setting up market making.
- **Random Model**: The market making introduces randomness to prevent front running or other negative botting behaviors.


