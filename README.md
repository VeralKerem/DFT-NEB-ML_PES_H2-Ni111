# DFT-NEB-ML_PES_H2-Ni111
This repository presents a density functional theory (DFT) and machine learning (ML) approach for studying H₂ adsorption on a Ni(111) surface. It includes potential energy surface (PES) construction, dissociative adsorption energy barrier calculation via NEB, and Gaussian Process Regression (GPR) modeling of the PES. 
# 🧠 DFT + NEB + ML: Modeling H₂ Dissociative Adsorption on Ni(111)

This repository presents a compact yet complete pipeline for modeling the **dissociative adsorption** of H₂ on Ni(111), combining **DFT**, **NEB** and **Machine Learning**.

🎯 **Project Aim**:  
To replicate and understand the core idea behind the Leiden University PhD project on *“Predicting and Testing Reaction Barriers on Metal Surfaces”* by constructing a potential energy surface (PES) and predicting reaction barriers using GPR.

---

## 📦 Contents

| File | Description |
|------|-------------|
| `calculate_slab_energy.py` | DFT energy for bare Ni(111) slab |
| `calculate_h2_gas_energy.py` | DFT energy for H₂ in gas phase |
| `calculate_energies.py` | DFT calculations for H₂ + slab systems at various heights |
| `neb_run.py` | NEB script to model H₂ dissociation barrier |
| `pes_data.csv` | Adsorption energy data |
| `pes_plotter.py` | PES visualization |
| `PES_ML_Notebook.ipynb` | GPR-based PES modeling and analysis |
| `neb_manual_plot.png` | Transition state energy profile |

---

## 📊 What’s Inside?

- ✅ **DFT calculations** using GPAW
- ✅ **Potential Energy Surface (PES)** construction
- ✅ **Adsorption energy** computation and visualization
- ✅ **NEB** for dissociation barrier estimation
- ✅ **GPR model** for PES prediction and uncertainty
- ✅ **LOOCV** validation with RMSE and R² evaluation

---

## 🌍 Why It Matters?

This workflow reflects real-world approaches to surface catalysis, showing how *data-driven modeling* (ML) can accelerate *first-principles methods* (DFT/NEB).


---

## 🚀 Future Extensions

- Compare different XC functionals (PBE, RPBE, SCAN, etc.)
- Perform geometry optimizations for initial/final states
- Include Bader charge analysis
- Expand dataset and build 2D/3D PES
- Try alternative ML models (Neural Networks, SVR, etc.)
- Apply active learning for data-efficient improvement

---

## 📬 Contact

For questions or collaboration ideas:

**Kerem Veral**  
📧 keremveral98@gmail.com  

