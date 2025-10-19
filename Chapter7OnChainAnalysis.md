# Chapter 7: On-Chain Analytics
## Reading the Blockchain Itself - What Smart Money Can't Hide

On-chain analytics reads the blockchain directly - the immutable ledger recording every transaction since genesis. This is pure blockchain intelligence: tracking coin age, movement patterns, and wallet behavior. Unlike exchange data that can be faked, blockchain data doesn't lie. Understanding these metrics reveals what long-term holders and whales are actually doing.

---

## The Power of Blockchain Transparency

### Why On-Chain Data Is Different

**What Makes It Unique:**
- Every transaction permanently recorded
- Can't fake coin age or movement
- Whale wallets trackable forever
- Historical patterns clearly visible
- No reliance on exchange reporting

The blockchain is the ultimate source of truth. While exchanges can fake volume and traders can lie about positions, the blockchain records reality.

---

## Coin Days Destroyed (CDD): The Ancient Coins Metric

### Understanding CDD

**Formula:** CDD = (Number of coins moved) × (Days held unmoved)

```
Examples:
100 BTC held 1 day, then moved = 100 CDD
1 BTC held 100 days, then moved = 100 CDD
100 BTC held 365 days, then moved = 36,500 CDD
10 BTC held 10 years, then moved = 36,500 CDD

Why It Matters:
- Old coins moving = Long-term holders acting
- Spikes often precede major tops
- Low CDD = HODLers holding strong
- Can't be gamed or faked
```

### Reading CDD Patterns

**Sustained High CDD (>90th percentile):**
- Long-term holders taking profits
- Distribution to new entrants
- Often marks cycle tops
- Example: May 2021 saw 30-day average CDD spike 400%

**Single Massive Spike:**
```
January 2025 Example:
- 12-year dormant wallet activated
- Moved 500 BTC (2013 era coins)
- Created 1.8M CDD spike in one day
- Price dropped 8% within a week
- Ancient miner finally took profits
```

**CDD Divergence:**
- CDD rising while price sideways = Hidden distribution
- CDD falling while price rising = Strong hands accumulating
- CDD flat during volatility = Traders churning, holders unmoved

### Supply-Adjusted CDD

Accounts for Bitcoin's growing supply:
**Formula:** CDD ÷ Circulating Supply

This makes historical comparisons valid:
- 2013: 1M CDD meant more with 11M supply
- 2025: 1M CDD means less with 19.5M supply
- Supply-adjusted shows true relative impact

---

## HODL Waves: The Diamond Hands Map

### Understanding Coin Age Distribution

HODL Waves show what percentage of Bitcoin supply hasn't moved for various time periods:

```
Age Bands Breakdown:
< 24 hours: Day traders, arbitrage bots
1-7 days: Short-term traders
1-3 months: Swing traders
3-6 months: Position traders
6-12 months: Early investors
1-2 years: Committed holders
2-3 years: Strong hands
3-5 years: Diamond hands
5-10 years: OG Bitcoiners
> 10 years: Lost coins/Satoshi
```

### Reading Market Cycles Through HODL Waves

**Bottom Formation Pattern:**
```
2022-2023 Bear Market Example:
- < 3 month coins: Dropped from 25% to 15%
- > 1 year coins: Rose from 55% to 65%
- > 5 year coins: Stayed steady at 25%
Interpretation: Weak hands sold to strong hands
```

**Top Formation Pattern:**
```
2021 Bull Market Peak:
- < 3 month coins: Spiked from 15% to 30%
- 2-5 year coins: Dropped from 30% to 20%
- Pattern: Old holders distributing to new buyers
Signal: Cycle top forming
```

### Realized Cap HODL Waves

Weights coins by the price when they last moved:
- Shows the "cost basis" of different age groups
- More accurate than regular HODL waves
- Reveals profit/loss status of cohorts

---

## SOPR: The Psychology of Profit and Loss

### Spent Output Profit Ratio Explained

