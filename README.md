# Thermal Saturation & Mechanical Load Analysis
**Technical Investigation into Diverter Gate Failures (USPS Chicago P&DC)**

[cite_start]This repository hosts the official White Paper and field research regarding magnetic force degradation in electromagnetic solenoids due to thermal saturation.

## 📊 Research Executive Summary
[cite_start]Under high-demand conditions (ZIP-code concentration), diverter gate solenoids experience excessive duty cycles that impede thermal dissipation.

**Key Findings:**
- [cite_start]**Resistance Increase:** Measured rise from 13.9Ω (baseline) to ~19Ω[cite: 7, 23].
- [cite_start]**Force Degradation:** A calculated 45% drop in magnetic pulling capacity[cite: 7, 36].
- [cite_start]**Root Cause:** The failure is a thermal-mechanical limit ($T > 220°F$) rather than a component defect[cite: 8, 93].

## 📑 Repository Contents
- [📄 White Paper (PDF)](docs/Thermal_Saturation_Analysis.pdf) - Full technical report in IEEE conference format.
- [🛠️ LaTeX Source](src/main.tex) - Source code and TikZ diagrams for replication.
- [cite_start][📸 Field Evidence](assets/) - Photos of coil measurements, jam events, and hardware diagnostics.

## 🛠️ Tech Stack & Methodology
- [cite_start]**Engineering Principles:** Ohm’s Law, Copper Temperature Coefficient of Resistance (TCR), and Hooke’s Law ($F=kx$)[cite: 28, 73].
- [cite_start]**Diagnostics:** Fluke Multimeter, High-Speed Video Motion Analysis (240 FPS)[cite: 40, 55].
- **Documentation:** LaTeX (IEEEtran class), TikZ for causal flowcharts.

---
**Author: Francisco González** *Electronic Engineer | [cite_start]Maintenance Mechanic, USPS Chicago P&DC* [cite: 3, 4]
