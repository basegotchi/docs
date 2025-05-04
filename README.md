
# Basegotchi Whitepaper (English)

## Introduction

Basegotchi is an on-chain farming simulation game built on the Base network. Players buy land, raise animals, and earn passive income with $GOTCHI tokens. The game combines a sustainable economy with an enjoyable gaming experience.

Our goal is to provide a fun and sustainable game model that offers both entertainment and earnings for players.

## Token Economy

### $GOTCHI Token

- Token initial price is set at **0.001 USD**.
- Use cases for the token:
  - Buying animals
  - Upgrading land
  - Claiming production rewards and in-game spending

### Token Price and Purchasing Power

**Token Price Formula:**

\[
1\ \text{USD} = 1,000\ \text{GOTCHI}
\]

\[
1\ \text{GOTCHI} = 0.001\ \text{USD}
\]

## Land System

Players can upgrade their land to increase animal slot capacity.

| Level | Slots | Production Multiplier | Upgrade Cost (Token) | USD Equivalent |
|-------|-------|-----------------------|---------------------|----------------|
| Level 1 | 2 | 0.015 | - | - |
| Level 2 | 4 | 0.020 | 20,000 | 20 USD |
| Level 3 | 6 | 0.030 | 35,000 | 35 USD |
| Level 4 | 8 | 0.040 | 50,000 | 50 USD |

### Production Multiplier Calculation

\[
\text{Total Production} = \text{Hourly Production} \times \text{Land Multiplier}
\]

## Animal System

Each animal is priced to amortize its cost over **15 days**.

\[
15\ \text{Days} = 360\ \text{Hours}
\]

### Hourly Production Formula

\[
\text{Hourly Production} = \frac{\text{Token Price}}{360}
\]

### Animal Prices and Hourly Production

| Animal | Price (USD) | Price (Token) | Hourly Production (Token/hour) |
|--------|-------------|---------------|---------------------------------|
| Chick | 4.50 USD | 4,500 | 12.50 |
| Chicken | 13.50 USD | 13,500 | 37.50 |
| Duck | 20.25 USD | 20,250 | 56.25 |
| Pig | 33.75 USD | 33,750 | 93.75 |
| Cow | 47.25 USD | 47,250 | 131.25 |

#### Example Production (Chicken)

\[
\frac{13,500}{360} = 37.5\ \text{Token/hour}
\]

Animals produce tokens only when placed on land. Production does not disappear if unclaimed.

## Production Model and Amortization

Each animal must recover its cost within the set amortization period.

### Daily Production Formula

\[
\text{Daily Production} = \text{Hourly Production} \times 24
\]

### Amortization Period Formula

\[
\text{Amortization Period (Days)} = \frac{\text{Token Price}}{\text{Daily Production}}
\]

#### Example (Chicken)

\[
37.5 \times 24 = 900\ \text{Token/day}
\]

\[
\frac{13,500}{900} = 15\ \text{Days}
\]

## Liquidity Plan (LP)

| ETH | GOTCHI Token | USD Equivalent |
|-----|--------------|----------------|
| 0.25 ETH | 450,000 GOTCHI | 450 USD |
| 0.5 ETH | 900,000 GOTCHI | 900 USD |
| 1 ETH | 1,800,000 GOTCHI | 1,800 USD |

### Uniswap v2 LP Calculation

ETH price is set at **1,800 USD**.

\[
1\ \text{ETH} = 1,800\ \text{USD} = 1,800,000\ \text{GOTCHI}
\]

Recommended initial liquidity:

\[
0.5\ \text{ETH} + 900,000\ \text{GOTCHI} = 900\ \text{USD}
\]

## Sustainability and Future Plans

- Animal and land pricing are balanced for long-term economic stability.
- Seasonal events and NFT integrations are planned.
- Token burn mechanisms and staking will be used to maintain tokenomics balance.

## Vision

Basegotchi aims to build a social and economic community on the Base network. Players will compete in a friendly way while becoming part of a larger collective ecosystem.

"Farms are forever — and so is $GOTCHI."

---

This document has been prepared to explain Basegotchi's game economy, detailed mathematical model, and sustainable structure.