**Formula:** (Value when sold) ÷ (Value when acquired)

```
SOPR Interpretation:
> 1.0 = Coins sold in profit
< 1.0 = Coins sold at loss
= 1.0 = Break-even (key psychological level)

Market Psychology:
Bull Market: SOPR repeatedly bounces off 1.0
Bear Market: SOPR repeatedly rejected at 1.0
```

### Long-Term Holder SOPR (LTH-SOPR)

Filters for coins held >155 days:

```
LTH-SOPR Signals:
> 3.0 = Long-termers taking 3x+ profits (cycle top)
< 1.0 = Diamond hands capitulating (cycle bottom)
1.5-2.5 = Healthy profit-taking zone

Historical Examples:
Dec 2017: LTH-SOPR hit 5.0 (top)
Dec 2018: LTH-SOPR hit 0.6 (bottom)
April 2021: LTH-SOPR hit 4.2 (local top)
June 2022: LTH-SOPR hit 0.7 (bottom)
```

---

## UTXO Analysis: Following the Coins

### What Are UTXOs?

Unspent Transaction Outputs - Bitcoin's accounting method:
- Each UTXO is like a bill in your wallet
- Has a specific value and age
- Must be fully spent when used
- Change creates new UTXOs

### UTXO Age Bands

```
UTXO Realized Price Distribution:
< $20k: Bear market 2022 buyers
$20-30k: 2023 accumulation
$30-50k: 2024 rally buyers
$50-69k: 2024-25 FOMO buyers
> $69k: 2021 top buyers (underwater)
```

### UTXO Profit/Loss Metrics

**Percent of UTXOs in Profit:**
- > 95% = Extreme greed, everyone winning
- 70-95% = Bull market conditions
- 50-70% = Transitional phase
- < 50% = Bear market, majority underwater

---

## Network Health Metrics

### Active Addresses

```
Not All Addresses Are Equal:
- Daily active: 800k-1M (normal)
- > 1.2M = Heightened activity
- < 600k = Network dormancy

But Filter for Value:
- Addresses moving >$10k (whale activity)
- Addresses moving <$100 (retail/spam)
- First-time addresses (new adoption)
```

### Entity-Adjusted Metrics

Clusters addresses belonging to same entity:
- Removes exchange internal shuffling
- Shows real economic actors
- More accurate user count
- Currently ~300k daily entities

### Network Value Metrics

**NVT (Network Value to Transactions):**
```
Formula: Market Cap ÷ Transaction Value
Interpretation:
< 50 = Network undervalued vs usage
50-100 = Fair value range
> 100 = Overvalued/speculative
> 150 = Bubble conditions
```

**MVRV (Market Value to Realized Value):**
```
Formula: Market Cap ÷ Realized Cap
Historical Zones:
< 1.0 = Below aggregate cost basis (bear)
1.0-2.5 = Equilibrium zone
2.5-3.5 = Overheated
> 3.5 = Cycle top territory
```

---

## Miner Behavior: The Forced Sellers

### Understanding Miner Dynamics

Miners have ongoing costs and must sell:
- Electricity bills don't accept Bitcoin
- Hardware financing needs fiat
- Most sophisticated about timing
- Always forced sellers to some degree

### What Is Hash Rate?

**Simple Definition:** Hash rate = Total computing power of all Bitcoin miners combined

Think of it like a global competition where millions of computers are trying to solve puzzles to mine Bitcoin. Hash rate measures how many attempts per second the entire network makes. 

```
Higher hash rate = More miners/machines competing
Lower hash rate = Fewer miners/machines competing

Current Bitcoin hash rate: ~450 EH/s
That's 450 quintillion calculations per second!
```

