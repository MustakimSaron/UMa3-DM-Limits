# Dark Matter Annihilation Constraints in Ursa Major III / UNIONS 1

This repository contains the Python analysis pipeline accompanying the paper:
**"Constraining WIMP Dark Matter Annihilation in the Ultra-Faint Milky Way Satellite Ursa Major III / UNIONS 1 with Fermi-LAT Observations"**

**Author:** Md Mustakim Bin Alam (Novosibirsk State University)  
**Contact:** m.alam1@g.nsu.ru  

---

## 🚀 Run in Google Colab

Click the badge below to run the analysis directly in your browser:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-GITHUB-USERNAME/UMa3-DM-Limits/blob/main/UMa3_DM_Limits.ipynb)

*(Note: Replace `YOUR-GITHUB-USERNAME` in the link above with your actual GitHub username).*

---

## 📌 Repository Overview

This code performs:
1. Astronomical coordinate conversion and target isolation for Ursa Major III ($b = +73.68^\circ$).
2. Automated region-of-interest query using NASA HEASARC 4FGL-DR4 Fermi-LAT catalogs.
3. Parametric modeling of prompt WIMP dark matter annihilation spectra ($\chi\chi \to b\bar{b}$).
4. Derivation of 95% C.L. velocity-averaged cross-section upper limits ($\langle \sigma v \rangle$) across $m_\chi \in [5, 1000]$ GeV.

---

## 🛠️ Installation & Dependencies

To run locally, clone this repository and install required packages:

```bash
git clone [https://github.com/YOUR-GITHUB-USERNAME/UMa3-DM-Limits.git](https://github.com/YOUR-GITHUB-USERNAME/UMa3-DM-Limits.git)
cd UMa3-DM-Limits
pip install -r requirements.txt
