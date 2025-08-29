# Cheap Experiments for Leverage University 🔧🌎

> «Математика — это та часть физики, где эксперименты дешевы.»  
> — В.И. Арнольд

N.B. LaTeX rendering is trash on Github, vs code works great.

- [Cheap Experiments for Leverage University 🔧🌎](#cheap-experiments-for-leverage-university-)
  - [Prospectus](#prospectus)
    - [Career Goals](#career-goals)
    - [Personal Motivations](#personal-motivations)
    - [Background](#background)
    - [Philosophy](#philosophy)
    - [Methodology \& Tools](#methodology--tools)
  - [Syllabus](#syllabus)
    - [Progress Tracking](#progress-tracking)
  - [Math Foundations — Two-Core Plan](#math-foundations--two-core-plan)
    - [Common base](#common-base)
    - [Goto Core (primary goal)](#goto-core-primary-goal)
    - [Modeling Core (secondary goal)](#modeling-core-secondary-goal)
  - [CS Core](#cs-core)
  - [Papers and Documentation](#papers-and-documentation)
    - [Philosophy \& Foundations](#philosophy--foundations)
    - [Performance Models](#performance-models)
    - [High-Performance Kernels](#high-performance-kernels)
    - [Memory \& Cache Models](#memory--cache-models)
    - [Compiler \& Program Transformations](#compiler--program-transformations)
    - [Machine Learning \& Differentiable Programming](#machine-learning--differentiable-programming)
  - [Domain Specific for Current Work](#domain-specific-for-current-work)
  - [Detours, Stretch Goals, Domain Specific](#detours-stretch-goals-domain-specific)


## Prospectus

### Career Goals

- Be the second coming of Kazushige Goto-san 🙇🥷
- HPC 🏎️💨
- Modeling 🚂
- Scientific Computing 🧑‍🔬
- Compiler work 🛠️

**North Star:** Ronin Perf LLC. ⚔️🥷

### Personal Motivations

- Conquer the Math Dragon 🧮🐉: persistent nerves about doing higher level math need to be confronted with exposure therapy. Don't be fooled, math is half intuition cultivation and half a bag of tricks 🪄. It is learnable.
- Find Leverage: the longer I ignore the closed form solutions lurking in math the more pathetic my programming gets. δῶς μοι πᾶ στῶ καὶ τὰν γᾶν κινάσω 🌍🔧.
- Don't Get Bored 🥱: it's easy to get the gist of every subject halfway through a book but math always goes deeper. It won't be boring.

### Background

I'm a software developer with minimal experience in math (some linear algebra and calculus). Now I want to make a career step change.

<!--  This section is commented out just for LLMs
### Status

36M. Currently a successful developer working as a quasi-build and test engineer (CI/CD, testing, maintaining build systems, and writing auxiliary programs) for a midsize semiconductor metrology company. Kind of a build and test engineer. More of a software mechanic with quick time to technical solution than a software developer with deep performance experience, but probably more knowledge about performance than the average developer. That is to say, I understand time complexity and op counting and what instruction pipelining is and memory latency, but haven't exactly spent time on avx intrinsics or assembly. Expertise in Python, experience in C, C++, C#, Rust, Java, and Javascript. Decent breadth of paradigm experience. 

No formal STEM background, more experience in literature, poetry, and classics. Majored in philosophy and classics with some specialization in logic and language:

- Phi of Lang
- Phi of Sci
- Phi of Mind
- Critical Thinking
- Symbolic Logic
- Modern Logic
- Aristotle's Logic
- Ancient Greek
- Latin

In my twenties I dipped into:

1. A random linear algebera textbook I never finished
2. Coding the Matrix (a linear algebra textbook) I never finished
3. A Programmer's Introduction to Mathematics (which covers linear algebra like SVD) but I never finished
4. A random calculus book I never finished (I got bored during Integration)

But I'm tired of CI/CD. I want to do the real under the hood work. I also find higher math interesting and elegant despite my historical aversion to math in general.
-->

### Philosophy

This isn't ultralearning in the traditional sense, I'm not speedrunning an MIT CS degree, I'm trying to surpass it. Building slow and deep and foundational knowledge and intuition. 

I am seeking a basis for the goal space: linearly independent and yet still spans the goal space.

I seek mathematical rigor to conquer the math dragon 🐉. No half assed computationally focussed "this is how you do a matrix multiply" books.

This booklist is meant to reflect the actual best and most rigorous texts that form the basis. MIT will have stuff like Strang, but I choose Axler. I choose Spivak for the disguised real analysis rather than a cookbook of derivatives. Soviet math is of particular interest for its reputation for blending intuition and rigor. Soviet books get ⚒️. 

No bridge books 🌉📚! LLMs solve the difficulty cold start wall problem. Sometimes I'll dip into supplemental works.

I am also interested in domain specific goals that can add dimensionality and give a real leg up in a particularly interesting domain (Durbin's BSA, Arnold's CM, Hecht etc.).

This syllabus is STRICTLY about the math and text books not about manuals and hands on work. That is all covered in parallel documents.

### Methodology & Tools

Interleave 1-3 books at a time.

Anki helps to retain familiarity with definitions and challenging proofs encountered in work.

A Leuchtturm 1916 notebook contains a "Commonplace Book" of encountered proof tricks like "Completing the Square." The book will be refined with experience.

Work through the problems in a paper pad and nice notebook and also write them up in LaTeX. Solve the problems independently multiple times.

This process will take years. But every book completed should add to performance abilities at work. There won't be one day after completing this list where "Now you can work on HPC! 🧑‍🎓." Likely the list will be refined as the books are completed and you identify paths yourself rather than with help.

---

## Syllabus

### Progress Tracking

- Axler 01: 1 month ✔️
- Axler 02: 1 month ✔️
- Spivak 01: Started July 28, problem 18/25 on August 12
- Spivak 02: 8/13/2025
- Axler 03a: 8/14/2025

Certainly this is a slow ramp up and will accelerate.

- 🛍️: Still to buy
- 🌐: Available Online
- 📖: Currently reading

## Math Foundations — Two-Core Plan

### Common base

1. Axler — Linear Algebra Done Right
   - Supplement: Shilov
   - Supplement: Gelfand’s Lectures on Linear Algebra
2. Spivak — Calculus
   - Supplement: Schaum’s Outline (exercises)
3. Spivak — Calculus on Manifolds

### Goto Core (primary goal)

1. Knuth et al. — Concrete Mathematics
2. Trefethen & Bau — Numerical Linear Algebra
   - Supplement: Golub & Van Loan — Matrix Computations
3. Higham — Accuracy and Stability of Numerical Algorithms
4. Saad — Iterative Methods for Sparse Linear Systems
5. 🛍️ Boyd & Vandenberghe — Convex Optimization
6. Nocedal & Wright — Numerical Optimization
7. 🛍️ Rivlin — Chebyshev Polynomials

### Modeling Core (secondary goal)

1. Arnold — Ordinary Differential Equations
2. 🛍️ Durrett — Probability: Theory and Examples
3. Kolmogorov & Fomin — Elements of the Theory of Functions and Functional Analysis
   - Supplement: Kreyszig
4. 🛍️ Samarskii — Theory of Difference Schemes
5. Tikhonov & Samarskii — Equations of Mathematical Physics
6. 🛍️ Körner — Fourier Analysis
7. 🛍️ Ahlfors — Complex Analysis
8. 🛍️ Trefethen — Spectral Methods in MATLAB

---

## CS Core

1. Bryant & O'Hallaron CSAPP
2. Sipser
3. CLRS – Introduction to Algorithms
4. Engineering a Compiler [Alternative:Modern Compiler Design by Grune et al]
  - Supplement: 🛍️ Muchnick's Advanced Compiler Design and Implementation
5. 🛍️ Pierce – Types and Programming Languages
6. 🛍️ Hennessy & Patterson – Computer Architecture: A Quantitative Approach
7. 🛍️ Herlihy & Shavit – Art of Multiprocessor Programming
8. 🛍️ Hwu & Kirk – Programming Massively Parallel Processors
9. 🛍️ Gropp, Lusk & Skjellum – Using MPI
10. 🛍️ Hastie & Tibshirani – Elements of Statistical Learning
11. 🛍️ Warren – Hacker's Delight
12. 🛍️ OSTEP

---

## Papers and Documentation

### Philosophy & Foundations

- Thurston — “On Proof and Progress in Mathematics”: philosophy of mathematics, discovery, and pedagogy.
- Wigner — “The Unreasonable Effectiveness of Mathematics in the Natural Sciences”: reflections on the mathematics–physics relationship.

### Performance Models

- Williams, Waterman & Patterson — “Roofline: An Insightful Visual Performance Model for Multicore Architectures”: performance modeling of memory- vs compute-bound workloads.
- Hong & Kung — “I/O Complexity: The Red–Blue Pebble Game” (1981): foundational lower bounds on communication complexity.
- Culler et al. — “LogP: Towards a Realistic Model of Parallel Computation” (1993): classic model for distributed-memory performance.
- Gustafson — “Reevaluating Amdahl’s Law” (1988): scalability model (weak scaling vs Amdahl’s pessimism).

### High-Performance Kernels

- Goto & van de Geijn — “Anatomy of High-Performance Matrix Multiplication”: cache optimization, BLAS kernel design.
- Whaley & Dongarra — “Automatically Tuned Linear Algebra Software (ATLAS)”: systematic search-based kernel optimization.
- Yotov et al. — “Is Search Really Necessary to Generate High-Performance BLAS?”: prediction vs empirical tuning.
- Frigo & Johnson — “The Design and Implementation of FFTW (‘The Fastest Fourier Transform in the West’)”: auto-tuning in FFT kernels.
- Volkov & Demmel — “LU, QR, and Cholesky Factorizations Using Vector Capabilities of GPUs” (2008): GPU kernel optimization, a Goto-style paper for accelerators.

### Memory & Cache Models

- Lam, Wolf & Lam — “The Cache Performance and Optimizations of Blocked Algorithms”: cache blocking theory.
- Frigo, Leiserson, Prokop & Ramachandran — “Cache-Oblivious Algorithms”: recursive cache-friendly algorithms without tuning parameters.

### Compiler & Program Transformations

- Lattner & Adve — “LLVM: A Compilation Framework for Lifelong Program Analysis & Transformation”: modular compiler infrastructure.
- Bastoul — “Code Generation in the Polyhedral Model”: loop transformations and dependence analysis.
- Allen & Kennedy — “Optimizing Compilers for Modern Architectures” (overview paper): classic introduction to compiler optimizations, ties into Muchnick.

### Machine Learning & Differentiable Programming

- Baydin et al. — “Automatic Differentiation in Machine Learning: A Survey”: AD foundations and systems.
- Vaswani et al. — “Attention Is All You Need”: the Transformer architecture, parallelism-friendly ML.
- Dean & Ghemawat — “MapReduce: Simplified Data Processing on Large Clusters”: distributed data processing at scale.


## Domain Specific for Current Work

These might help with my current job directly.

- Streetman & Banerjee – Solid State Electronic Devices
- Arnold's Mathematical Methods of Classical Mechanics ⚒️
- 🛍️ Hecht's Optics
- 🛍️ Griffiths – Introduction to Electrodynamics

## Detours, Stretch Goals, Domain Specific 

It is fine if these seem completely ancillary or redundant. This is a subscription list to expand and pick through after the main curriculum.

- Durbin's Biological Sequence Analysis
- 🛍️ Cover & Joy – Elements of Information Theory
- 🛍️ Nielsen & Chuang – Quantum Computation and Quantum Information
- 🛍️ Shreve – Stochastic Calculus for Finance II
- 🛍️ Anderson – Computational Fluid Dynamics: The Basics with Applications: Navier-Stokes is the perfect PDE playground for HPC. Ties together everything: PDEs, numerical methods, parallel computing. Plus, fluid flow shows up in semiconductor manufacturing.
- 🛍️ Pharr, Jakob & Humphreys – Physically Based Rendering (PBRT): Combines Monte Carlo methods (Durrett), optics (Hecht), and serious optimization. Rendering is embarrassingly parallel - perfect HPC domain. Ray tracing for metrology simulation.
- 🛍️ Diestel – Graph Theory