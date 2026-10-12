Comparative Equity Valuation & Macro-Financial Analysis: NVIDIA (NVDA) vs. Broadcom (AVGO)
Executive Summary
This project presents a rigorous quantitative and structural valuation framework comparing two major pillars of artificial intelligence infrastructure and semiconductor design: NVIDIA Corporation (NVDA) and Broadcom Inc. (AVGO).

By integrating live financial market data, macroeconomic cost-of-capital estimates (WACC), and multi-year Free Cash Flow (FCF) projections, this model examines how distinct capital structures and high-growth trajectories impact intrinsic firm value under shifting macroeconomic regimes.
Methodology & Technical Architecture
The valuation model is structured in Python using automated financial extraction and corporate finance theory:

Data Pipeline: Pulls real-time balance sheets, market capitalizations, and equity betas directly via yfinance.

Cost of Capital (WACC): Dynamically computes the Weighted Average Cost of Capital by combining the Capital Asset Pricing Model (CAPM) for Cost of Equity with capital structure weightings for Debt and Equity.

Intrinsic Valuation Engine: Implements a 5-year explicit Discounted Cash Flow (DCF) projection paired with a Gordon Growth Method Terminal Value calculation.
Key Findings & Comparative ResultsMetricNVIDIA (NVDA)Broadcom (AVGO)Economic Intuition / TakeawayCurrent Beta2.221.48NVIDIA displays higher historical price volatility and hyper-growth sensitivity.WACC (%)16.36%12.02%Higher equity risk weighting and beta drive a steeper discount rate for NVIDIA.Enterprise Value ($B)$868.95B$407.94BReflects the relative scale of capital structures and asset bases.Implied Share Price ($)$35.97$75.20Baseline intrinsic valuation under current template parameters.Market Share Price ($)$226.32$354.73Highlights market growth expectations versus baseline modeling inputs.
macroeconomic & Strategic Insights
Monetary Policy Sensitivity: Because high-growth technology equities derive a massive share of their terminal value from far-future cash flows, shifts in the risk-free rate (driven by central bank policy adjustments) disproportionately compress valuations for high-beta firms like NVIDIA.

Diversification vs. Pure Play: Broadcom’s hybrid model—spanning enterprise software integration (VMware) and custom accelerated computing silicon (XPUs)—yields a more stable cash-flow profile and a lower cost of capital compared to NVIDIA’s concentrated GPU ecosystem.
