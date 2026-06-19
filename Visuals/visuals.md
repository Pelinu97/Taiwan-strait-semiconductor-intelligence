# Visuals

This document contains planned visual intelligence products supporting the OSINT analysis. All visuals are based on publicly available data and structured open-source research.

---

## 1. Global Semiconductor Supply Chain Map

This visualization maps the global semiconductor ecosystem across design, fabrication, equipment, and assembly layers.

### Structure

- United States → Chip design, EDA tools, IP control
- Taiwan → Advanced fabrication (TSMC dominance)
- South Korea → Memory and logic chips (Samsung, SK Hynix)
- Netherlands → Semiconductor equipment (ASML)
- Japan → Materials and precision equipment
- China → Assembly, packaging, and demand concentration

### Analytical Purpose

- Identify geographic concentration risks
- Map interdependencies across semiconductor value chain
- Visualize chokepoint vulnerabilities

### Sources

- https://www.sia-online.org/
- https://www.semi.org/en
- https://www.cset.georgetown.edu/
- https://www.csis.org/
- https://www.oecd.org/sti/ind/semiconductors.htm

---

## 2. US–China–Taiwan Semiconductor Trade Flow Diagram

This diagram illustrates semiconductor trade flows and geopolitical restrictions across major actors.

### Key Flows

- US → Taiwan: Design input, IP licensing, advanced chip demand
- Taiwan → US: High-end semiconductor exports
- Netherlands → US/Taiwan: EUV lithography equipment (ASML)
- US → China: Export control restrictions (advanced chips & tools)
- China → Global Market: High-volume semiconductor demand

### Analytical Purpose

- Identify supply chain chokepoints
- Show export control impact on technology flow
- Map fragmentation of global semiconductor system

### Sources

- https://www.bis.doc.gov/
- https://www.asml.com/en
- https://www.csis.org/analysis/semiconductors-and-us-china-competition
- https://www.brookings.edu/topic/technology/
- https://www.wto.org/

---

## 3. Turkey Semiconductor Risk Exposure Matrix

This matrix evaluates Turkey's exposure to semiconductor dependency across key sectors.

### Sector Risk Table

| Sector | Dependency | Risk Level |
|---|---|---|
| Defense Industry | High | Critical |
| Automotive | High | High |
| Consumer Electronics | Medium | Medium |
| Telecommunications | Medium | Medium |
| Industrial Systems | Medium | Medium |

> See `turkey_risk_matrix.docx` in this folder for the full sector scoring table and methodology.

### Analytical Purpose

- Assess national industrial vulnerability
- Identify critical dependency sectors
- Support strategic planning and risk mitigation

### Sources

- https://www.sipri.org/
- https://www.tubitak.gov.tr/
- https://www.aselsan.com.tr/
- https://www.roketsan.com.tr/
- https://www.oecd.org/turkey/

---

## 4. Global Semiconductor Manufacturing Concentration Map

This visualization highlights geographic concentration of advanced semiconductor production.

### Key Nodes

- Taiwan → >90% of advanced chips (<7nm nodes)
- South Korea → Memory and advanced logic
- United States → Design + partial fabrication
- Japan → Materials and upstream supply chain
- EU → Equipment and emerging fabs

### Analytical Purpose

- Demonstrate systemic dependency on Taiwan
- Highlight lack of redundancy in advanced fabrication
- Assess geopolitical production risk

### Sources

- https://www.sia-online.org/
- https://www.cset.georgetown.edu/
- https://www.tsmc.com/english
- https://www.samsung.com/semiconductor/
- https://www.mckinsey.com/industries/semiconductors

---

## 5. TSMC Global Dependency Network

This network map illustrates TSMC's role as a central node in global semiconductor supply chains.

### Key Connections

- Apple → TSMC (mobile chips)
- NVIDIA → TSMC (AI chips)
- AMD → TSMC (CPU/GPU production)
- Qualcomm → TSMC (mobile platforms)
- US Department of Defense → TSMC (defense electronics supply chain)

### Analytical Purpose

- Visualize systemic dependency on a single manufacturer
- Highlight cross-sector exposure (consumer + defense + AI)
- Support "Silicon Shield" geopolitical assessment

### Sources

- https://www.tsmc.com/english
- https://www.apple.com/supply-chain/
- https://www.nvidia.com/en-us/about-nvidia/
- https://www.amd.com/en/corporate
- https://www.csis.org/

---

## General Data Sources (Cross-Project)

- https://www.uncomtrade.org/
- https://www.worldbank.org/
- https://www.iea.org/
- https://www.statista.com/
- https://www.bis.doc.gov/
- https://www.oecd.org/sti/

---

## Implementation Notes

All visualizations are intended to be generated using open-source intelligence methods and publicly available datasets. No classified, proprietary, or restricted data sources are used.

Tools recommended for visualization:

- Flourish Studio (https://flourish.studio/)
- Draw.io (https://app.diagrams.net/)
- Gephi (https://gephi.org/)
- QGIS (https://qgis.org/)
- Python (Matplotlib / NetworkX)

---

## Final Statement

These visuals are not decorative elements but analytical components designed to support structured OSINT assessment of global semiconductor geopolitics.
