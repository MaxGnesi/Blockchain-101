# Chapter 7: On-Chain Analytics
## Reading the Blockchain Itself - What Smart Money Can't Hide

On-chain analytics reads the blockchain directly - the immutable ledger recording every transaction since genesis. This is pure blockchain intelligence: tracking coin age, movement patterns, and wallet behavior. Unlike exchange data that can be faked, blockchain data doesn't lie. Understanding these metrics reveals what long-term holders and whales are actually doing with their coins.

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

**The On-Chain Framework:**
1. **Valuation Metrics** - Is Bitcoin cheap or expensive? (MVRV, NVT)
2. **Holder Behavior** - What are long-term holders doing? (CDD, HODL Waves)
3. **Profit/Loss Psychology** - Are people selling in profit or loss? (SOPR)
4. **Supply Dynamics** - Who owns what? (Wallet cohorts, lost coins)
5. **Network Health** - Is the network growing? (Active addresses, hash rate)

---

## MVRV: The Master Valuation Metric

### Understanding Market Value to Realized Value

**What MVRV Measures:**
- Market Value = Current market cap (price × supply)
- Realized Value = Sum of all coins valued at their last movement price
- MVRV = Market Value ÷ Realized Value

Think of Realized Value as the "aggregate cost basis" of all Bitcoin holders.

### Reading MVRV Zones

```
MVRV Historical Zones:
< 0.7 = Deep value (generational bottom)
0.7-1.0 = Below cost basis (accumulation)
1.0-1.5 = Near equilibrium 
1.5-2.5 = Profitable market (healthy)
2.5-3.5 = Overheated (caution)
> 3.5 = Extreme greed (cycle top)

Historical Extremes:
- Dec 2017: 4.8 (absolute top)
- Dec 2018: 0.72 (bottom)
- April 2021: 3.98 (local top)
- Nov 2021: 3.94 (cycle top)
- June 2022: 0.75 (bottom)
- Oct 2025: 2.1 (current - mid-range)
```

### Why MVRV Works

When MVRV = 2.0, the average holder is sitting on 100% profit. History shows markets reverse when average profits get too high (greed) or losses too deep (capitulation).

**MVRV Z-Score** (normalized version):
```
Formula: (Market Value - Realized Value) ÷ Standard Deviation
Z-Score > 7 = Extreme bubble
Z-Score 3-7 = Overvalued
Z-Score -0.5 to 3 = Fair value
Z-Score < -0.5 = Undervalued
```

---

## NVT: The Network Valuation Ratio

### Network Value to Transactions

Think of this as the P/E ratio for Bitcoin - comparing market cap to actual usage.

**Formula:** Market Cap ÷ Daily Transaction Value (in USD)

```
NVT Interpretation:
< 50 = Network undervalued vs usage
50-100 = Fair value range
100-150 = Overvalued/speculative
> 150 = Bubble conditions

Why It Matters:
- High NVT = Price outpacing usage (bearish)
- Low NVT = Usage exceeding price (bullish)
- Best used with 30-day moving average
```

### NVT Signal (More Responsive Version)

Uses 90-day MA of transaction value for smoother signal:
- Catches tops and bottoms faster than raw NVT
- Less noisy, more tradeable

---

## Coin Days Destroyed: When Old Coins Move

### Understanding CDD

**Formula:** CDD = (Number of coins moved) × (Days held unmoved)

