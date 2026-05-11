# Linear Algebra of Quantum Mechanics

**Methods and Models for Statistical Mechanics** — Mathematical Engineering, Politecnico di Milano  
Academic year: 2025–2026 | Advisor: Prof. Silvia Lorenzani

---

## 📄 Overview

This report presents a rigorous exposition of the lecture notes *"Linear Algebra of Quantum Mechanics"* by Vojkan Jakšić (2022), addressing the mathematical foundations required to describe quantum systems. The central motivation lies in the inadequacy of classical probability for non-commutative structures: while commuting observables admit a classical probabilistic treatment, bounded linear operators on a Hilbert space give rise to fundamentally new phenomenology.

The scope is deliberately restricted to finite-dimensional Hilbert spaces, a mathematically justified choice that makes spectral theory reducible to the study of eigenvalues and eigenprojections of matrices, while remaining rich enough to encompass quantum channels, quantum Markov chains, and the foundational structures of quantum information theory.

**Keywords:** Hilbert spaces · Spectral theory · Trace inequalities · Quantum probability · C\*-algebras

---

## 📚 Structure

### 1. Hilbert Spaces and Linear Maps
- Hilbert spaces and orthonormal bases, Parseval identity
- Adjoints and special classes of operators (self-adjoint, normal, unitary, projections)
- Spectral theory: eigenvalues, eigenprojections, abstract Jordan normal form, functional calculus
- Completely positive maps and quantum channels: Kraus–Stinespring theorem, Perron–Frobenius theory
- Operator monotone and operator convex functions, Loewner's theorem

### 2. Trace and Schatten p-Norms
- Definition of the trace and basis-independence, cyclicity property
- Schatten p-norms, singular values, Hölder and Minkowski inequalities
- Key trace inequalities of quantum statistical mechanics:
  - **Peierls–Bogolyubov inequality** (quantum Jensen)
  - **Klein's inequality** (foundation of quantum relative entropy)
  - **Golden–Thompson inequality** (partition function bounds)
  - **Araki–Lieb–Thirring inequality** (monotonicity of quantum relative entropies)

### 3. Quantum Probability
- Lattice of quantum events, failure of distributivity
- Density matrices, quantum probability measures, and **Gleason's theorem**
- Quantum random variables, commutativity, and the **Heisenberg uncertainty principle**
- Quantum marginals, partial trace, and **entanglement** (Bell states, entanglement entropy)
- Quantum stochastic processes and **quantum Markov chains** in the C\*-algebra framework

### 4. Proofs and Exercises
Selected proofs of key results:
- Spectral theorem for normal and unitary operators
- Polar decomposition
- Schwarz inequality for 2-positive maps
- Hölder and Minkowski inequalities for Schatten norms
- Failure of the triangular inequality for absolute values in dimension 2
- Properties of quantum marginals via partial trace

---

## 🗂️ Repository Contents

```
├── main.tex                # Main LaTeX source file
├── report.pdf              # Compiled PDF report
├── Presentation
│   ├── presentation.pdf    # Compiled PDF presentation
│   └── main.tex            # Main LaTeX source file
└── README.md
```

---

## 🔧 Compiling the Report

The report is written in LaTeX. To compile:

```bash
pdflatex main.tex
```

---

## 📖 References

The report is based entirely on:

> Vojkan Jakšić, *Linear Algebra of Quantum Mechanics*, Lecture Notes, McGill University, 2022.

Additional references cited within include works by Gleason (1957), Evans & Høegh-Krohn (1978), Fagnola & Pellicer (2009), Wolf (*Quantum Channels and Operations*, 2012), and Petz (*Quantum Information Theory and Quantum Statistics*, Springer, 2008).
