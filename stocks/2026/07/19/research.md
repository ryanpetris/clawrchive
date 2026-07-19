# Research Notes — July 19, 2026

## Dense Analysis and Marginal Context

### Moonshot AI Kimi K3 — Deeper Analysis

**Capability claims:**
- 2.8 trillion parameters, sparse MoE with 896 experts (16 active per token, ~1.8%)
- 1M token context window, native vision
- $3/M input tokens, $15/M output tokens (cached input at $0.30/M)
- GPQA Diamond: 93.5% (self-reported)
- Arena Frontend Code benchmark: #1
- Autonomous chip design: 48-hour run, 4mm² die, 13 modules, 1.46M standard cells, 0.277MB SRAM, INT4 MAC array, 100 MHz timing closure, 8,721 tokens/sec simulated throughput
- MiniTriton GPU compiler written from scratch

**Caveats:**
- All figures self-reported; weights not yet public (July 27)
- 45nm Nangate academic library — several generations behind 3nm/2nm where frontier chips live
- No physical fabrication — simulation results only
- Open-source toolchain (OpenROAD/OpenLane) already existed; U.S. government-funded
- Early independent evaluations flag elevated hallucination rates on factual tasks
- Unclear if licensed IP was embedded in the design

**Market reaction asymmetry:**
- CDNS -9.5%, SNPS -7.9% on Friday = ~$15.8B combined market cap loss
- ARM +2% — the market sold specific EDA software franchises, not chip design broadly
- Full weights July 27 = the real verification event. Until then, Friday's move is a bet on a curve, not a point.

**TSMC's agentic AI CPU comment:**
- CC Wei's observation that agentic AI is creating incremental CPU demand is important for the broader compute landscape
- If agents are CPU-bound (long-horizon, stateful, tool-call-intensive), the composition of data center silicon shifts
- This is incremental to GPU/accelerator spend, not a replacement
- The architecture war (x86 vs Arm vs RISC-V) is open, but TSMC captures the toll regardless
- Benficiaries: AMD (EPYC Venice on 2nm), Intel (Granite Rapids), ARM (Neoverse), custom silicon programs

### Leverage / Positioning Concerns

**Data points:**
- S&P 500 Momentum Index pulled back 11% in July vs <1% drop in S&P 500
- SOXL (Direxion 3x Semi Bull) down >50% from June peak, still up 200%+ YTD
- Hedge funds reduced AI infrastructure exposure (Goldman Sachs)
- Retail margin elevated; short-dated options volume high
- "People got way overextended on these names" — Walter Todd, Greenwood Capital

**Implication:** The January 2025 DeepSeek selloff was sharp but shallow. This feels different — longer duration, broader, with more leverage in the system. The 3x ETF drawdown is a canary.

### Alphabet Earnings Preview — Key Metrics

**Consensus:**
- Revenue: ~$116B (+21% YoY)
- Google Cloud: expected acceleration; previous quarter +28%
- EPS: consensus beat trajectory maintained (each 2026 beat so far)

**Key questions:**
1. Cloud growth trajectory — is the acceleration real?
2. Capex — Evercore's Mahaney expects 2027 guide could hit $275-325B
3. Gemini 3.5 Pro timeline — is the Bloomberg report accurate?
4. Search revenue resilience — AI Overviews monetization path
5. Moonshot K3 — does Alphabet's advantage in foundation models narrow?

**Risk:** If Gemini 3.5 is truly months behind, and Moonshot K3 is genuinely competitive (weights July 27), Alphabet's AI narrative faces a credibility gap. The stock is down 2.5% Friday and ~4.5% on Thursday on the Bloomberg report.

### Tesla Earnings Preview — Key Metrics

**Consensus:**
- Revenue: ~$27.6B (Q2)
- Auto gross margin (ex-credits): ~17-18%
- EPS: positive trajectory, beat in Q1

**Key questions:**
1. Robotaxi expansion — Miami launched, what's next?
2. Unsupervised FSD timeline — progress on HW3 upgrade?
3. AI chip development — internal silicon progress
4. Delivery numbers — Q2 deliveries showed improvement
5. SpaceX read-through — much of the attention is shifting to SpaceX

**Options pricing:** ~7% implied move by end of week. Going into earnings at ~15% YTD decline.

### Intel Earnings Preview — Q2 2026

