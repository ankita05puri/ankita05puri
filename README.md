# Ankita Puri

Computational Materials Scientist | Heterogeneous Catalysis | Atomistic Modeling | Physics-Informed Machine Learning

I develop computational frameworks that connect electronic structure calculations to catalytic performance under realistic operating conditions

📍 Portland, OR  
📧 ankit05puri@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/ankita-puri-phd)

### Modeling pipeline

```bash
DFT Surface Modeling
        ↓
Adsorption Energetics
        ↓
Microkinetic Simulation
        ↓
Catalytic Performance Maps
        ↓
Physics-Informed ML Surrogate
```

## Featured Projects

### 1. Periodic DFT Modeling of Surface Reactivity
	
	Pt(111) Surface and Adsorption Energetics
	•	Constructed periodic Pt(111) slab models using ASE with vacuum separation and constrained bulk layers
	•	Performed surface and adsorption geometry optimizations using GPAW (PBE, plane-wave basis)
	•	Investigated adsorption configurations for CO* and O* across surface sites
	•	Computed adsorption energetics to identify preferred binding geometries and site stability
	•	Implemented reproducible Python workflows for surface construction, adsorbate placement, and geometry relaxation
	•	Prepared co-adsorption configurations and reaction pathway setup for CO oxidation studies

🔗 Repository: [cat-adsorption-dft](https://github.com/ankita05puri/cat-adsorption-dft)

### 2. Microkinetic Modeling of CO Oxidation

	Developed a physics-based microkinetic framework translating surface reaction energetics into catalytic performance.
	•	Implemented a mean-field microkinetic model for heterogeneous CO oxidation on Pt(111)
	•	Constructed a reaction network including CO adsorption, O₂ dissociation, surface reaction, and CO₂ desorption
	•	Solved stiff ODE systems (BDF integration) to simulate surface coverage evolution and steady-state catalytic flux
	•	Generated TOF maps across temperature and CO partial pressure revealing oxygen-activated, balanced, and CO-poisoned regimes
	•	Extracted apparent activation energies from Arrhenius analysis of steady-state catalytic rates
	•	Performed barrier perturbation and degree-of-rate-control (DRC) analysis to identify regime-dependent rate-controlling steps
	•	Visualized kinetic regime maps showing how catalytic behavior shifts across operating conditions
 
🔗 Repository: [cat-microkinetics](https://github.com/ankita05puri/cat-microkinetics)

### 3. Physics-Informed Machine Learning for Catalysis
	
	Developed a machine learning surrogate model to accelerate evaluation of catalytic performance.
	•	Generated structured datasets from microkinetic simulations across temperature and CO partial pressure
	•	Engineered physics-informed features including inverse temperature (1/T) and log partial pressure
	•	Trained regression models to predict steady-state turnover frequency (TOF) in log space
	•	Achieved high predictive accuracy within trained kinetic regimes
	•	Evaluated generalization under CO pressure holdout conditions
	•	Demonstrated how surrogate models approximate learned kinetic manifolds but degrade across regime transitions

🔗 Repository: [cat-microkinetics](https://github.com/ankita05puri/cat-ml-surrogate) 

## Technical Skills

	•	Electronic Structure & Surface Science: Periodic DFT (GPAW), surface slab modeling, adsorption energetics, surface site analysis
	•	Catalysis & Reaction Modeling: Microkinetic modeling, Arrhenius kinetics, surface coverage dynamics, degree-of-rate-control (DRC)
	•	Machine Learning for Physical Systems: Physics-informed ML, regression models, surrogate modeling, regime generalization analysis
	•	Scientific Programming: Python, NumPy, SciPy, Matplotlib, reproducible simulation workflows

## Current Direction

Developing scalable computational frameworks that connect electronic structure calculations, microkinetic modeling, and machine learning to enable predictive catalyst discovery.
