# Cheap Experiments for Leverage University 🔧🌎

> «Математика — это та часть физики, где эксперименты дешевы.»  
> — В.И. Арнольд

- [Cheap Experiments for Leverage University 🔧🌎](#cheap-experiments-for-leverage-university-)
  - [Prospectus](#prospectus)
    - [Career Goals](#career-goals)
    - [Personal Motivations](#personal-motivations)
    - [Background](#background)
    - [Philosophy](#philosophy)
    - [Methodogy \& Tools](#methodogy--tools)
  - [Syllabus](#syllabus)
    - [Progress Tracking](#progress-tracking)
  - [Math Foundations – Ordered Spine](#math-foundations--ordered-spine)
      - [Stage 1 — Core algebra/analysis bedrock](#stage-1--core-algebraanalysis-bedrock)
      - [Stage 2 — ODEs + applied linear algebra](#stage-2--odes--applied-linear-algebra)
      - [Stage 3 — Functional Analysis + Probability](#stage-3--functional-analysis--probability)
      - [Stage 4 — Fourier/complex toolkits](#stage-4--fouriercomplex-toolkits)
      - [Stage 5 — Optimization + PDEs](#stage-5--optimization--pdes)
      - [Stage 6 — Specialized methods](#stage-6--specialized-methods)
  - [Core](#core)
  - [Papers and Documentation](#papers-and-documentation)
  - [Domain Specific for Current Work](#domain-specific-for-current-work)
  - [Detours, Stretch Goals, Domain Specific](#detours-stretch-goals-domain-specific)


## Prospectus

### Career Goals

- Be the second coming of Kazushige Goto-san 🙇🥷
- HPC 🏎️💨
- Modelling 🚂
- Scientific Computing 🧑‍🔬
- Compiler work 🛠️

### Personal Motivations

- Conquer the Math Dragon 🧮🐉: persistent nerves about doing higher level math need to be confronted with exposure therapy. Don't be fooled, math is half intuition cultivation and half a bag of tricks 🪄. It is learnable.
- Find Leverage: the longer I ignore the closed form solutions lurking in math the more pathetic my programming gets. δῶς μοι πᾶ στῶ καὶ τὰν γᾶν κινάσω 🌍🔧.
- Don't Get Bored 🥱: it's easy to get the gist of every subject halfway through a book but math always goes deeper. It won't be boring.

### Background

I'm a software developer with minimal experience in math (some linear algebra and calculus). Now I want to make a career step change

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

This isn't ultralearning in the traditional sense, I'm not speedrunning MIT level knowledge, I'm trying to surpass it. Slow and deep and foundational knowledge.

I am Seeking a basis for the goal space: linearly independent and yet still spans the goal space.

I seek mathematical rigor to conquer the math dragon 🐉. No half assed computationally focussed "this is how you do a matrix multiply" books.

This booklist is meant to reflect the actual best and most rigorous texts that form the basis. MIT will have stuff like Strang, but I choose Axler. I choose Spivak for the disguised real analysis rather than a cookbook of derivatives. Soviet math is of particular interest for its reputation for blending intuition and rigor. Soviet books get ⚒️. 

No bridge books 🌉📚! LLMs solve the difficulty cold start wall problem. Sometimes I'll dip into supplemental works.

I am also interested in domain specific goals that can add dimensionality and give a real leg up in a particularly interesting domain (Durbin's BSA, Arnold's CM, Hecht etc.).

This syllabus is STRICTLY about the math and text books not about manuals and hands on work. That is all covered in parallel documents.

### Methodogy & Tools

Interleave 1-3 books at a time.

Anki helps to retain familiarity with definitions and challenging proofs encountered in work.

A Leuchtturm 1916 notebook contains a "Commonplace Book" of encountered proof tricks like "Completing the Square." The book will be refined with experience.

Also, work through the problems in a paper pad and nice notebook and also write them up in LaTeX. Solve the problems independently multiple times.

This process will take years. But every book completed should add to performance abilities at work. There won't be one day after completing this list where "Now you can work on HPC! 🧑‍🎓." Likely the list will be refined as the books are completed and you identify paths yourself rather than with help.

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

## Math Foundations – Ordered Spine

#### Stage 1 — Core algebra/analysis bedrock

1. 📖🌐 Axler – Linear Algebra Done Right
   - Supplement with Shilov ⚒️
   - Supplement with Gelfand's lectures ⚒️
2. 📖 Spivak – Calculus
   - Supplement with Shaum's Outline
3. Spivak – Calculus on Manifolds

#### Stage 2 — ODEs + applied linear algebra

4. Arnold – Ordinary Differential Equations ⚒️
5. Trefethen & Bau – Numerical Linear Algebra
6. Saad – Iterative Methods for Sparse Linear Systems
7. Higham – Accuracy and Stability of Numerical Algorithms : Floating-Point Arithmetic, Condition Numbers, Backward Error Analysis, Numerical Stability

#### Stage 3 — Functional Analysis + Probability

8. Kolmogorov & Fomin – Elements of the Theory of Functions and Functional Analysis ⚒️
   - Supplement with Kreyszig
9. 🛍️ Durrett – Probability: Theory and Examples
10. Knuth et al – Concrete Math

#### Stage 4 — Fourier/complex toolkits

11. 🛍️ Stein & Shakarchi OR Körner – Fourier Analysis
12. 🛍️ Stein & Shakarchi OR Ahlfors – Complex Analysis

#### Stage 5 — Optimization + PDEs

13. 🛍️🌐 Boyd & Vandenberghe – Convex Optimization
14. Nocedal & Wright – Numerical Optimization
15. Tikhonov & Samarskii – Equations of Mathematical Physics ⚒️
16. Samarskii Theory of Difference Schemes ⚒️

#### Stage 6 — Specialized methods

17. Rivlin – Chebyshev Polynomials

## Core

1. Bryant & O'Hallaron CSAPP
3. Sipser
4. CLRS – Introduction to Algorithms
5. Engineering a Compiler [Alternative:Modern Compiler Design by Grune et al]
6. 🛍️ Pierce – Types and Programming Languages
7. 🛍️ Muchnick's Advanced Compiler Design and Implementation
8. 🛍️ Hennessy & Patterson – Computer Architecture: A Quantitative Approach
10. 🛍️ Herlihy & Shavit – Art of Multiprocessor Programming
11. 🛍️ Hwu & Kirk – Programming Massively Parallel Processors
12. 🛍️ Hastie & Tibshirani – Elements of Statistical Learning
13. 🛍️ Warren – Hacker's Delight

## Papers and Documentation
- Goto & van de Geijn – Anatomy of High-Performance Matrix Multiplication: High-Performance Matrix Multiplication, Cache Optimization, BLAS Kernel Design
- On Proof and Progress in Mathematics: Philosophy of Mathematics, Mathematical Discovery and Progress
- The Unreasonable Effectiveness of Mathematics: Mathematics-Physics Relationship, Applied Mathematics Philosophy
- Williams, Waterman & Patterson – Roofline Model
- Baydin et al – Automatic Differentiation in Machine Learning
- Dean & Ghemawat – MapReduce
- Vaswani et al – Attention Is All You Need
- Lattner & Adve – LLVM
- Lam, Wolf & Lam – "The Cache Performance and Optimizations of Blocked Algorithms" - foundational cache blocking theory
- Frigo, Leiserson, Prokop & Ramachandran – "Cache-Oblivious Algorithms" - the mathematical framework
- Bastoul – "Code Generation in the Polyhedral Model" - connects the math to actual compiler transformations
- Whaley & Dongarra – "Automatically Tuned Linear Algebra Software (ATLAS)" - how to systematically search optimization space
- Yotov et al. – "Is Search Really Necessary to Generate High-Performance BLAS?" - prediction vs empirical search for cache optimization
- Hong & Kung (1981) “I/O Complexity: The Red–Blue Pebble Game”

## Domain Specific for Current Work

These might help with my current job directly.

- Streetman & Banerjee – Solid State Electronic Devices
- Arnold's Mathematical Methods of Classical Mechanics ⚒️
- 🛍️ Hecht's Optics
- 🛍️ Griffiths – Introduction to Electrodynamics

## Detours, Stretch Goals, Domain Specific 

It is fine if these seem completely ancillary or redundant. This is a subscription list to expand and pick through after the 12+12 curriculum.

- Durbin's Biological Sequence Analysis
- 🛍️ Cover & Joy – Elements of Information Theory
- 🛍️ Nielsen & Chuang – Quantum Computation and Quantum Information
- 🛍️ Shreve – Stochastic Calculus for Finance II
- 🛍️ Anderson – Computational Fluid Dynamics: The Basics with Applications: Navier-Stokes is the perfect PDE playground for HPC. Ties together everything: PDEs, numerical methods, parallel computing. Plus, fluid flow shows up in semiconductor manufacturing.
- 🛍️ Pharr, Jakob & Humphreys – Physically Based Rendering (PBRT): Combines Monte Carlo methods (Durrett), optics (Hecht), and serious optimization. Rendering is embarrassingly parallel - perfect HPC domain. Ray tracing for metrology simulation.
- 🛍️ Diestel – Graph Theory
