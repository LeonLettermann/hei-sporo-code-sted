# hei-sporo-code-sted

**Code for analysis of microtubule position in STED images of plasmodium sporozoites.**

This repository is part of the [hei-sporo-code](https://github.com/LeonLettermann/hei-sporo-code) project and contains Python/JAX code for analysis of STED super-resolution microscopy images of sporozoites, and the inference of the position of the microtubules.

📦 **Test data** is available at the [associated dataset repository](https://doi.org/10.11588/DATA/4YBYXE).

---

## Repository Structure

```text
hei-sporo-code-sted/
├── AnalyzeSTED.ipynb    # Angular profile generation and microtubule position inference
└── environment.yml      # Conda environment file
                         # ⚠️ JAX version might need to be adapted to your system
