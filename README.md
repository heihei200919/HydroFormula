# HydroFormula – Interactive Hydraulic Engineering Calculator

An **interactive, scenario‑based** calculation tool for hydraulic engineering, covering **16 typical scenarios** including open channels, sluices, pumping stations, aqueducts, tunnels, seepage, and more.  
It helps students, engineers, and educators quickly understand and apply core formulas through a step‑by‑step workflow: **select a scenario → input parameters → run calculation → review detailed steps**.

> **⚠️ Important Disclaimer**  
> This tool is intended for **educational purposes, formula demonstration, and preliminary estimation only**. It **must not replace** professional design software, code‑based verification, or experienced engineer review. Complex problems (e.g., dam stability, seepage fields, structural reinforcement, water hammer) require full design methods and detailed boundary conditions.

---

## ✨ Features

- **16 ready‑to‑use scenarios** covering common hydraulic tasks (channels, gates, pumping stations, aqueducts, tunnels, earth dams, siphons, ecological flow, water quality, flood routing, soil conservation, compound sections, desilting basins, etc.).
- **Chain‑of‑formulas** design: each scenario follows a real‑world logic flow, combining multiple formulas (Manning, hydraulic jump conjugate, Darcy's law, USLE, etc.) to demonstrate the complete calculation chain.
- **Interactive parameter input**: each scenario has its own input panel with default values and clear units.
- **Step‑by‑step results**: after clicking “Execute Calculation”, the output is displayed in 7 collapsible sections:
  1. Input parameters table
  2. Referenced standards and formulas
  3. Parameter checks (e.g., velocity range, Froude number, safety factors)
  4. Core calculation steps (with substitutions and intermediate values)
  5. Final result summary table
  6. Verification and summary of checks
  7. Conclusion and scope of applicability
- **Standard‑based**: each scenario references relevant national or industry codes (SL, GB, etc.).
- **Fully offline**: runs entirely in the browser – no internet or server needed.

---

## 🚀 Getting Started

### Online Demo
Download the single HTML file (`index.html`) and open it with any modern browser (Chrome / Edge / Firefox recommended).

### How to Use
1. Select a scenario from the dropdown list (e.g., “Irrigation Channel Design”).
2. Modify the input parameters as needed (typical values are pre‑filled).
3. Click the **“▶ Execute Calculation”** button.
4. Wait for the calculation to finish; seven sections will expand below.
5. Click on any section header to expand/collapse and review details.
6. Change parameters and re‑run to compare results.

---

## 📂 Scenario List

| ID  | Scenario Name |
|-----|---------------|
| s1  | Irrigation Channel Design & Capacity Check |
| s2  | Sluice Gate Opening Design & Discharge Capacity |
| s3  | Stilling Basin Design for Energy Dissipation |
| s4  | Pumping Station Selection & Water Hammer Protection |
| s5  | Aqueduct Hydraulic & Structural Integrated Design |
| s6  | Overall Stability Verification for Sluice Structures |
| s7  | Earth‑Rock Dam Seepage & Slope Stability (Simplified) |
| s8  | Inverted Siphon Hydraulic Design & Diameter Optimisation |
| s9  | Ecological Flow Determination & Water Resources Allocation |
| s10 | Water Environmental Capacity & Pollution Control |
| s11 | Small Catchment Flood Estimation & Drainage Design |
| s12 | Soil & Water Conservation Measures & Sediment Reduction |
| s13 | Compound Channel Flow Calculation |
| s14 | Gate Hoist Force & Metal Structure Design |
| s15 | Tunnel Lining Design & Reinforcement |
| s16 | Desilting Basin Design for Sediment Removal |

---

## 🛠️ Technology Stack

- **HTML5** – structure and layout
- **CSS3** – styling, responsive design
- **Vanilla JavaScript (ES6)** – data, logic, and rendering
- No external libraries or frameworks – lightweight and easy to modify.

---

## 📚 Target Users

- **Hydraulic engineering students** – for learning and practice.
- **Junior engineers** – for quick estimates and option comparisons.
- **Educators** – for classroom demonstration or lab sessions.
- **Enthusiasts** – to understand basic hydraulic computation methods.

---

## ⚠️ Important Notes

1. **Not for final design**: the tool is for teaching and preliminary checks **only**. Always use certified design software and comply with current codes.
2. **Parameter ranges**: default values are illustrative; real projects must use survey data and code‑specified values.
3. **Simplified models**: some scenarios (e.g., dam stability, seepage) employ simplified assumptions (e.g., planar slip, average gradient) – results indicate trends, not actual safety.
4. **Browser compatibility**: latest versions of Chrome, Edge, or Firefox are recommended.
5. **Interpretation**: conclusions are based on the current inputs; recalculate after changing parameters and always cross‑check.

---

## 📖 Customisation & Extension

- **Add new scenarios**: extend the `SCENES` object with new keys, following the existing structure (parameters, formulas, calculation function).
- **Modify calculation logic**: implement the corresponding function in the `CALC` object, returning `{ steps, checks, outputs, conclusion }`.
- **Adjust styles**: edit CSS variables in `:root` to change colours, spacing, etc.

---

## 📄 License

This project is licensed under the **MIT License** – free to use, modify, and distribute, provided the original copyright notice is retained. See [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Issues and pull requests are welcome – feel free to improve scenarios, fix formulas, or enhance the UI.  
If you have expertise in hydraulic engineering, we encourage you to contribute new scenarios.

---

## 📧 Contact

For questions or suggestions, please open an issue on GitHub.

---

**Let’s make hydraulic computation clearer and more accessible – together!** 💧****
