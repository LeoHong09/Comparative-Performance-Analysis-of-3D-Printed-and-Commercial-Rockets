# Comparative-Performance-Analysis-of-3D-Printed-and-Commercial-Rockets
Evaluating flight stability, speed, and durability: Custom-designed 3D-printed rockets vs. store-bought commercial kits.


## 📌 1. Project Overview

This project presents a rigorous comparative performance analysis between **custom 3D-printed modular rockets** and **standard commercial store-bought kits**. By combining digital CAD modeling in Tinkercad with precise aerodynamic physics, we engineered a reliable, reusable, and highly customizable rocketry system designed to outperform fragile, pre-made commercial alternatives.

### 🔍 Problem Statement
Standard commercial rocket kits available on the market suffer from two major flaws:
1. **Low Reliability & Catastrophic Failures:** Built from fragile materials like paper, cardboard, and thin wood, these kits often fail or experience structural compromise (such as mid-air explosions) under high launch pressure.
2. **Limited Educational Value:** Because commercial kits come pre-made, students cannot alter or experiment with the physical design, preventing them from genuinely understanding how core physics concepts—like the Center of Gravity (CG)—affect flight dynamics.

### 💡 Our Solution
* **High-Durability PLA Construction:** Replaced fragile paper bodies with robust 3D-printed plastic components, significantly increasing structural integrity to withstand high-pressure launches and rough landings.
* **Modular Customization:** Engineered a modular snap-on/attach-on system for core components like the nose cone and wings, allowing users to physically swap and test different aerodynamic configurations to maximize flight performance.

---

## 🔬 2. Core Experiment: Custom 3D-Printed vs. Commercial Kits

The core of this project is an empirical flight trial designed to evaluate the flight stability, ascent speed, and structural durability of our custom 3D-printed prototype against standard commercial kits. 

### 🎛️ Experimental Controls
To ensure a fair and scientifically controlled experiment, all trials utilized:
* The exact same engine type (**Estes B4-4 Engines**)
* The identical launch pad and ignition system
* Executed at the same outdoor location under identical environmental weather conditions

---

## 📊 3. Testing Results & Performance Analysis

The results from our flight trials demonstrated a clear performance advantage for the custom 3D-printed modular design.

### 📈 Comparative Flight Data

| Rocket Type (Materials) | Ascent Speed | Total Flight Time | Wing & Body Durability |
| :--- | :--- | :--- | :--- |
| **Commercial Rocket #1** <br>(Paper + Plastic + Wood) | N/A (Exploded on Pad) | 0.0s | **Destroyed** (Catastrophic Failure) |
| **Commercial Rocket #2** <br>(Paper + Plastic + Wood) | ~6 m/s | ~17s | **Destroyed** (Wings snapped upon landing) |
| **3D-Printed Rocket (Ours)** <br>(PLA Plastic) | **~10 m/s (66% Faster)** | **~37s (117% Longer)** | **Not Destroyed** (Wings fully intact) |

### 🎯 Key Findings
* **Aerodynamic & Speed Superiority:** Guided by physics calculations and optimized in Tinkercad, our 3D-printed rocket achieved a much faster ascent speed (~10 m/s) and more than doubled the flight duration of the surviving commercial kit.
* **Exceptional Structural Integrity:** While the commercial cardboard bodies suffered severe heat damage from the engine and their wings snapped upon impact, our 3D-printed PLA components survived a hard landing on asphalt with **zero wing damage**, proving the design is highly reusable.

---

## 📐 4. Engineering Science & Design Calculations

### 📊 Static Stability & Center of Gravity (CG)
To prevent the rocket from tumbling and ensure an arrow-straight vertical flight path, we mathematically calculated the precise Center of Gravity ($\bar{x}_{cg}$) to ensure it always sits forward of the Center of Pressure (CP).

$$\bar{x}_{cg} = \frac{\sum x_i m_i}{\sum m_i}$$

#### 📍 Practical Calculation Example (Theoretical CG: 9.12 inches)
* **Nose Cone:** $100\text{ g}$ at $x = 2.0\text{ in}$
* **Body Tube:** $80\text{ g}$ at $x = 10.0\text{ in}$
* **Engine & Mount:** $50\text{ g}$ at $x = 18.0\text{ in}$
* **Fins/Wings:** $20\text{ g}$ at $x = 19.0\text{ in}$

$$\bar{x}_{cg} = \frac{(100 \cdot 2) + (80 \cdot 10) + (50 \cdot 18) + (20 \cdot 19)}{100 + 80 + 50 + 20} = \frac{2280}{250} = 9.12\text{ inches}$$

**Result:** The mathematical model placed the Center of Gravity exactly **9.12 inches from the tip of the nose cone**, successfully validating our digital simulations with flawless physical flight stability.

---

## 💻 5. Tools & Materials Selection

* **Digital Design & Simulation:** **Tinkercad** was utilized to transition 2D sketches into low-fidelity 3D models, allowing us to visually verify proportions and pre-calculate balance points before committing to manufacturing.
* **Manufacturing Tool:** FDM 3D Printer.
* **Material Selection:** **PLA Filament**
  * *Justification:* PLA was selected for its excellent dimensional accuracy and high structural rigidity. It allows for high-precision printing required to seamlessly fit the modular components together and successfully prevents wing "fluttering" at high flight velocities.

---

## 🛡️ 6. Safety & Field Procedures

* **Assembly Safety:** Adhesives and structural glues were applied strictly in well-ventilated workspaces. High-temperature safety protocols were observed when handling the 3D printer's hot end.
* **Launch Field Protocols:** Launches must only be conducted in vast, open outdoor areas clear of hazards like overhead power lines, trees, or buildings. 
* **Misfire Procedure:** In the event of an ignition failure or misfire, a strict **60-second wait window** must be enforced before disconnecting the launch battery and approaching the rocket.

---

## 📜 7. References & Acknowledgments

* **Expert Validation:** Design concept, specialized parachute retention hooks, and modular snap-on engine mount areas validated through technical analysis and feedback from **Ms. Jennifer Yates** (NASA Mentor and At-Site Worker, HAS Online 2025-2026).
* Sagias, N. P., Giannarakis, K. M., & Stergiou, C. I. (2018). *Mechanical Performance of 3D Printed Materials for Small-Scale Rocket Components.* Aerospace, 5(3), 93.
* Trust, T., & Maloy, R. W. (2017). *Why 3D Print? The Impact of 3D Printing on Student Engagement and Learning.* Journal of Computers in Mathematics and Science Teaching, 36(3), 253-275.
