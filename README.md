\# Hydrogen Atom Ab-initio Solver



This project implements a simple ab-initio numerical solution of the radial Schrödinger equation for the hydrogen atom using finite difference methods.



\## Theory



We solve the radial Schrödinger equation:



-1/2 d²u/dr² - 1/r u = E u



The exact ground state energy is:



E = -0.5 Hartree



\## Method



\- Finite difference discretization

\- Tridiagonal Hamiltonian matrix

\- Eigenvalue solution using scipy.linalg.eigh\_tridiagonal

\- Wavefunction normalization



\## Results



The computed ground state energy is approximately:



E ≈ -0.499 Hartree



which agrees well with the theoretical value -0.5 Hartree.



\## Requirements



numpy  

matplotlib  

scipy  



\## Author



Eren Balibey

