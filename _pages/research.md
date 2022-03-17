---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

<!-- {% include base_path %}

[<span style="color:navy">[Download CV]</span>](http://sekwonlee.github.io/files/cv.pdf) -->

<!-- <h2> Research interest </h2>  -->
# Research
<!-- I am broadly interested in developing hybrid quantum-classical theories and methods, including the following three parts. -->

- **Quantum many-body physics** <br>
  - Quantum many-body physics is principly a complicated problem with high complexity, where emergent phenomena are hidden behind the strong correlations beyond the mean-field. I am broadly interested in **inner mathematical structure of quantum many-body physics**. With the mathematical formulation well-understood, reasonable approximations can be made, useful information can be kept for the emergent phenomena of interest, and even predictions can be made in a way of first-principles. <br>

  - In condensed matter field theory, the quantum many-body problem is firstly formly written as a many-body action with infinite degrees of freedom, with which the physical quantities of interests can usually be expressed. By doing diagrammatic expansion and truncation obeying the conservation laws, reasonable approximations can be made in a controlled manner. Famous examples include the Hartree-Fock approximation, the *GW* approximation and the dynamical mean-field approximation etc. These approximations can be equivalently found in many-body perturbation theory (MBPT) and dynamical mean-field theory (DMFT). These approaches can also be combined together, that is the so-called quantum embedding, by which the strongly correlated region of the system can be mainly targeted.

  - Different from field theory, the quantum many-body problem can also be approached in a wave function perspective, by which the expectation value of a physical quantities of interest can be calculated. Namely, the true many-body wave function can be expanded as an infinite series of Slater determinants with infinite orders. In quantum chemistry, the series are truncated according to command, and the approximate expansion coefficients are obtained by diagonalization; in quantum Monte Carlo (QMC), the true ground state is represented by an imaginary time evolution of a trial wavefunction, which can be computed with stochastic sampling; in density matrix renormalization group (DMRG), the quantum state or narrowly the ground state wave function is represented by a matrix product state (MPS) where the correlation is reserved, and the variation is achieved by iterative sweeps of the matrix product operator (MPO).

  - Although density functional theory (DFT) is not diagrammatic, it is self-contained and provides a good mean-field starting point in most cases.

  - As a member of Galli group, I am focusing on **deriving and developing [quantum defect embedding theory (QDET)](https://arxiv.org/abs/2203.05493)**, which is a natural framework for the description of strongly correlated many-body states of promising spin-defects for quantum information science. As an intern student at Flatiron, I am focusing on **application of [discrete Lehmann representation (DLR)](https://arxiv.org/abs/2107.13094)**, which is a compact formalism of imaginary-time Green's function to Green's function theories including DMFT and MBPT to accelerate the real calculations.
    
- **Quantum computation and simulation** <br>
  - Due to the exponential complexity of quantum many-body physics, naturally it is unfavorable to simulate quantum with classical computers. On the contrary, the promising quantum computers, which hold the same nature of quantum, provide unlimited possiblities. For this reason, I am also interested in **algorithms for simulations on quantum computers**. <br>

  - In general, quantum computers have great advantage in memory due to the way of encoding. Quantum computers have also been proved to be powerful in time dependent simulations. No explicit proof has been established for the scaling of state related simulations on quantum computers.

  - In the current noisy intermediate-scale quantum era (NISQ), quantum phase estimation (QPE) is still not feasible and variational quantum eigensolver (VQE) is often adopted as the solver for an effective physical Hamiltonian of interests. However, the results from VQE is typically severely corrupted by the noise from the current quantum architechture. In order to reduce the error from the perspective of a theorist, what we can do is to **design post-processing error mitigation scheme** for this purpose.

  - Quantum computers can also be a good host for QMC calculations. Specifically, efficient algorithms can be designed for controlling the fermionic sign problem on quantum computers.
    
- **Scientific computing** <br>
  - Including but not limited to quantum, I am broadly intereted in **numerical algorithms for scientific computing** as well as the related **software development**. In many cases, physical problems, especially those are limited by computational cost, can be viewed in a mathematical way and from that angle, robust numerical tricks can be introduced for indentifying and solving the bottleneck. Furthermore, the structure of software can often be designed and optimized for the aim. <br>

  - For example, quantum mechanics is defined on an inifinite dimensional Hilbert space, the operations on which can be explained as matrix transformations. For this reason, numerical algorithms in matrix theory, such as Lanczos algorithm, Schmidt decomposition, singular value decomposition and QR decoposition etc can be applied. In many cases cases, such as QMC sampling, the calculations are almost independent from each other and can be implemented in a heavily parallel fashion with MPI or GPU.

  - As a member of Galli group, I am a developer of open source software [WEST](http://www.west-code.org) (Without Empty States) for large scale MBPT calculations, and the main developer for QDET. As an intern student at Flatiron, I participate in the development of open source software [TRIQS](https://triqs.github.io/triqs/latest) (Toolbox for Research on Interacting Quantum Systems) for DMFT calculations.

