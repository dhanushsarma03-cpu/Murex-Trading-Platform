# MUREX Practice Tasks — Build 2026.09

Use the simulator with simulated data. Do not treat it as an official Murex/MX.3 system or live market feed.

## Task 1 — Trade Capture
Create a USD/INR FX Forward: Buy USD 1M @ 90, value date 11-Dec-2026. Validate and book it. Record the Trade ID.

## Task 2 — Amendment
Amend the same trade from USD 1M to USD 1.5M. Explain which modules should change and why.

## Task 3 — MTM
Assume the relevant current market rate is 92. Calculate the simplified MTM for a Buy USD 1M forward contracted at 90.

## Task 4 — Production Support
Use the Issue Simulator for VAL-2041. Write the first five investigation steps, the likely root-cause hypothesis, business impact, and three Given/When/Then acceptance criteria.

## Task 5 — Settlement
Investigate the failed settlement scenario. Identify the likely reference-data area, the downstream impact, and a practical workaround.

## Task 6 — Accounting
Explain Settlement vs Accounting for the FX Forward in 3–4 lines. Then identify the trade event that could trigger each downstream process.

## Task 7 — Configuration
Write a business rule: inactive counterparties must not be bookable for FX Forward. Add functional requirement and Given/When/Then acceptance criteria.

## Task 8 — Risk
Explain VaR, Expected Shortfall, PFE and a limit breach in business language. Identify which one is most directly related to counterparty exposure.

## Task 9 — Data / SQL
Using the SQL practice starter in Tools, identify the primary key and foreign-key relationships you would expect between TRADE, PRODUCT, COUNTERPARTY, POSITION and PNL.

## Task 10 — End-to-End BA Case
A trader changes Value Date from 11-Dec to 20-Dec. Trade, valuation and risk show 20-Dec, but settlement and accounting remain on 11-Dec. Identify the first investigation point, impacted teams, root-cause hypothesis, and regression tests.
