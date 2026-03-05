# Ankita Puri

Computational Materials Scientist | Heterogeneous Catalysis | Atomistic Modeling | Physics-Informed ML

I build computational frameworks that connect electronic structure calculations to catalytic performance under realistic operating conditions.

📍 Portland, OR  
📧 ankit05puri@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/ankita-puri-phd)

---

### Modeling pipeline

DFT Surface Modeling → Adsorption Energetics → Microkinetic Simulation → Catalytic Performance Maps → Physics-Informed ML Surrogate

---

## Featured Projects

### 1. Periodic DFT: CO Adsorption on Pt(111)

	Pt(111) Surface and Adsorption Energetics
	•	Constructed periodic Pt(111) surface slabs using ASE with vacuum separation and bulk constraints
	•	Relaxed slab geometries using GPAW (PBE, plane-wave basis) to obtain stable surface structures
	•	Investigated adsorption configurations for CO and O** across surface sites (top, bridge, fcc, hcp)
	•	Computed site-dependent adsorption energies to determine preferred binding geometries
	•	Built reproducible scripts for surface setup, adsorbate placement, and geometry optimization

🔗 Repository: [cat-adsorption-dft](https://github.com/ankita05puri/cat-adsorption-dft)

---

### 2. Microkinetic Modeling of CO Oxidation

	•	Implemented a mean-field microkinetic model for heterogeneous CO oxidation on Pt(111)
	•	Constructed a reaction network including CO adsorption, O₂ dissociation, surface reaction, and CO₂ desorption
	•	Solved stiff ODE systems (BDF integration) to simulate surface coverage dynamics and reach steady-state catalytic flux
	•	Generated TOF maps across temperature and CO partial pressure, revealing oxygen-activated, balanced, and CO-poisoned regimes
	•	Extracted apparent activation energies from Arrhenius analysis of steady-state catalytic rates
	•	Performed barrier perturbation and degree-of-rate-control (DRC) analysis to identify regime-dependent rate-controlling steps
	•	Visualized kinetic regime maps showing how catalytic behavior shifts across operating conditions

🔗 Repository: [cat-microkinetics](https://github.com/ankita05puri/cat-microkinetics)

---

### 3. Physics-Informed Machine Learning for Catalysis

	Built a machine learning surrogate model to approximate catalytic performance predicted by the microkinetic simulations.
	•	Generated structured datasets from microkinetic simulations across temperature and CO partial pressure
	•	Engineered physics-informed features (1/T, log P_CO) reflecting Arrhenius scaling
	•	Trained regression models to predict steady-state turnover frequency (TOF)
	•	Evaluated interpolation performance within known kinetic regimes
	•	Investigated generalization limits across regime transitions (e.g., CO-poisoned conditions)
	•	Analyzed how surrogate accuracy depends on coverage of the kinetic state space

🔗 Repository: [cat-microkinetics](https://github.com/ankita05puri/cat-microkinetics)

---

## Technical Skills

**Electronic Structure & Surface Science:** Periodic DFT (GPAW), surface slab modeling, adsorption energetics, surface site analysis
**Catalysis & Reaction Modeling:** Microkinetic modeling, Arrhenius kinetics, surface coverage dynamics, degree-of-rate-control (DRC)
**Machine Learning for Physical Systems:** Physics-informed ML, regression models, surrogate modeling, regime generalization analysis
**Scientific Programming:** Python, NumPy, SciPy, Matplotlib, reproducible simulation workflows

---

## Current Direction

Developing scalable computational frameworks that connect electronic-structure calculations to catalytic performance through microkinetic modeling and physics-informed machine learning.
