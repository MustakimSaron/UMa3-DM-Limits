# Dark Matter Annihilation Constraints in Ursa Major III / UNIONS 1

This repository contains the Python analysis pipeline accompanying the manuscript:  
**"Constraining WIMP Dark Matter Annihilation in the Ultra-Faint Milky Way Satellite Ursa Major III / UNIONS 1 with Fermi-LAT Observations"**

**Author:** Md Mustakim Bin Alam (Novosibirsk State University)  
**Email:** m.alam1@g.nsu.ru  

---

## 🚀 Run in Google Colab

Click the badge below to open and run the notebook directly in your browser:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MustakimSaron/UMa3-DM-Limits/blob/main/UMa3_DM_Limits.ipynb)

---

## 📌 Repository Overview

This project includes:
1. **Target Mapping:** Astronomical coordinate conversion and Galactic latitude isolation ($b = +73.68^\circ$) for Ursa Major III / UNIONS 1.
2. **Background Isolation:** Automated HEASARC 4FGL-DR4 catalog query confirming a clean $3.0^\circ$ Region of Interest (ROI) with zero point-source contamination.
3. **Spectral Modeling:** Parametric yield calculations for hadronic dark matter annihilation ($\chi\chi \to b\bar{b}$).
4. **Cross-Section Limit Engine:** Numerical derivation of 95% C.L. upper bounds on velocity-averaged cross-sections ($\langle \sigma v \rangle$) across $m_\chi \in [5, 1000]\text{ GeV}$.

### 🛠️ Key Technical & Computational Highlights

* **Target Verification & Coordinates:** Mapped RA/Dec and Galactic coordinates ($b = +73.68^\circ$) for Ursa Major III / UNIONS 1 using `astropy`.
* **Automated Catalog Querying:** Queried NASA's HEASARC 4FGL-DR4 database via `astroquery` to verify a clear $3.0^\circ$ Region of Interest (ROI) with no background point sources.
* **WIMP Gamma-Ray Spectral Integration:** Parameterized and calculated differential photon energy spectra ($E^2 \, dN_\gamma/dE$) for hadronic annihilation channels ($\chi\chi \to b\bar{b}$) across dark matter masses $m_\chi \in [5, 1000]\text{ GeV}$.
* **Cross-Section Limit Engine:** Automated derivation of 95% C.L. upper bounds ($\langle \sigma v \rangle$) using numerical trapezoidal integration (`scipy.integrate.trapezoid`) against astrophysical J-factor inputs ($J = 10^{20.5}\text{ GeV}^2\text{ cm}^{-5}$).
* **Publication Visualizations:** Generated publication-ready figures formatted for double-column scientific layout using `matplotlib`.

---

## 🛠️ Installation & Setup

To run locally:

```bash
git clone [https://github.com/MustakimSaron/UMa3-DM-Limits.git](https://github.com/MustakimSaron/UMa3-DM-Limits.git)
cd UMa3-DM-Limits
pip install -r requirements.txt
