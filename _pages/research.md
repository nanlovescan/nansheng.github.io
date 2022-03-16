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

  - In condensed matter field theory, the quantum many-body problem is formly written as a many-body action with infinite degrees of freedom, with which the physical quantities of interests can usually be expressed. By doing diagrammatic expansion and truncation obeying the conservation laws, reasonable approximations can be made in a controlled manner. Famous examples include the Hartree-Fock approximation, the *GW* approximation and the dynamical mean-field approximation etc. These approximations can be equivalently found in many-body perturbation theory (MBPT) and dynamical mean-field theory (DMFT). These approaches can also be combined together, that is the so-called quantum embedding, by which the strongly correlated region of the system can be mainly targeted.

  - Different from field theory, the quantum many-body problem can also be approached in a wave function perspective, by which the expectation value of a physical quantities of interest can be calculated. Namely, the true many-body wave function can be expanded as an infinite series of Slater determinants with infinite orders. In quantum chemistry, the series are truncated according to command, and the approximate expansion coefficients are obtained by diagonalization; in quantum Monte Carlo (QMC), the true ground state is represented by an imaginary time evolution of a trial wavefunction, which can be computed with stochastic sampling; in density matrix renormalization group (DMRG), the quantum state or narrowly the ground state wave function is represented by a matrix product state (MPS) where the correlation is reserved, and the variation is achieved by iterative sweeps of the matrix product operator (MPO).

  - Although density functional theory (DFT) is not diagrammatic, it is self-contained and provides a good mean-field starting point in most cases.

<!-- 

  * **Areas:** <br>
    Condensed Matter field theory <br>
    Diagrammatic expansion <br>
    Quantum embedding theory (QET) <br>
    Dynamical mean-field theory (DMFT) <br>
    Many-body perturbation theory (MBPT) <br>
    Density functional theory (DFT) <br>
    Matrix product states (MPS) and density-matrix renormalization group (DMRG) <br>
    Post-Hartree-Fock (post-HF)
  * **Focus:** <br> -->
    Quantum defect embedding theory (QDET) for strongly-correlated states in materials<br>
    Discrete Lehnmann representation (DLR) for DMFT and MBPT <br>
    First-principles studies and predictions of spin qubits using QDET
    

- **Quantum computation and simulation** <br>
  Due to the exponential complexity of quantum many-body physics, naturally it is unfavorable to simulate quantum with classical computers. On the contrary, the promising quantum computers, which hold the same nature of quantum, provide unlimited possiblities. For this reason, I am also interested in **algorithms for simulations on quantum computers**. <br>
  * **Areas:** <br>
    Variational quantum eigensolver (VQE) <br>
    Quantum phase estimation (QPE) <br>
  * **Focus:** <br>
    Error mitigation scheme for quantum algorithms <br>
    Quantum algorithms as solvers for downfolded Hamiltonians
    
- **Scientific computing** <br>
  Besides the topics closely related to quantum, I am also broadly intereted in **numerical algorithms for scientific computing** as well as the related **software development**. In many cases, physical problems, especially those are limited by computational cost, can be viewed in a mathematical way and from that angle, robust numerical tricks can be introduced for indentifying and solving the bottleneck. Furthermore, the structure of software can often be designed and optimized for the target. <br>
  * **Areas:** <br>
    Numerical computing <br>
    Parallel computing
  * **Focus:** <br>
    Development of open source software [WEST](http://www.west-code.org) (Without Empty States) for MBPT calculations <br>
    Development of open source software [TRIQS](https://triqs.github.io/triqs/latest) (Toolbox for Research on Interacting Quantum Systems) for DMFT calculations