**Why It Matters:**
- **Rising hash rate** = Miners investing in equipment (confident in Bitcoin's future)
- **Falling hash rate** = Miners shutting down (unprofitable, capitulating)
- **Security measure** = Higher hash rate makes network more secure

Hash rate follows price with a lag - when Bitcoin price drops, unprofitable miners shut off machines, hash rate falls. When price rises, mining becomes profitable, more miners join, hash rate rises.

### Reading Miner Data Despite Constant Selling

**Normal Baseline (The Noise):**
```
Typical Daily Operations:
- Miners produce ~900 BTC/day (current, post-2024 halving)
- Usually sell 50-70% immediately for operations
- Hold 30-50% as treasury/speculation
- This is normal - always happening
```

**What Actually Matters - CHANGES in Behavior:**
```
Accumulation Signal:
- Selling <40% of production (building reserves)
- Treasury balance increasing
- Hash rate stable/growing
= Miners bullish, can afford to hold

Distribution Signal:
- Selling 70-90% of production
- Treasury balance flat/declining slowly
= Miners cautious, selling to market

Capitulation Signal:
- Selling >100% of production (dipping into reserves)
- Treasury balance declining rapidly  
- Hash rate dropping (weakest miners offline)
= Miners in distress, forced liquidation
```

### Key Miner Metrics

**Hash Ribbons**
Tracks 30-day and 60-day mining hash rate MAs:
```
Capitulation Signal:
- 30-day MA crosses below 60-day MA
- Weak miners shutting down
- Historically marks bottoms

Recovery Signal:
- 30-day crosses back above
- Mining profitable again
- New accumulation phase begins
```

**Miner Position Index (MPI)**
```
Formula: (USD outflow from miners) ÷ (365-day MA)

Reading the MPI:
< 0 = Miners holding more than usual (bullish)
0-2 = Normal operational selling
> 2 = Excessive selling (bearish)
> 3 = Capitulation (extreme, often marks bottom)
```

**Miner Net Position Change**
Daily change in miner Bitcoin holdings:
```
Rising treasury = Accumulation (very bullish)
Flat treasury = Status quo operations
Declining slowly = Marginal stress
Declining rapidly = Capitulation

Real Examples:
2020-2021 Bull: Treasuries grew 50k → 80k BTC
2022 Bear: Miners sold 30,000 BTC in 6 months
- Treasuries hit multi-year lows
- Marked the cycle bottom
```

### Why Miner Capitulation Marks Bottoms

1. **Maximum Pain Point**: Miners are most informed (know mining economics)
2. **Forced Sellers Exhausted**: Once reserves gone, selling ends
3. **Survival of Fittest**: Only efficient miners remain
4. **Hash Recovery Signal**: Indicates profitability returning

When hash ribbons flip negative AND miners empty treasuries, it's historically been the best buying opportunity.

### Where to Get This Data

**Free Sources:**
- **LookIntoBitcoin.com**: Hash Ribbons chart
- **Blockchain.com**: Raw hash rate data
- **CryptoQuant Free**: Basic miner flows

**Professional ($30-40/month):**
- **Glassnode**: Complete miner suite with MPI
- **CryptoQuant Advanced**: Real-time alerts
- **ByteTree**: Miner's Rolling Inventory (MRI)

### The Smart Interpretation

**Don't Focus On:** Daily miner selling (too noisy)
**Do Focus On:** Monthly trend changes in:
- Percentage of production sold
- Treasury balance direction
- Hash rate trends

**Key Questions:**
- Are miners selling MORE or LESS than their usual 50-70%?
- Is their treasury GROWING or SHRINKING?
- Is hash rate RISING or FALLING?

The answers reveal if miners (despite being forced sellers) are optimistic or pessimistic. When the most informed forced sellers capitulate, it's often the absolute bottom.

---

## Wallet Cohort Analysis

### Tracking Different Player Types

**Shrimp (<1 BTC):** Retail investors
**Crab (1-10 BTC):** Serious retail
**Fish (10-100 BTC):** Wealthy individuals
**Dolphin (100-500 BTC):** Small funds
**Shark (500-1000 BTC):** Large traders
**Whale (1000-5000 BTC):** Institutions
**Humpback (>5000 BTC):** Exchanges/massive funds

### Supply Distribution Shifts

```
Current Distribution (Oct 2025):
Shrimp-Crab: 15% of supply (growing)
Fish-Dolphin: 30% of supply (stable)
Shark-Whale: 35% of supply (accumulating)
Humpback: 20% of supply (exchanges/funds)

Bullish when: Sharks/Whales accumulating
Bearish when: Sharks/Whales distributing
```

### The Plankton Indicator

When shrimp (<1 BTC) supply percentage rises rapidly:
- Retail FOMO has arrived
- Distribution phase active
- Local top forming

---

## Lost Coins and Dormancy

### Estimating Lost Bitcoin

```
Assumed Lost Categories:
- Satoshi's coins (1M BTC): Never moved
- 2009-2011 unmoved (2M BTC): Likely lost
- Known burn addresses: Provably lost
- Total estimated lost: 3-4M BTC

This means:
- Real supply ~16M not 19.5M
- Makes all metrics more bullish
- Increases scarcity premium
```

### Dormancy Flow

Tracks the average age of coins moved daily:
- High dormancy = Old coins waking up
- Low dormancy = Only young coins moving
- Spikes = Long-term holders acting

---

## Advanced On-Chain Patterns

### The Capitulation Cascade

```
Week 1: Miners start selling reserves
Week 2: 6-12 month holders capitulate
Week 3: 1-2 year holders break
Week 4: Entity count drops (users leaving)
Week 5: Maximum pain, bottom forms
```

### The Accumulation Staircase

```
Month 1: Whale addresses increase holdings
Month 2: Exchange balances decline
Month 3: CDD remains low despite volatility
Month 4: Old coins stop moving completely
Month 5: Entity count starts rising
Month 6: Breakout begins
```

### The Distribution Fingerprint

```
Phase 1: 5+ year coins start moving (CDD spikes)
Phase 2: Coins split to multiple addresses
Phase 3: Gradual flow to exchanges
Phase 4: SOPR rises above 2.0
Phase 5: Young coin percentage spikes
Phase 6: Price tops, cycle completes
```

---

## Limitations of On-Chain Analysis

### What It Can't Tell You

- **Exact price targets** (shows behavior, not levels)
- **Exchange internals** (off-chain activity hidden)
- **Derivative impacts** (futures/options off-chain)
- **Identity certainty** (addresses ≠ people)
- **Lost vs HODL** (dormant could be either)

### The Context Requirement

On-chain works best combined with:
- Market structure (separate chapter)
- Macro environment
- Technical levels
- Sentiment extremes

---

## Building Your On-Chain Framework

### Daily Health Check (5 minutes)
1. CDD trend (spiking or calm?)
2. SOPR level (profit or loss?)
3. Miner position (selling or holding?)

### Weekly Deep Dive (30 minutes)
1. HODL Waves shifts
2. Entity growth/decline
3. Whale accumulation/distribution
4. Dormancy patterns

### Monthly Cycle Review (1 hour)
1. MVRV position
2. NVT trends
3. Supply distribution changes
4. Lost coin adjustments

---

## Key Takeaways

**On-chain data is blockchain truth:**
- Can't be faked or manipulated
- Shows what holders actually do
- Reveals accumulation/distribution
- Catches tops and bottoms

**Most powerful metrics:**
1. **CDD** - When old coins move, pay attention
2. **HODL Waves** - Shows who's in control
3. **SOPR** - Psychology of profit/loss
4. **MVRV** - Aggregate profit/loss position
5. **Miner behavior** - The forced sellers

**The edge:** 
While everyone watches price charts and exchange data, on-chain shows what's happening beneath - whether diamond hands are accumulating or distributing. In a transparent blockchain, following smart money footprints is your alpha.

---

*Next Chapter: Market Intelligence - Exchange Flows, Derivatives, and Trading Signals*
