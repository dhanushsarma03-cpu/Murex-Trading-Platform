# Murex BA Practice — Fresh Sequential Tasks

The simulator starts with **zero student-created trades**. Complete tasks in order and report your result to your tutor before moving on.

1. **Trade Capture** — Create a USD/INR FX Forward: Buy USD 1,000,000 at 90.00, value date 11-Dec-2026. Validate and book. Record Trade ID.
2. **Trade Verification** — Verify product, book, counterparty, side, notional, rate, trade date and value date.
3. **Amendment** — Amend the same trade from USD 1,000,000 to USD 1,500,000. Report version, notional and status.
4. **Lifecycle Impact** — Explain which Middle Office, Back Office and Accounting outputs should change after the amendment.
5. **MTM** — Using current relevant market rate 92.00, calculate simplified MTM: (market rate − contract rate) × USD notional.
6. **Market Data** — Inspect USD/INR Bid/Ask and explain which quote a USD buyer uses and why.
7. **Production Support** — Investigate a case where trade screen shows amended notional but valuation uses the old notional. Write first five investigation steps.
8. **Settlement** — Identify the reference-data area to investigate when an FX Forward settlement fails.
9. **Accounting** — Explain Settlement vs Accounting for an FX Forward in 3–4 lines.
10. **Risk** — Explain VaR, Expected Shortfall, PFE and limit breach; identify the counterparty-exposure measure.
11. **Configuration** — Write Given/When/Then acceptance criteria for blocking inactive counterparties on FX Forward booking.
12. **End-to-End BA Case** — Value Date changes from 11-Dec to 20-Dec; trade and valuation update, settlement/accounting remain 11-Dec. Identify first investigation point, teams, root cause hypothesis and regression tests.

## Training rule
Do not jump ahead or use an answer key. The tutor reviews each result and gives the next task only after the current task is understood.

The website is an independent educational simulation, not an official Murex installation or live market feed.