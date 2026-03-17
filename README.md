Inside the Ban: A Quantitative Autopsy of Jane Street's Trading Tactics in India
Author: Sandra (Yijia) Cai
Published: July 26, 2025
Status: Open Source, contributions welcome

Overview
In July 2025, Indian regulators issued a sweeping ban on Jane Street Group from participating in its securities markets. This paper offers a forensic, quantitative breakdown of the two-legged trading strategy that attracted SEBI's scrutiny — one of the most significant enforcement actions in modern derivatives trading.
The paper covers:

The mathematical model behind the index-lifting and gamma harvesting strategy
A step-by-step execution timeline: from delta positioning to profit realization
Quantitative P&L simulations across varying index moves
How SEBI's advanced surveillance infrastructure uncovered the manipulation
The legal framework and penalties invoked


Table of Contents

Context
Strategy Overview
Mathematical Model
Execution Illustration
Market Reaction & Sentiment
Gamma Convexity P&L Simulation
Legal Framework
How SEBI Uncovered the Manipulation


Key Findings

Jane Street used a two-legged strategy: aggressively purchasing illiquid NIFTY index constituents (Leg 1) to mechanically lift the index, while holding pre-positioned delta exposure in NIFTY options (Leg 2) that repriced due to the artificial index shift.
The strategy exploited gamma convexity, near-expiry ATM options are highly sensitive to small index moves, generating outsized P&L relative to the manipulation cost.
SEBI detected the scheme through cross-market orderbook correlation, Granger-causality analysis, and recurring "strategy fingerprints" in high-frequency trade data.
Penalties included an asset freeze of 48.4 billion rupees (~$570M), bank account locks, and full market access prohibition.


How to Read / Cite
The full paper is available as a PDF in this repository.
To cite this work:
Cai, Sandra (Yijia). "Inside the Ban: A Quantitative Autopsy of Jane Street's Trading 
Tactics in India." July 26, 2025.

Contributing
I believe complex financial events deserve rigorous, public analysis, and good ideas improve through collaboration.
Pull requests are warmly welcome! You can contribute by:

Correcting the mathematics: If you spot errors in the formulas or simulations
Improving clarity: Simplifying explanations or adding intuition
Updating legal analysis: As regulatory proceedings develop
Adding new simulations: Extending the P&L models or backtesting the strategy
Translating: Making the paper accessible in other languages

Please open an Issue first if you're proposing a significant change, so we can discuss it before you invest time writing.

License
This work is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0).
You are free to share and adapt this material for any purpose, provided appropriate credit is given.

Best,
Sandra (Yijia) Cai
