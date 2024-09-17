**ELECTRA - ELECtron TRAnsfer broadened EPR simulator**
-------------------------------------------------------------
*by Mirco Zerbetto, Alessandro Agostini, Lorenzo Franco*, Department of Chemical Sciences, University of Padova, Italy

**********************************************************
This MATLAB live script is distributed under the GPL-v3.0 license.
**********************************************************

 ELECTRA is the MATLAB implementation of a simple model for the simulation of cw-ESR spectra showing broadening
 due to intramolecular electron transfer. The model is based on these assumption:
 * Redfiled limit for the roto-conformational dynamics of the molecule
 * secular approximation of the spin Hamiltonian
 
The script allows the simulation of molecules showing two sites between which electron transfer can occur.
The unpaired electron has hyperfine coupling with two nitrogen atoms in the two sites. Gaussian broadening
due to the interaction of hydrogen atoms is also implemented.

The user can load an experimental cw-ESR spectrum as 2-columns ASCII file and fit all the model parameters.
The live script is self explanatory; for the theory use as reference the paper. 
