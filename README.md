# Prestack-impedances-density-inversion
MATLAB implementation of Seismic pre-stack inversion using iterative, nonlinear quasi-second-order optimization techniques, accompanying Ahmed et al., Mathematical Geosciences (2026).

# Title: Seismic pre-stack inversion using iterative, nonlinear quasi-second-order optimization techniques

Ahmed, M. et al. (2026). *Seismic pre-stack inversion using iterative, nonlinear quasi-second-order optimization techniques*. Mathematical Geosciences.

## Overview

The code implements:
- Aki–Richards (1980) linearized reflectivity modeling (Used gradient equations B2-B4: Appendix B of Ahmed et al. (2026))
- Fatti et al. (1994) linearized reflectivity modeling (Used gradient equations A2-A4: Appendix A of Ahmed et al. (2026))
- Adjoint-state gradient computation (See equations A2 - A4 and B2 - B4, Appendix A/B of Ahmed et al. (2026))
- L-BFGS optimization
- Tikhonov regularization

## Requirements
- MATLAB R2020 or newer

## How to run

1. Open `Inversion folders: (INVERSION_AkiRichardsEquation.zip or INVERSION_FattiEquation.zip)
2. Run the forward model - Step 1
3. Run the script ''run inversion

## Repository structure

Two folders for each inversion - using Fatti et al. and Aki and Richards equations

