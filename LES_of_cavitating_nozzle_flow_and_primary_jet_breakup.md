## Large-eddy simulation of cavitating nozzle flow and primary jet break-up 
 
Örley, F., Trummler, T., Hickel, S., Mihatsch, M. S., Schmidt, S. J., & Adams, N. A. (2015)

- Employed a barotropic two-phase/two-fluid model to study the primary break-up of cavitating liquid jets emanating from a rectangular nozzle, which resembles a high aspect-ratio slot flow
- *A detailed understanding of flow phenomena is necessary to control the effects of cavitation and their influence on jet and spray characteristics when injected into a gas phase.*
- Proposal of a simple, closed-form barotropic two-fluid cavitation model including non-condensable gases. The thermodynamic model is an extension of the compressible framework for single-fluid implicit large-eddy simulations of turbulent, cavitating flows
- Principle of the homogeneous-mixture model inside a computational cell in the framework of a finite volume discretization is sketched. The actual interface of water in its liquid and vaporous state, which may consist of several discrete small vapor bubbles inside one
computational cell, and the interface between liquid (or liquid-vapor) and non-condensable gas are not reconstructed, unlike with sharp-interface methods.
- Employing an implicit LES approach based on the Adaptive Local Deconvolution (ALDM) method

### Results

- Extended a thermodynamic equilibrium cavitation model by a non-condensable gas component to formulate a simple, but highly effective approach for LES. Focus of the present study is the initial stage of the jet break-up. 
- The simulation of the secondary break-up, that is, ligament and droplet formation, has not been considered since the current model does not include surface tension effects.
- The model has been applied to a cavitating nozzle slot and jet flow injected into air
- In addition to classical Kelvin-Helmholtz type large scale instabilities of the jet surface, three main mechanisms suggested to be responsible for jet break-up in cavitating liquid flows have been reproduced and analyzed, namely:
  - turbulent fluctuations induced by the collapse of cavitation structures in the proximity of the exit plane of the nozzle
  - entrainment of gas into the nozzle
  - collapse events inside the jet near the liquid-gas interface. 
- All three mechanisms induce momentum directed away from the jet axis and lead to primary break-up of the jet. Collapse events near the exit and outside the nozzle region were found to be of particular importance.
