# Basegotchi Whitepaper

## Introduction

Basegotchi is an on-chain farming simulation game built on the Base network. Players buy land, raise animals, and earn passive income with \$GOTCHI tokens. The game combines a sustainable economy with an enjoyable gaming experience.

Our goal is to provide a fun and sustainable game model that offers both entertainment and earnings for players.

## Token Economy

### \$GOTCHI Token

* Token price benchmark is set at **1 ETH = 1,223,150 GOTCHI**.
* Use cases for the token:

  * Buying animals
  * Upgrading land
  * Claiming production rewards and in-game spending

### Token Price and Purchasing Power

**Token Price Reference:**

1 ETH = 1,223,150 GOTCHI

## Land System

Players can upgrade their land to increase animal slot capacity.

| Level   | Slots |Price (ETH) |
| ------- | ----- | ----------- |
| Level 1 | 2     |0.01        |
| Level 2 | 4     |0.02        |
| Level 3 | 6     |0.034       |
| Level 4 | 8     |0.049       |




### Hourly Production Formula

Hourly Production = Token Price / 96

### Animal Prices and Hourly Production

| Animal  | Price (ETH) | Price (Token) | Hourly Production (Token/hour) | Land Requirement |
| ------- | ----------- | ------------- | ------------------------------ | ---------------- |
| Chick   | 0.00368     | 4,500         | 180.00                         | L1               |
| Chicken | 0.01104     | 13,500        | 270.00                         | L1               |
| Duck    | 0.01308     | 16,000        | 1800.00                        | L2               |
| Pig     | 0.02760     | 33,750        | 5623.00                        | L3               |
| Cow     | 0.07850     | 96,000        | 28000.00                       | L4               |

#### Example Production (Chicken)

13,500 / 96 = 140.625 Token/hour → updated to 270 Token/hour

Animals produce tokens only when placed on land. Production does not disappear if unclaimed.

## Production Model and Amortization


#### Example (Chicken + L1 Land)

**Chicken + L1 Land:**

* Chicken Price: 13,500 Tokens
* Land Price: 0.01 ETH = 12,231.5 Tokens
* Total Cost: 25,731.5 Tokens
* Daily Production: 270 × 24 = 6,480 Tokens
* ROI: 25,731.5 / 6480 ≈ 3.97 Days

#### Example (2 Chicken + 2 Duck with L1 + L2 Land)

* Chicken Cost: 13,500 × 2 = 27,000 Tokens
* Duck Cost: 16,000 × 2 = 32,000 Tokens
* Land Cost: L1 (0.01 ETH) + L2 (0.02 ETH) = 0.03 ETH = 36,693 Tokens
* Total Setup Cost: 27,000 + 32,000 + 36,693 = 95,693 Tokens
* Daily Production:

  * 2 Chicken × 270 × 24 = 12,960 Tokens
  * 2 Duck × 1800 × 24 = 86,400 Tokens
  * Total = 99,360 Tokens/day
* ROI: 95,693 / 99,360 ≈ 0.96 Days

#### Example (Pig)

**6 Pig with L1 + L2 + L3 Land:**

* Pig Cost: 33,750 × 6 = 202,500 Tokens
* Land Cost: L1 (0.01 ETH) + L2 (0.02 ETH) + L3 (0.034 ETH) = 0.064 ETH = 78,281.6 Tokens
* Total Setup Cost: 202,500 + 78,281.6 = 280,781.6 Tokens
* Daily Production:

  * 6 Pig × 5623 × 24 = 810,912 Tokens
* ROI: 280,781.6 / 810,912 ≈ 0.35 Days

#### Example (Cow)

**8 Cow with L1 + L2 + L3 + L4 Land:**

* Cow Cost: 96,000 × 8 = 768,000 Tokens
* Land Cost: L1 (0.01 ETH) + L2 (0.02 ETH) + L3 (0.034 ETH) + L4 (0.049 ETH) = 0.113 ETH = 138,215 Tokens
* Total Setup Cost: 768,000 + 138,215 = 906,215 Tokens
* Daily Production:

  * 8 Cow × 56,000 × 24 = 5,376,000 Tokens
* ROI: 906,215 / 5,376,000 ≈ 0.1685 Days (≈ 4 hours)

## Sustainability and Future Plans

* Animal and land pricing are balanced for long-term economic stability.
* Seasonal events and NFT integrations are planned.
* Token burn mechanisms and staking will be used to maintain tokenomics balance.

## Vision

Basegotchi aims to build a social and economic community on the Base network. Players will compete in a friendly way while becoming part of a larger collective ecosystem.

"Farms are forever — and so is \$GOTCHI."

---

This document has been prepared to explain Basegotchi's game economy, detailed mathematical model, and sustainable structure.
