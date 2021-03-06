Hartree-Fock Self-Consistent Field
==================================

This module seeks to provide an overview of the theory and programming challenges associated with Hartree-Fock molecular orbital theory, with the following tutorials:

- (3a) Restricted Hartree-Fock (RHF): Introduces the theory of the closed-shell, restricted orbital formulation of Hartree-Fock Molecular Orbital Theory, before guiding the reader through the implementation of a simple RHF program.

- (3b) Direct Inversion of the Iterative Subspace (DIIS): Explores the theory and integration of the DIIS convergence accelleration method into the RHF implementation from tutorial 3a.  

- (3c) Unrestricted Hartree-Fock (UHF): Introduces the open-shell, unrestricted orbital formulation of Hartree-Fock theory, and a walks through the implementation of a UHF program employing DIIS convergence accelleration.

- Density Fitting: Introduces and describes the generation and manipulation of approximate 3-index ERI tensors, illustrated with a simple algorithm for building the RHF Fock matrix.


## Planned tutorials:
- Restricted Open-Shell Hartree-Fock: Introduces the theory and implementation of ROHF.

- JK Building: Compares the speed and computational expense of several canonical and density-fitted algorithms for building Coulomb and Exchange matrices.

- Tensor Engines: Compares several engines for handling tensor contractions within quantum chemistry codes, including `np.einsum()`, `np.dot()`, and accessing direct BLAS routines through Psi4.

- Second-Order Self-Consistent Field (SOSCF): Discusses the application of second-order orbital optimization to accellerate the convergence of self-consistent field computations, and illustrates this method by walking through the integration of SOSCF into a RHF-DIIS program.

## References

1. A. Szabo and N. S. Ostlund, *Modern Quantum Chemistry*, Introduction to Advanced Electronic Structure Theory. Courier Corporation, 1996.
2. I. N. Levine, *Quantum Chemistry*. Prentice-Hall, New Jersey, 5th edition, 2000.
3. T. Helgaker, P. Jorgensen, and J. Olsen, *Molecular Electronic Structure Theory*, John Wiley & Sons Inc, 2000.
4. P. Pulay. *Chem. Phys. Lett.* **73**, 393-398 (1980)
5. C. David Sherrill. *"Some comments on accellerating convergence of iterative sequences using direct inversion of the iterative subspace (DIIS)".* Available at: vergil.chemistry.gatech.edu/notes/diis/diis.pdf. (1998)
