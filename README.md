## Project: Voltage Stability Assessment in Large-Scale Power Systems

---

### Project Executive Summary
This research project, completed for **ENEL 670**, synthesizes the current landscape of **Voltage Stability Assessment (VSA)**. As modern grids transition toward **Inverter-Based Resources (IBRs)**, traditional stability margins are shrinking. This study evaluates the transition from offline deterministic tools to real-time, AI-enhanced hybrid frameworks.

---

### Comparison of Assessment Paradigms


| Category | Specific Methods | Primary Advantage | Key Limitation |
| :--- | :--- | :--- | :--- |
| **Classical** | P-V & Q-V Curves, CPF, Modal Analysis | Analytical foundation | Not for real-time |
| **Probabilistic** | PVSA, Monte Carlo, Weibull | Handles uncertainty | Time-consuming |
| **Synchrophasor**| PMUs, Thevenin Tracking | Real-time monitoring | Latency dependent |
| **AI & ML** | PIML, GNNs, Ensemble Learning | Fast & Predictive | Data dependency |

---

### Key Takeaways & Industry Insights


| Insight Area | The Challenge | The Emerging Solution |
| :--- | :--- | :--- |
| **Inverter Challenge** | Loss of reactive power support from IBRs. | Real-time tracking of thinning margins. |
| **Evolution of Tools** | Offline methods are too slow for fast grid dynamics. | PMU-based monitoring for situational awareness. |
| **Hybrid Frameworks** | Pure AI can violate physical grid constraints. | Physics-Guided AI (PIML) for law-abiding predictions. |

---

### Summary of Deterministic Analysis


| Analysis Type | Focus | Key Indicator |
| :--- | :--- | :--- |
| **P-V Curve** | Active Power (P) vs Voltage (V) | Nose Point (Max Loadability) |
| **Q-V Curve** | Reactive Power (Q) vs Voltage (V) | Minimum Point (Reactive Margin) |
| **Modal Analysis** | Eigenvalue Decomposition | Smallest Eigenvalue (Stable if > 0) |

---

### Core References
*   **P. Kundur (2004):** *Power System Stability and Control*
*   **C. W. Taylor (1994):** *Power System Voltage Stability*
*   **Ajjarapu & Christy (1992):** *Continuation Power Flow for Stability Margin Calculations*
*   **M. Amroune (2021):** *Review of ML Applied to On-Line Voltage Stability*

---
*Project completed as part of the ENEL 670: Power System Analysis Application curriculum.*
