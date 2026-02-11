# Thermal Saturation & Mechanical Load Analysis
**Technical Investigation into Diverter Gate Failures (USPS Chicago P&DC)**

This repository hosts the official White Paper and field research regarding magnetic force degradation in electromagnetic solenoids due to thermal saturation.

## 📊 Research Executive Summary
Under high-demand conditions (ZIP-code concentration), diverter gate solenoids experience excessive duty cycles that impede thermal dissipation.

**Key Findings:**
- **Resistance Increase:** Measured rise from 13.9Ω (baseline) to ~19Ω.
- **Force Degradation:** A calculated 45% drop in magnetic pulling capacity.
- **Root Cause:** The failure is a thermal-mechanical limit ($T > 220°F$) rather than a component defect.

## 📑 Repository Contents
- [📄 White Paper (PDF)](docs/Thermal_Saturation_Analysis.pdf) - Full technical report in IEEE conference format.
- [📸 Field Evidence](assets/) - Photos of coil measurements, jam events, and hardware diagnostics.

## 🛠️ Tech Stack & Methodology
- **Engineering Principles:** Ohm’s Law, Copper Temperature Coefficient of Resistance (TCR), and Hooke’s Law ($F=kx$).
- **Diagnostics:** Fluke Multimeter, High-Speed Video Motion Analysis (240 FPS).
- **Documentation:** LaTeX (IEEEtran class), TikZ for causal flowcharts.

---
**Author: Francisco González** *Electronic Engineer | [cite_start]Maintenance Mechanic, USPS Chicago P&DC* 