```
Examples:
100 BTC held 1 day, then moved = 100 CDD
1 BTC held 100 days, then moved = 100 CDD
100 BTC held 365 days, then moved = 36,500 CDD
10 BTC held 10 years, then moved = 36,500 CDD

Why It Matters:
- Old coins rarely move without reason
- Spikes often precede major tops
- Low CDD = HODLers confident
- Can't be faked or gamed
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

### Supply-Adjusted CDD

Accounts for Bitcoin's growing supply:
**Formula:** CDD ÷ Circulating Supply

This makes historical comparisons valid across different eras.

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

### UTXO Realized Price Distribution

```
Current UTXO Cost Basis Bands:
< $20k: Bear market 2022 buyers (in profit)
$20-30k: 2023 accumulation (in profit)
$30-50k: 2024 rally buyers (in profit)
$50-69k: 2024-25 FOMO buyers (mixed)
> $69k: 2021 top buyers (underwater)
```

### UTXO Profit/Loss Metrics

**Percent of UTXOs in Profit:**
- > 95% = Extreme greed, everyone winning
- 70-95% = Bull market conditions
- 50-70% = Transitional phase
- < 50% = Bear market, majority underwater

---

## Miner Behavior: The Forced Sellers

### Understanding Miner Dynamics

Miners have ongoing costs and must sell:
- Electricity bills require fiat
- Hardware financing needs cash
- Most sophisticated about timing
- Always forced sellers to some degree

### Hash Rate and Mining Economics

**Hash Rate Basics:**
- Measures total network computing power
- Higher = more secure, more miners competing
- Currently ~450 EH/s (Oct 2025)

**Why It Matters:**
- Rising hash rate = Miners investing (bullish on future)
- Falling hash rate = Miners capitulating (unprofitable)
- Follows price with 3-6 month lag

### Reading Miner Behavior Changes

**Normal Baseline:**
```
Daily Production: ~900 BTC (post-2024 halving)
Typical Selling: 50-70% of production
Reserve Building: 30-50% held

This is the noise - always happening
```

**What Actually Matters - CHANGES:**
```
Accumulation Signal:
- Selling <40% of production
- Treasury balance increasing
- Hash rate stable/growing

Distribution Signal:
- Selling 70-90% of production
- Treasury slowly declining

Capitulation Signal:
- Selling >100% (dipping into reserves)
- Treasury rapidly declining
- Hash rate dropping
```

### Key Miner Metrics

**Hash Ribbons:**
- 30-day MA crosses below 60-day MA = Capitulation
- Cross back above = Recovery beginning
- Historically excellent bottom indicator

**Miner Position Index (MPI):**
```
Formula: (USD outflow from miners) ÷ (365-day MA)

< 0 = Miners holding (bullish)
0-2 = Normal selling
> 2 = Excessive selling (bearish)
> 3 = Capitulation (often marks bottom)
```

**Puell Multiple:**
```
Formula: (Daily mining revenue) ÷ (365-day MA)

< 0.5 = Miners in pain (bottom near)
0.5-1.0 = Accumulation zone
1.0-2.0 = Normal operations
2.0-4.0 = High profitability (take profits)
> 4.0 = Extreme profits (cycle top)
```

---

## Wallet Cohort Analysis

### Tracking Different Player Types

```
Size Classifications:
Shrimp (<1 BTC): Retail investors
Crab (1-10 BTC): Serious retail
Fish (10-100 BTC): Wealthy individuals
Dolphin (100-500 BTC): Small funds
Shark (500-1000 BTC): Large traders
Whale (1000-5000 BTC): Institutions
Humpback (>5000 BTC): Exchanges/massive funds
```

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

## Network Health Metrics

### Active Addresses

```
Daily Active Addresses:
800k-1M = Normal activity
> 1.2M = Heightened interest
< 600k = Network dormancy

But filter by transaction size:
- >$10k transfers = Whale activity
- <$100 transfers = Retail/spam
- First-time addresses = New adoption
```

### Entity-Adjusted Metrics

Clusters addresses belonging to same entity:
- Removes exchange internal shuffling
- Shows real economic actors
- Currently ~300k daily entities (Oct 2025)

### Network Growth Indicators

```
Healthy Growth Signs:
- New addresses growing steadily
- Entity count rising
- Transaction count increasing
- Average transaction value stable

Warning Signs:
- New addresses declining
- Entities leaving
- Transaction count dropping
- Only exchange shuffling remains
```

---

## Ethereum Staking Dynamics

### Understanding ETH 2.0 Lock-Up

Since the Merge, staking creates unique supply dynamics:

```
Total ETH Staked: ~36M (30% of supply)
Staking Yield: 3-5% APR

