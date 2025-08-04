# CAMB-Project-Results

# CAMB Quintessence Model – CMB Anisotropy Analysis

This project uses the [CAMB](https://camb.info) (Code for Anisotropies in the Microwave Background) framework to study dark energy through a dynamic **quintessence model**. The model is compared against Planck 2018 CMB data to constrain cosmological parameters using MCMC techniques.

---

## 🔬 Objective

To investigate how a **trigonometric quintessence potential** of the form

\[
V($\phi$) = m^2 f^2 (1 - \cos(\phi/f))^n + \Lambda
\]

affects the CMB power spectrum, and to constrain its parameters using observational data.

---

## 📈 Methodology

- CMB anisotropies computed using CAMB with a custom dark energy model.
- Parametrized equation of state:  
  \[
  w(a) = w_0 + (1 - a) w_a
  \]
- Best-fit cosmological parameters derived from MCMC sampling (Planck 2018 likelihoods).
- Visualization of TT, EE, BB, and TE spectra along with lensing effects.

---

## 🧪 Parameter Values (Sample 3 Best Fit)

|     Parameter        |    Value      |
|----------------------|---------------|
| H₀                   |   70.156      |
| Ω<sub>b</sub>h²      |   0.074       |
| Ω<sub>c</sub>h²      |   0.065       |
| n<sub>s</sub>        |   1.078       |
| A<sub>s</sub> × 10⁹  |   1.914       |
| τ                    |   0.043       |
| w₀                   |   -0.281      |
| w<sub>a</sub>        |   -0.424      |
----------------------------------------
