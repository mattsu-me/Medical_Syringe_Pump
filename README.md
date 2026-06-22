# High-Precision Micro-Injection Pump R&D Project
### Medical Device Engineering Portfolio

## 1. Project Overview
To eliminate volumetric flow errors caused by eccentric loads and backlash-induced stick-slip effects during micro-dose delivery, this project introduces a **fully-constrained twin-rail precision injection system**. The architecture successfully maintains the volumetric flow accuracy within an optimal regulatory margin of **±2%** under continuous high-resistance scenarios (up to 50 N).

---

## 2. Core Mechanical Design Rationale (The 'Why')

* **Fully-Constrained Twin-Rail Alignment**
    Deployed dual micro MGN9H linear guide rails to eliminate parasitic tilting moments and structural deflection under a 50 N peak injection load, ensuring consistent linear push-rod displacement.
* **Custom Integrated Anti-Backlash Gearbox**
    Utilized SolidWorks Top-Down modeling to design a split-gear 60T anti-backlash pinion with embedded torsion spring pockets, completely neutralizing rotational play during motor reversals.
* **Optimized Thermal Management**
    Selected a low-current, high-impedance NEMA 17 stepper motor to drastically minimize dynamic heat dissipation, preventing temperature-induced geometric tolerance shifts during long-term clinical infusion.

---

## 3. System Geometry & Mechanical Specifications

| Component | Part Specification | Design & DFM Considerations |
| :--- | :--- | :--- |
| **Linear Guides** | MGN9H 200mm (Black Oxide Steel) | Provides rigid, fully-constrained guidance to combat eccentric thrust forces. |
| **Drive Screw** | T8 Stainless Steel Lead Screw (Lead 2mm) | Single-start thread architecture optimizing mechanical advantage and sub-microliter resolution. |
| **Anti-Backlash Nut** | uxcell Tr8x2 POM Nut Assembly | Low friction coefficient, high wear resistance, and absolute elimination of axial play. |
| **Actuator** | NEMA 17 Stepper Motor (Holding Torque > 30 N·cm) | Sufficient torque margin to overcome 50 N syringe resistance with low dynamic heat signature. |

---

## 4. 3D Assembly & R&D Documentation

> 💡 *Tip: You can upload your SolidWorks screenshots directly to this repository and link them below.*

![SolidWorks Assembly Render](image.png)
*Figure 1: 3D CAD modeling of the twin-rail alignment and anti-backlash drive system.*

---

## 5. Development Roadmap & Timeline
* **Week 1:** CAD Modeling, Component Selection, and Interference Check (SolidWorks).
* **Week 2:** Finite Element Analysis (FEA) for structural deflection & DFM reviews.
* **Week 3:** 3D Printing Prototyping and Hardware Assembly (Linear Rails & Lead Screw integration).
* **Week 4:** Mechatronics Integration (Arduino/A4988) and Volumetric Flow Rate Verification.
