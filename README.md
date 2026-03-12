## Project: Voltage Stability Assessment in Large-Scale Power Systems

This repository contains the comprehensive literature review and research synthesis completed for **ENEL 670**. The project evaluates the evolution of assessment methods used to ensure grid reliability as modern power systems transition toward renewable-rich architectures.

##  Project Overview
Voltage stability is a critical challenge for modern grids due to the high penetration of **Inverter-Based Resources (IBRs)**. This study investigates the mathematical foundations and industry practices used to prevent voltage collapse, from traditional offline planning to emerging real-time AI solutions.

##  Comparison of Assessment Paradigms


| Category | Specific Methods | Primary Advantage | Key Limitation |
| :--- | :--- | :--- | :--- |
| **Classical** | P–V & Q–V Curves, CPF, Modal Analysis | Simple visualization; Analytical foundation | Not suitable for real-time; High computational cost |
| **Probabilistic** | PVSA, Monte Carlo, Weibull Modeling | Handles renewable uncertainty | Time-consuming; High data requirements |
| **Synchrophasor** | PMUs, Thevenin Parameter Tracking | Real-time monitoring; High observability | Dependent on PMU placement and latency |
| **AI & ML** | PIML, GNNs, Ensemble Learning | Fast, predictive; Topology-aware | Requires large datasets; "Black-box" nature |

##  Key Takeaways & Industry Insights


| Insight Area | The Challenge | The Emerging Solution |
| :--- | :--- | :--- |
| **The Inverter Challenge** | Replacing synchronous generators with IBRs reduces inherent reactive power support. | Thinning stability margins require more granular, real-time tracking. |
| **Evolution of Tools** | Classical methods are too slow for today's fast-changing grid dynamics. | Shifting toward **PMU-based monitoring** for faster situational awareness. |
| **Hybrid Frameworks** | Pure AI models can violate physical grid constraints. | **Physics-Guided AI (PIML)** ensures predictions obey fundamental power-flow laws. |

##  Summary of Deterministic Stability Analysis


| Analysis Type | Focus | Key Indicator |
| :--- | :--- | :--- |
| **P–V Curve** | Active Power (P) vs Voltage (V) | The "Nose Point" (Maximum Loadability) |
| **Q–V Curve** | Reactive Power (Q) vs Voltage (V) | Minimum Point (Reactive Power Margin) |
| **Modal Analysis** | Eigenvalue Decomposition | Smallest Eigenvalue ($\lambda_{min} \to 0$) |

##  Core References
*   **P. Kundur (2004):** *Power System Stability and Control*
*   **C. W. Taylor (1994):** *Power System Voltage Stability*
*   **Ajjarapu & Christy (1992):** *Continuation Power Flow for Stability Margin Calculations*
*   **M. Amroune (2021):** *Review of ML Applied to On-Line Voltage Stability*

---
*Project completed as part of the **ENEL 670: Power System Analysis Application** course curriculum.*