**Consensus:**
- Revenue: ~$14.4B (+18% YoY)
- EPS: ~$0.21 (vs $0.019 last quarter, which was a big miss at $0.29 expected)
- Gross margin: Q1 was 41% (non-GAAP), expecting improvement

**Context:**
- Stock +160% YTD to ~$95
- Foundry yields at 85% for 18A
- Nvidia and OpenAI among foundry customers
- 18A wafer output ahead of internal projections
- 14A maturity outpacing 18A at similar stage
- Fab 34 buyout funded with $7.7B cash + $6.5B debt
- Q1 revenue $13.6B (above prior midpoint)

**Risk:** The stock has priced in a massive turnaround. Simply meeting expectations may not be enough. The market is looking for tangible evidence of sustainable financial improvement.

### Iran Conflict Timeline (Recent)

- **July 12:** Trump reinstates naval blockade on Iranian ports near Strait of Hormuz, imposes 20% toll on cargo. Oil crosses $75. Markets fall.
- **July 13:** OPEC lowers demand forecast. Oil stabilizes somewhat.
- **July 14:** Trump abandons 20% levy plan. But hostilities continue.
- **July 16:** Iran claims to have targeted US forces in Syria and Bahrain. Fragile truce fractures.
- **July 17:** Two US service members killed. Iran calls off interim peace deal. Oil surges again. 10Y yield drops to 4.537%.

**Key uncertainty:** The Strait of Hormuz handles ~20% of global oil traffic. Full closure would be an unprecedented supply shock. The IEA calls it "the greatest global energy security challenge in history." This is a non-trivial stagflation risk.

### ASML Guidance Raise

ASML raised annual guidance for the second time this year amid "extremely strong" order momentum. The company noted that demand for extreme ultraviolet lithography (EUV) machines is being driven by leading-edge logic and memory customers. This is consistent with TSMC's capex raise and the 2nm/N2 ramp.

### S&P 500 Earnings Season Scorecard

- Blended Q2 earnings growth: 24.7% YoY (above 23.3% expected at quarter end)
- 88% of S&P 500 companies exceeding estimates
- Magnificent 7: 31.1% earnings growth expected
- Excluding NVDA and MU: growth drops to 16.8%
- 86 S&P 500 companies reporting this week (3rd busiest week)

### Discarded / Lower-Priority Items

- **Apple:** No material update. Briefly overtook NVDA in market cap Thursday. No new product cycle catalysts imminent.
- **Palantir:** No breaking news. AI platform demand continues but no specific catalyst this week.
- **SMCI:** No major news. AI server and liquid cooling demand strong but stock is caught in the semi selloff.
- **Dell:** Was down 14% on July 15 on memory concerns. No new incremental catalyst.
- **KORU:** KOSPI in bear market despite 62% YTD gain. Korean semis (SK Hynix, Samsung) caught in the global selloff.
- **ORCL, CRM, ADBE, NOW, SNOW, PANW, CRWD, DDOG, NET, ANET, VRT, HPE:** No material updates for this rest-of-week briefing. Most are caught in the broader tech selloff but lack specific catalysts.

### Uncertainty Notes

- Moonshot K3's chip design claims are unverifiable until July 27. The entire EDA selloff is based on a claim with zero reproducibility.
- The Iran conflict trajectory is highly uncertain. "Peace deal" was called off, but negotiation windows may reopen.
- Alphabet Gemini 3.5 delay is based on a single Bloomberg report (Thursday). The actual timeline could be different.
- Intel's 85% foundry yield figure is self-reported. External verification is limited.
- The SOX bear market is defined by the 20% threshold from the June high. This is technical, not fundamental. The "bear market" label is a sentiment indicator, not a valuation signal.

### Key Levels to Watch

| Instrument | Bullish Break | Bearish Break | Current |
|------------|--------------|---------------|---------|
| S&P 500 | 7,600 | 7,300 | 7,458 |
| Nasdaq | 19,500 | 18,000 | ~18,900 |
| SOX | 5,000 | 4,000 | ~4,400 |
| 10Y Yield | 4.75% | 4.25% | 4.537% |
| WTI Crude | $80 | $65 | ~$75 |
| Gold | $4,200 | $3,800 | $4,005 |
| VIX | 25 | 18 | ~22 |