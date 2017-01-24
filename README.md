* =================================================================
*                          FORTRAN SUBROUTINE
* =================================================================
*  This subroutine is used to estimate the diffusion coefficient from
*  un-reactive variavly saturated  half cell diffusion experiments.
*
*  Solves the diffusion equation using the solution for large times 
*  in which concentration at the cell ends change whith time  
*  (Barrer, 1951) cited in  Equation (4.58) page 63
*  Crank: Mathematics of Diffusion.
* 
*  Authors:
*  Marcos Paradelo Pérez
*  José Eugenio López Periago 
*  University of Vigo (2011)
*  Revision Jul 18, 2013
* 
*  Dependences: This should be implemented with the LM_OPT optimizacion code
*  (Clausnitzer, V.  and Hopmans, J.W. 1995)
*
* Clausnitzer, V., and J. W. Hopmans. 1995. Non-linear parameter estimation: LM_OPT.
* General-purpose optimization code based on the Levenberg–Marquardt algorithm. 
* Land, Air and Water Resources Paper No. 100032. University of California, 
* Davis, CA.
* =================================================================
