# Math.Notes.et.Problems

This repository contains on-going Linear Algebra, Exponent Sum, etc. lecture-style notes and adjunctive exercises, which mainly based on my independent chain of theorems, definitions and correlated remarks.

## Notes

### Problems in Mathematical Analysis

Based on *Problems in Mathematical Analysis* by *B. P. Demidovich*,

analysis project is a selection of some exceptionally hard or unfamiliar exercises from the exercise booklet.

### Linear Algebra

Based on *Linear Algebra and Geometry* by *Shafarevich*,  
*Exercises in Algebra* by *Kostrikin*, multiple resources by Prof. *Gilbert Strang*, and *Axler*, 

the linear algebra project corresponds to basic concepts of the course and selects some of the typical, illuminating problems from *Exercises in Algebra* by *Kostrikin*.

### Exponent Sum

Based on *Van der Corput's Method of Exponential Sums* by  
*S. W. Graham* (Michigan Technological University, USA) and  
*G. Kolesnik* (California State University, Los Angeles, USA),

the exponential sum project covers basic application estimating exponent sums as well as Van der Corput's method, including the _A-process_ and _B-process_. 

In addition, I addressed some typical number theory problems:
1. Exercise in _Harvard Lecture Notes- "Exponential sums III- the van der Corput" by Noam Elkies_, involving _Equidistribution_,
2. Exercise 3, 4, 5 in _Terrence Tao "254A, Notes 5: Bounding exponential sums and the zeta function"_, involving _Vinogradov-Korobov bound_ of L(s,χ).


## Build System

All PDF documents are automatically compiled through GitHub Actions and deployed through GitHub Pages.

## Online PDFs

### Problems in Mathematical Analysis

Link:  
https://Evaristesgun.github.io/Math.Notes.et.Problems/Problems_in_Mathematical_Analysis/main.pdf

---

### Linear Algebra

Link:  
https://Evaristesgun.github.io/Math.Notes.et.Problems/LinearAlgebra/main.pdf

---

### Exponent Sum

Link:  
https://Evaristesgun.github.io/Math.Notes.et.Problems/ExPair/main.pdf

---

## Repository Structure

```text
Math.Notes.et.Problems/
│
├── LinearAlgebra/
│   ├── sections/      Linear algebra notes in distinct themes
│   ├── src/           Custom notation and style settings
│   ├── main.tex       Main LaTeX source
│   └── main.pdf       Compiled PDF
│
├── ExPair/
│   ├── sections/      Expository notes and exercises
│   ├── src/           Custom notation and style settings
│   ├── main.tex       Main LaTeX source
│   └── main.pdf       Compiled PDF
│
├── Problems_in_Mathematical_Analysis/
│   ├── main.tex       Main LaTeX source
│   └── main.pdf       Compiled PDF
│
├── .github/
│   └── workflows/
│       ├── LinearAlgebra.yml
│       ├── ExPair.yml
│       ├── analysis.yml
│       └── deploy-pages.yml
│
└── index.html         Personal homepage for GitHub Pages
```
