## LES of Cavitating Nozzle and Jet Flows

Örley, F., Trummler, T., Mihatsch, M. S., Schmidt, S. J., & Hickel, S. (2017). 

- Developed a computationally very efficient method for the LES of injector and jet flows based on an Eulerian description with barotropic phase-equilibrium models. 
- This model extends existing compressible framework for LES of turbulent multiphase fuel flows (fuel in a liquid and gaseous state), and can now additionally capture the mixing of cavitating fuel jets with non-condensable gas

### Numerical Model

- The fluid flow is governed by the compressible Navier–Stokes equations, which we discretize with the finite-volume LES model of Hickel et al. and an additional transport equation for the mass fraction βG of the non-condensible gas.
- compressibility of all phases in order to capture cavitation induced wave dynamics considered.
- Transported volume-averaged mass density ρ = Φ βΦρΦ, is the sum of the volume-averaged densities ρΦ of the three componentsΦ = {M, W, G} weighted by their volume fraction βΦ. 
- Assuming thermodynamic and mechanical equilibrium, the cell-averaged pressure p can be computed from the equations of state (EOS) of the individual components Φ = {M, W, G} to close the transport equations.
- Barotropic equations of state, leading to p = p(ρ , βG).
- An isothermal, ideal gas EOS ρG = p/(RG Tref ), with Tref = 293.15, is used for the non-condensible gas. Liquid water is modeled as an isentropic fluid with a constant speed of sound cliq = 1482.35 m/s at the same ambient conditions. The EOS thendirectly follows from c2
liq = ∂p/∂ρ by integration. 

### Results

- For the third operating point with σ = 0.65, we observe cavitation in stable vortices that develop from the corners to the nozzle center and strongly damp the turbulence. These vortices are not stable in the experiment,probably due to a high level of inflow perturbations
- The collapse of cavitation structures near the nozzle exit induces turbulent fluctuations and promotes the jet breakup
- Collapse events identified near the exit plane of the nozzle increase the turbulence level, perturb the liquid-gas interface, and enhance the jet breakup in very good agreement with experimental data.
- Subsequent identification of two additional mechanisms that affect the jet breakup: 
  - The collapse of cavitation structures near the nozzle exit can lead to an entrainment of ambient gas into the nozzle, which then changes the effective nozzle cross section and tilts the jet. 
  - The collapse cavitation structures inside the jet near the liquid-gas interface leads to ejections of fuel into the ambient air, which increases the jet spreading angle
  
 
