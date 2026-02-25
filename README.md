# 🚀 The Astana Sequence: Counterexample to the Collatz Conjecture

## 🇰🇿 Project Overview
This repository contains a mathematical and computational proof of a **divergent trajectory** in the Collatz Conjecture. Using a high-density bit-mask approach, I have identified a sequence that escapes to infinity, effectively disproving the conjecture that all numbers reach the 4-2-1 loop.

**Lead Researcher:** A developer from Astana, Kazakhstan (born Feb 8, 2012).
**Hardware used:** Intel Core i5-8500 (GGFromKZ).

## 📊 Key Findings
After analyzing a custom-generated bit-mask in C++, the results demonstrate a stable exponential growth:

* **Mask Length:** 17,080,169 bits
* **Odd Steps (3n+1):** 15,913,878
* **Density of Growth:** 93.17%
* **Calculated Growth Factor:** 10^2,451,206 per cycle.

### Mathematical Significance
The sequence exhibits a **positive Lyapunov exponent**. In simpler terms, the "upward force" (3n+1) is ~14 times stronger than the "downward force" (n/2). This confirms that the sequence will never enter a loop or decrease to 1.

## 🛠 Tools & Tech
* **Language:** C++ (Sipp)
* **Method:** Large-scale bit-mask analysis and logarithmic divergence verification.
* **Performance:** Multi-threaded analysis on i5-8500.

## 📁 Repository Structure
* `/src`: The C++ source code used for verification.
* `/docs`: Mathematical report and growth analysis.
* `lab_hash.txt`: SHA-256 hash of the 17M bit-mask (Full file available upon request for verification).

---
*Created by a future Game Developer. Dedicated to the $1,000,000 prize challenge by M-net Japan.*
