# Research Notes — Tech Stock Rest-of-Week Outlook, June 21, 2026

## Calendar & Market Structure Notes

- **Juneteenth (June 19, Friday)** was a full U.S. stock market holiday (NYSE, Nasdaq closed). The market last traded Thursday, June 18.
- **Sunday, June 21** is never a trading day. This creates a three-day gap between the last close (Thu) and the next open (Mon).
- This week's market days: Mon 6/22 through Fri 6/26. Final day of the Sunday-Saturday week: Fri 6/26.
- The briefing week starts Sunday per the schedule rules. Since today is a non-market day before the final market day of the current week (Fri 6/26), the rest-of-week format applies (Rule 3).
- Next week begins Sunday June 28 (non-market) with first market day Monday June 29.

## Market Context — Thursday Close (June 18)

The Thursday June 18 session was a broad-based risk-on rally driven by:
1. **U.S.-Iran MoU entering force** — Pakistani PM Sharif confirmed the Strait of Hormuz reopening with "immediate effect"
2. **Nvidia raised forecast** — After-hours Thursday, NVDA +6.4% after the close
3. **Intel-Apple Trump announcement** — INTC +10.6%
4. **AI memory crunch** — Cook WSJ interview; MU +8.7%, Sandisk +11.5%

Key levels and sector performance from Thursday (per InteractiveCrypto data):
- XLK (Tech): +3.04% to $191.44
- INTC: +10.64%
- AMD: +4.86%
- AVGO: +4.70%
- NVDA: +2.95%
- AMZN: +2.90%
- XLY (Consumer Disc): +1.45%
- XLE (Energy): -1.65% (oil price decline)
- XLF (Financials): -0.89%
- XLV (Healthcare): -0.87%

## Nvidia Forecast Raise — Deep Dive

Sources: Credence Wire, Motley Fool, InteractiveCrypto

- Data-center revenue $38.6B vs consensus $36.5B — $2.1B beat
- Blackwell Ultra backlog >$180B — extends delivery schedules into 2027
- Hyperscalers (MSFT, AMZN, GOOGL, META) = 62% of DC revenue
- Sovereign AI (Saudi Arabia, Japan, France) = 11% (up from 4% prior year)
- Gross margins 75.1% — held despite ramp costs on new packaging lines
- FCF $14.8B; $9B stock buyback
- HBM supply remains primary constraint, not wafer output
- NVDA competing with customer ASIC programs (Google TPU, Amazon Trainium) via rack-scale liquid cooling reference designs reducing per-token cost 18%

**Bearish counterpoint (from the article itself):**
- $180B backlog may include double-ordering. Cancellation penalties exist after deposit stages, but specifics vary
- Export controls to China limit addressable market; Chinese domestic competitors gaining in advanced nodes
- AMD and custom ASICs winning inference workloads below NVDA's premium
- The bear case is that $180B reflects customer hoarding, not genuine demand

**From Motley Fool (Adria Cimino):**
- Nvidia annual shareholders meeting is June 24 (Tuesday). Historically, the meeting doesn't produce major announcements, and stock moves <2% in the following week
- External catalysts matter more: improving macro (Iran deal), SpaceX IPO excitement, broader AI enthusiasm

## Intel-Apple Foundry Deal — Deep Dive

Sources: TechTimes, AInvest, InteractiveCrypto

- Trump announced on Truth Social Thursday that Apple agreed to partner with Intel for U.S.-based chip design and manufacturing
- Neither Apple nor Intel has confirmed the deal with an official statement
- WSJ reported in May 2026 that Apple and Intel had reached a *preliminary* agreement after more than a year of negotiations
- Supply chain analyst Ming-Chi Kuo reported Intel began small-scale testing of Apple chips using 18A-P process node
- Dan Ives (Wedbush): Deal gives Apple "tool to reduce heavy reliance on TSMC"
- Apple CEO Tim Cook acknowledged iPhone 17 production "constrained" because TSMC couldn't produce enough A19 chips
- **Key nuance:** This would be a foundry deal only. Apple left Intel processors in 2020 and designs its own silicon. Apple's flagship A20 will likely still be TSMC-made
- Reports point to lower-volume/older parts first, not immediate shift of Apple's most advanced processors
- Timeline: 18A-P targeting risk production in 2026, volume production no earlier than ~2027-2028
- Trump's framing: Government's $8.9B CHIPS Act stake in Intel (9.9% equity, Aug 2025) now worth ~$60B — "most profitable single equity position in U.S. industrial policy history"
- INTC has roughly tripled YTD — "no longer a cheap reset trade"

**What to watch:**
- Formal Apple or Intel statement
- Which products/chip families involved
- 18A update: Intel's initial production progress
- Clear terms/deadlines

## Google Cloud Backlog

Source: Briefs.co

- Backlog $462B — roughly doubled in a single quarter
- Growth rate now tops AWS and Azure for the first time in years
- Search revenue accelerated for 4th straight quarter
- AI tools driving ad targeting and pricing precision
- Stock up just 16% YTD — trailing the Nasdaq despite these numbers
- Trades at ~25x forward earnings, near 5-year average
- CapEx stays elevated through 2026 and 2027
- Note: This article is from Briefs.co, an aggregator; cross-reference with Google's actual earnings release (Q2 2026 not yet reported)

## AI Memory Crunch

Source: TECHi

- Tim Cook told WSJ memory-driven price increases are "unavoidable" for Apple products
- Situation "has become unsustainable"
- TrendForce: Q2 NAND contract prices +70-75% QoQ, DRAM +58-63%
- AI servers eating wafer capacity — the crunch has reached consumer devices
- Sandisk closed +11.5% at all-time high; MU +8.7%
- MU reports June 24 — critical test
- **Note of caution:** Both stocks above analyst price targets as of June 18 close — Sandisk ~25% above $1,751 mean target, MU ~29% above $879 mean target
- Pure NAND play vs MU = DRAM + HBM + NAND