Supply Impact:
- Staked ETH = locked supply
- Withdrawal queue = selling friction
- Creates artificial scarcity
```

### Staking Metrics That Matter

**Staking Inflow/Outflow:**
- Large inflows = Long-term confidence
- Declining inflows = Yield seeking elsewhere
- Withdrawal queue spikes = Panic (rare)

**Validator Queue:**
- Entry queue long = FOMO building
- Exit queue long = Capitulation
- Both empty = Equilibrium

---

## Lost Coins and True Supply

### Estimating Lost Bitcoin

```
Provably Lost:
- Satoshi's coins: ~1M BTC
- 2009-2011 unmoved: ~2M BTC
- Burn addresses: ~200k BTC
- Total lost: 3-4M BTC

True Circulating Supply:
- Official: 19.5M BTC
- Minus lost: ~16M BTC
- Actually tradeable: ~13M BTC
```

### Dormancy Flow

Tracks average age of coins moved daily:
- Rising = Old coins waking up (distribution)
- Falling = Only young coins moving (accumulation)
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
Month 2: Young coin supply decreasing
Month 3: CDD remains low despite volatility
Month 4: Old coins stop moving completely
Month 5: Entity count starts rising
Month 6: Breakout begins
```

### The Distribution Fingerprint

```
Phase 1: 5+ year coins start moving (CDD spikes)
Phase 2: Coins split to multiple addresses
Phase 3: Young coin percentage rises
Phase 4: SOPR rises above 2.0
Phase 5: Whale wallets decreasing
Phase 6: Price tops, cycle completes
```

---

## Building Your On-Chain Framework

### Daily Health Check (5 minutes)
1. MVRV level (overvalued or undervalued?)
2. CDD trend (old coins moving?)
3. SOPR bounces (profit/loss behavior)
4. Miner flows (accumulating or selling?)

### Weekly Deep Dive (30 minutes)
1. HODL Wave shifts
2. Entity growth/decline
3. Whale accumulation/distribution
4. NVT ratio changes

### Monthly Cycle Review (1 hour)
1. MVRV Z-Score position
2. Realized Cap growth
3. Supply distribution changes
4. Lost coin adjustments

---

## Data Sources and Tools

### Free Resources
- **Glassnode Academy**: Learn the metrics
- **LookIntoBitcoin**: Key charts (MVRV, NVT)
- **Blockchain.com**: Basic network stats
- **CryptoQuant Free**: Limited metrics

### Professional Platforms ($30-40/month)
- **Glassnode**: Most comprehensive metrics
- **CryptoQuant**: Good alerts system
- **Santiment**: Social + on-chain
- **IntoTheBlock**: User-friendly

### Advanced Tools ($100+)
- **Chainalysis**: Institutional grade
- **Nansen**: Wallet labels and Smart Money
- **Dune Analytics**: Custom queries
- **CoinMetrics**: Academic rigor

---

## Limitations of Pure On-Chain Analysis

### What It Can't Tell You

- **Exact price levels** (shows behavior, not targets)
- **Exchange activity** (happens off-chain)
- **Derivative positioning** (futures/options off-chain)
- **Identity certainty** (pseudonymous addresses)
- **Lost vs HODL** (dormant could be either)

### The Context Requirement

On-chain works best combined with:
- Market structure (Chapter 8)
- Technical analysis (Chapter 4)
- Macro environment (Chapter 3)
- Sentiment analysis (Chapter 6)

---

## Key Takeaways

**On-chain data is blockchain truth:**
- Can't be faked or manipulated
- Shows what holders actually do
- Reveals accumulation/distribution
- Catches cycle tops and bottoms

**The most powerful metrics:**
1. **MVRV** - Overall market valuation
2. **CDD** - When old coins move, pay attention
3. **HODL Waves** - Shows who's in control
4. **SOPR** - Psychology of profit/loss
5. **Miner behavior** - The forced sellers

**The workflow hierarchy:**
1. Start with valuation (MVRV, NVT) - are we cheap or expensive?
2. Check holder behavior (CDD, HODL waves) - who's buying/selling?
3. Assess psychology (SOPR) - profit-taking or capitulation?
4. Monitor miners - are the forced sellers stressed?
5. Track network health - growing or shrinking?

**The edge:** 
While everyone watches price charts, on-chain analysis shows what's happening beneath the surface. The blockchain doesn't lie - it records every transaction permanently. Learning to read these tea leaves separates informed traders from exit liquidity.

---

*Next Chapter: Market Intelligence - Exchange Flows, Derivatives, and Trading Signals*
