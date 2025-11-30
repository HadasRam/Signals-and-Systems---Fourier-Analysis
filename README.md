# Signals & Systems – Recitation 2  
This document summarizes key theoretical concepts and solved examples from Recitation 2 in the Signals & Systems course. The material covers convolution (linear and cyclic), Fourier series analysis, and Parseval’s identity, with detailed step-by-step mathematical derivations.

## 📘 Topics Covered
- **Linear Convolution**
  - Definition for continuous and discrete signals
  - Analytical formulation: z[n] = Σ x[m]·y[n−m]

- **Cyclic Convolution**
  - Definition for periodic continuous and discrete signals
  - Cyclic convolution using modulo indexing  
  - Construction of a **circulant matrix** and convolution via matrix–vector multiplication
  - Worked example: g[n] = {1,3,5}, h[n] = {2,1,4}

- **Fourier Series Coefficients**
  - Computing ak and bk for periodic signals x[n], y[n]
  - Full derivation of coefficients for:
    - x[n] = sin(3π/4 · n)
    - y[n] = δ[n−1] (periodic extension)
  - Using Euler’s identity and exponential representation

- **Convolution Property in the Fourier Domain**
  - Proof that for z[n] = (x ⊛ y)[n],
    **ck = N · ak · bk**
  - Verification using the specific Fourier coefficients of x[n] and y[n]

- **Parseval’s Identity**
  - Continuous-time and discrete-time formulations
  - Full proof using orthogonality of exponentials
  - Application: evaluating Σ 1/(2k+1)²

## 🧪 Exercises Included
1. Periodicity of x[n], cyclic convolution with δ[n−1], Fourier coefficients, and convolution–multiplication property.
2. Fourier coefficients of a piecewise signal using:
   - Derivative property,
   - Time shifts,
   - Known reference waveforms.
3. Power calculation of periodic signals and evaluation of classic sums using Parseval.

## 🎓 Purpose
This document provides a compact and clear reference for key Fourier and convolution concepts in Signals & Systems. It is intended as a study companion for students reviewing the course material.

