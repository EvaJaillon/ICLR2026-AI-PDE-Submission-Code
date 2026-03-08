# ICLR2026-AI-PDE-Submission-Code
Code used for the paper **"Physics Informed Neural Networks for Magnetohydrodynamic Equations"** accepted at the **ICLR 2026 workshop on AI&amp;PDE**.

## Code Release Notice
The dedicated code is in the fill  <ins>ICLR_AI_PDE</ins>.
### What is included:
* Training neural networks model using the SIPN method and transfer learning to solve 8 MHD equations
* The solver used for evaluation
* Training neural network model using the SIPN method and transfer learning with the LBFGS to solve 8 MHD equations
* Ploting codes for figures such as the loss function, solutions and errors for the case detailed in the paper

  ## Abstract
  >[We present a data-free Physics-Informed Neural Network (PINN) framework for solving a coupled system of magnetohydrodynamic (MHD) equations. Rather than introducing a new network architecture, this work focuses on a practical training strategy that enables stable optimization of large, strongly coupled PINN systems using only physical residuals. The proposed approach employs a stepwise initialization protocol, in which subsets of equations and output variables are progressively introduced while reusing previously trained weights. This structure naturally supports transfer learning across different initial conditions and optimization regimes. We demonstrate that the resulting model can solve the full eight-equation MHD system without observational data and can be efficiently adapted to new initial conditions using multi-head transfer learning and hybrid Adam/L-BFGS optimization, achieving substantial reductions in training time while preserving solution accuracy.]
