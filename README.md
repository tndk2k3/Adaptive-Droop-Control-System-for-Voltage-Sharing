# Adaptive Droop Control for Automatic Voltage Restoration in DC Microgrids

**TL;DR:** A simple adaptive droop controller that (1) shares current fairly and (2) restores the DC bus to its nominal voltage under source/load changes—automatically.

## Why it matters
Classic droop often leaves bus-voltage error and uneven current sharing when sources or loads vary.

## What’s new
- **Primary loop:** tunes virtual resistance from current-sharing error → reduces mismatch.
- **Secondary loop:** shifts voltage reference from DC-bus error → removes steady-state deviation.

## Test bench
- PLECS simulation; **2 sources + 1 load**, nominal **Vbus ≈ 50 V**.
- Scenarios: source voltage step; two load steps.

## Results (high level)
- **Faster transient:** ~**0.08 s** vs **0.15 s** (classic droop).
- **Tighter regulation:** Vbus error ~**0.1 V** vs **1.5 V**.
- **Robust to load steps:** Vbus stays near nominal; overshoot/undershoot quickly suppressed.

## Quick view
![Overview](assets/Overview_Method.png)

## Reference
IEEE Xplore: https://ieeexplore.ieee.org/document/10227142

**Keywords:** DC microgrid · adaptive droop · voltage restoration · current sharing · PLECS