## AMD Competitive Position

Source: Alan Any, InteractiveCrypto

- MI355X beats Nvidia B200 on inference: ~30% higher throughput Llama 3.1 405B (AMD data), ~40% cheaper per-token (SemiAnalysis)
- MI400 specs: 432GB HBM4, 19.6 TB/s bandwidth, 2nm-class process
- But MI400 will compete against Nvidia Vera Rubin (288GB HBM4, ~13 TB/s), not B200
- Memory lead shrinks from 2.25x to ~1.5x against Rubin
- CUDA moat still dominant for training; OpenAI Triton compiler eroding it at edges
- Microsoft runs inference workloads on AMD hardware
- Definitive agreement with Rackspace signed June 16 for 30 MW AMD-based AI compute
- AMD closed at $537.37 (+4.86%) on Thursday

## Hyperscaler Cash-Flow Squeeze

Source: 24/7 Wall St (citing Epoch AI)

- AI capex growing ~70% annually; operating cash flow growing ~23%
- Aggregate FCF across major AI builders crosses zero around Q3 2026
- Individual projections:
  - **Oracle:** Already crossed (negative $24B FCF)
  - **Amazon:** Crossing now ($44B Q1 capex vs $26B OCF; long-term debt $119.1B)
  - **Alphabet:** ~Q1 2027 ($84.75B equity raise on June 1)
  - **Meta:** ~Q3 2027 (weighing share sale for $125-145B capex)
  - **Microsoft:** ~Q3 2028 (strongest balance sheet)
- Big Four combined capex: >$700B in 2026, potentially >$1T in 2027
- ~90% of OCF spent on capex in 2026, up from ~65% in 2025
- NVDA down 8% over past month despite blowout Q1 — market already pricing this in?

## Tesla — Musk Option Exercise

Source: GuruFocus

- Elon Musk exercised 2018 compensation plan options: 304M options → ~286M shares
- Paper gain: $116B
- Exercise price: $23.34/share; current TSLA ~$404.66
- Musk now holds ~700M shares = 19.9% of Tesla
- TSLA withheld ~17.53M shares ($7.1B) to cover exercise costs — cannot sell until ~2028
- P/E (TTM): 367.42 vs 5-year median of 107.37
- GuruFocus GF Value: $287.85 — stock is 39.1% overvalued per that metric
- No insider purchases in past 3 months; $21.7M insider sales
- TSLA -6.74% in June, -9.63% YTD

## Microsoft Restructuring

Source: Times of India (citing Business Insider)

- Nadella broke up decades-old senior leadership structure
- Three new groups: 5-person corporate leadership, 35-person engineering group, dedicated 3-person Copilot team
- Rajesh Jha (influential product leader) retiring July 1
- Yusuf Mehdi (35-year veteran, CMO) leaving
- Charlie Bell (ex-AWS architect) now listed as "engineer" with zero reports
- Mustafa Suleyman (DeepMind co-founder) overseeing narrower ~650-person superintelligence group
- Asha Sharma (Core AI exec) replaced Phil Spencer as Xbox head
- MSFT: -13.2% in June, -19.21% YTD — worst Mag 7 performer

## Dell/HPE/ServiceNow AI Infrastructure

Source: FolkNouveau

- Dell Q1: Record $43.8B revenue (+88% YoY); AI servers $16.1B (+757% YoY)
- FY27 revenue outlook raised to $165-169B; AI server target raised to $60B
- DELL $421 (+234% YTD); 24x adjusted earnings
- HPE: Revenue +18% to $9.3B; Juniper-acquisition networking +151.5%; 18x earnings
- ServiceNow: Q1 subscription rev $3.7B (+22%); Now Assist on track for $1.5B ACV

## U.S.-Iran Deal — Deeper Macro Context

Source: Al Jazeera, CNBC, BBC, Goldman Sachs, Investing.com

- MoU signed June 14 (announced Sunday), entered force June 18
- 60-day negotiation period (extendable) for nuclear details
- Max 14M bpd oil shortfall during war (IEA estimate)
- Brent peaked >$120; now ~$77-78
- Pre-war Brent: ~$70
- Goldman Sachs base case: Brent averaging $75 in 2027
- Goldman downside scenario: Brent $60 in 2027 (fast reopening + persistent demand loss + non-ME supply response)
- Asian markets (Nikkei, Kospi) hit all-time highs
- DXY weakened; 10Y yield fell to ~4.45%
- Minesweeping will take weeks to months
- Insurance premiums and tanker backlog unresolved
- Admiral Mark Montgomery estimate: 30-45 days to fully normalise flows

## SpaceX IPO and Cursor Acquisition

Source: Motley Fool, Founded

- SpaceX raised $85.7B in IPO (including greenshoe)
- $2.4T valuation — below Amazon, above Meta and Tesla
- Acquiring Cursor (AI coding startup) for $60B all-stock
- xAI (absorbed into SpaceX) losing money; Anthropic approaching profitability
- Planning $20B bond offering

## ETF/Market Structure Notes

- IBD data: All Mag 7 negative in June. MSFT worst (-13.2%), NVDA least bad (-2.8%)
- QQQE (equal-weight Nasdaq-100): +0.3% in June vs QQQ -4.02% — breadth improving
- NVDA and GOOGL best-positioned Mag 7 technically
- META and MSFT "look terrible, well below key moving averages" per IBD
- Broadcom June swoon: -14.5%
