# RF–CA–Markov and Probabilistic CA Land-Use Projection for Mamminasata, Indonesia

This repository contains reproducible Python scripts for land-use suitability mapping and 2032 land-use projections in the **Mamminasata Metropolitan Area (South Sulawesi, Indonesia)**.  
The modeling workflow integrates **Random Forest-based suitability analysis** (2008–2016) with **CA–Markov** and **probabilistic CA simulations** under multiple policy scenarios.

---

## 🧭 Project Overview

**Framework:**
1. **Suitability Modeling (2008–2016)** — Random Forest classification of land-use suitability using environmental and accessibility factors.  
2. **Land-Use Projection (2016–2032)** — Transition-based and probabilistic CA projections.

**Policy Scenarios:**
- **BAU (Business-as-Usual):** Baseline CA–Markov projection.  
- **B4B5 (Zero Rice Field Pressure):** 10% adaptive allowance for paddy-field conversion in protection zones.  
- **UPI (Urban Policy Intensity):** Prioritizes built-up expansion under controlled policy intensity.  
- **HYBRID (UPI ∪ B4B5):** Combined adaptive protection and urban intensity.  

All scenarios are simulated using 2016–2024 transitions and Random Forest suitability layers.

---

## 📁 Repository Structure

- `rf_suitability_mapping_mamminasata.py` — Random Forest model for land-use suitability mapping (2008, 2016).  
- `landuse_projection_scenarios_2032.py` — Probabilistic CA and CA–Markov projections for 2032.  
- `*.ipynb` notebooks — Colab-ready versions of the above scripts.  
- `requirements.txt` — List of required Python dependencies.  
- `LICENSE` — MIT license for open research use.

