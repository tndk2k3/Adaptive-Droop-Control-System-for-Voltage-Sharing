# Adaptive Droop Control System for Automatic Voltage Restoration in DC Microgrids

This repository contains simulation models and materials related to the research paper:  
[Adaptive Droop Control System for Automatic Voltage Restoration in DC Microgrids](https://ieeexplore.ieee.org/document/10227142)

## Overview
DC microgrids are promising for integrating renewable energy and sharing power locally.  
However, traditional droop control suffers from:
- Inaccurate current sharing  
- Voltage deviations under load or source fluctuations  

This project proposes an **Adaptive Droop Control Method** that:
1. Dynamically adjusts droop coefficients in real time to minimize current-sharing errors.  
2. Uses a secondary control loop to eliminate bus voltage deviation and restore voltage automatically.  

The system is validated through **PLECS simulations**, showing:
- Faster response and smaller transient time compared to conventional droop control  
- Improved load balancing and bus voltage regulation  
- Stable operation even under sudden changes in renewable input or load variations:contentReference[oaicite:1]{index=1}  

---

## Illustrations

### Simplified Model of a DC Microgrid
![Simplified Model](Simplified%20model%20of%20a%20DC%20microgrids.png)

### Block Diagram of the Proposed Controller
![Block Diagram](Block%20diagram%20of%20the%20controller.png)

---

## Repository Structure
- `Part4_Adaptive Droop Control System.plecs` – Simulation model (Case studies)  
- `Part6_Adaptive Droop Control System.plecs` – Extended simulation model  
- `SLIDE_Droop_Voltage_Sharing_in_DC_Microgrids.pdf` – Presentation slides  
- `README.md` – Project overview  

---

## Tools
- Simulation software: **PLECS**  
- Models: Dual generator + DC load test system  


