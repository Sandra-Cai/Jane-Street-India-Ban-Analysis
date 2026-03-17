# Inside the Ban: A Quantitative Autopsy of Jane Street's Trading Tactics in India

**Author:** Sandra (Yijia) Cai  
**Published:** July 26, 2025  
**Status:** Open Source, contributions welcome

---

## Overview

In July 2025, Indian regulators issued a sweeping ban on Jane Street Group from participating in its securities markets. This paper offers a forensic, quantitative breakdown of the two-legged trading strategy that attracted SEBI's scrutiny, one of the most significant enforcement actions in modern derivatives trading.

The paper covers:

- The mathematical model behind the index-lifting and gamma harvesting strategy
- A step-by-step execution timeline: from delta positioning to profit realization
- Quantitative P&L simulations across varying index moves
- How SEBI's advanced surveillance infrastructure uncovered the manipulation
- The legal framework and penalties invoked

---

## Table of Contents

1. [Context](#1-context)
2. [Strategy Overview](#2-strategy-overview)
3. [Mathematical Model](#3-mathematical-model)
4. [Execution Illustration](#4-execution-illustration)
5. [Market Reaction & Sentiment](#5-market-reaction--sentiment)
6. [Gamma Convexity P&L Simulation](#6-gamma-convexity-pl-simulation)
7. [Legal Framework](#7-legal-framework)
8. [How SEBI Uncovered the Manipulation](#8-how-sebi-uncovered-the-manipulation)

---

## Key Findings

- Jane Street used a **two-legged strategy**: aggressively purchasing illiquid NIFTY index constituents (Leg 1) to mechanically lift the index, while holding pre-positioned delta exposure in NIFTY options (Leg 2) that repriced due to the artificial index shift.
- The strategy exploited **gamma convexity**, near-expiry ATM options are highly sensitive to small index moves, generating outsized P&L relative to the manipulation cost.
- SEBI detected the scheme through cross-market orderbook correlation, Granger-causality analysis, and recurring "strategy fingerprints" in high-frequency trade data.
- Penalties included an **asset freeze of 48.4 billion rupees (~$570M)**, bank account locks, and full market access prohibition.

---

## How to Read / Cite

The full paper is available as a PDF in this repository: [`Inside_the_Ban.pdf`](./Inside_the_Ban__A_Quantitative_Autopsy_of_Jane_Street_s_Trading_Tactics_in_India.pdf)

To cite this work:
```
Cai, Sandra (Yijia). "Inside the Ban: A Quantitative Autopsy of Jane Street's Trading 
Tactics in India." July 26, 2025.
```

---

## Contributing

Pull requests are warmly welcome! See [CONTRIBUTING.md](./CONTRIBUTING.md) for full guidelines.

---

## License

This work is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

---

## Author

**Sandra (Yijia) Cai**  
Founder @ Plurall AI | Neo Scholar Finalist  
[LinkedIn](https://www.linkedin.com/in/sandracai) · [GitHub](https://github.com/Sandra-Cai)
