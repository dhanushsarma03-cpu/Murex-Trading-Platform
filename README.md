# MUREX Trading Platform

An independent MUREX-style enterprise trading and risk practice environment for Business Analyst learning.

## Learning modules

- Front Office / Trade Capture / Trade Blotter
- Trade lifecycle: Capture → Validate → Enrich → Price → Book → Confirm → Settle → Account → Risk/P&L
- Market Data: rates, FX, credit, equity, commodities and volatility
- Pricing & valuation: curves, models, PV and sensitivities
- Risk: VaR, limits, stress testing and exposure
- P&L and attribution
- Confirmations and matching
- Settlement and nostro operations
- Collateral and margin
- Accounting and trade events
- Reference data and product mapping
- Reports and management information
- Operations/service monitoring
- BA Issue Simulator for root-cause analysis, SQL/data tracing, requirements and acceptance criteria
- BA Learning Lab

## Running locally

This version is a zero-build static web application. Open `index.html` in a browser or serve the repository directory with any static HTTP server.

Example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Important

The application uses simulated practice data. It is an independent learning implementation and is not connected to an official MUREX/MX.3 installation, bank production environment, or live market feed.
