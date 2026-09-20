# Shared Decision Challenge

**Proposed starting question:** Given a fixed student-organization educational budget, which workshop plan remains affordable under different attendance and cost assumptions?

Raymundo confirms the question and dataset at the September 23 kickoff. This is a proposed educational scenario, not an actual spending recommendation or evidence that a campus group has requested one.

## Shared inputs

Use a small public or clearly labeled simulated attendance series, stated per-session costs, capacity limits, and a fixed hypothetical budget. Record the source, permitted use, time coverage, field definitions, and any simulation seed. Do not invent actual attendance records or mix simulated figures with observed results.

## Tasks

1. Document and inspect the data. Make time order and missing values clear.
2. Use BA II Plus exercises to teach time value of money, cash flows, NPV/IRR, or amortization. Use a separate multi-period example when those concepts do not naturally fit a single workshop budget; do not force a discount rate into a short event calculation.
3. Build a naive or moving-average attendance baseline. Compare one suitable forecasting model using the same chronological holdout and metric. Use a model only if the dataset supports the comparison.
4. Run the documented inference workflow on a Jetson. Record software versions and repeated runtime measurements. Do not claim that a Jetson improves prediction accuracy merely because it runs the model.
5. Vary attendance, costs, or capacity. Show which assumptions change the feasible workshop plan. Keep forecast error separate from runtime measurements.
6. Write a one- to two-page decision brief: question, assumptions, evidence, alternatives, uncertainty, recommendation or reason to defer, and what not to conclude.

## Final package

Dataset metadata; reproducible analysis; calculator exercise; setup and benchmark protocol; sensitivity results; decision brief; facilitator notes. The package is ready when a second student can reproduce it and Raymundo reviews it.

Keep the broader original finance curriculum available: present value, DCF, NPV, IRR, amortization, risk-return tradeoffs, and scenario analysis. This challenge provides a common application rather than replacing those materials.
