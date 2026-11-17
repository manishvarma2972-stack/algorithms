# Algorithmic Foundations & Pseudocode Specifications

[![Topic: Algorithms](https://img.shields.io/badge/Domain-Computer%20Science-4B0082?style=flat-square&logo=academia)](https://en.wikipedia.org/wiki/Algorithm)
[![Format: Pseudocode](https://img.shields.io/badge/Format-Step--by--Step%20Pseudocode-008080?style=flat-square)](https://en.wikipedia.org/wiki/Pseudocode)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)

A formal repository of step-by-step algorithmic specifications documenting core numerical routines, number theory tests, mathematical series expansions, and deterministic control-flow logic.

---

## 🧭 Algorithmic Taxonomy

### 1. Number Theory & Divisibility
| Specification File | Algorithmic Problem | Technique / Bound |
| :--- | :--- | :--- |
| `prime.algo` | Prime verification test | Trial division up to $\lfloor\sqrt{N}\rfloor$ ($\mathcal{O}(\sqrt{N})$) |
| `multiplesof7.algo` | Divisibility filter for multiple of 7 | Modular congruence ($N \equiv 0 \pmod 7$) |

### 2. Decision Logic & Extremum Selection
| Specification File | Algorithmic Problem | Branching Strategy |
| :--- | :--- | :--- |
| `greatestoftwo.algo` | Selects maximum of two numerical inputs | Single conditional comparison |
| `greateshoftwonodup.algo` | Evaluates maximum while detecting duplicate equality | Multi-condition equality check |
| `greatestofthree.algo` | Finds global maximum across three inputs | Nested conditional decision tree |

### 3. Iterative Series Generation
| Specification File | Algorithmic Problem | Mathematical Sequence |
| :--- | :--- | :--- |
| `naturalnumbers.algo` | Generates sequence of natural numbers | $1, 2, 3, \dots, N$ |
| `uptoevennumbers.algo` | Generates consecutive even integers $\le N$ | $2, 4, 6, \dots, 2k \le N$ |
| `uptooddnumbers.algo` | Generates consecutive odd integers $\le N$ | $1, 3, 5, \dots, 2k - 1 \le N$ |
| `uptosquareseries.algo` | Generates perfect squares up to threshold $N$ | $k^2 \le N$ |
| `uptoNpowerN.algo` | Generates exponential progression series | $1^1, 2^2, \dots, N^N$ |

### 4. Bounded Accumulation & Cardinality
| Specification File | Algorithmic Problem | Invariant & Accumulator |
| :--- | :--- | :--- |
| `sum.algo` | Computes arithmetic sum $\sum_{i=1}^N i$ | Additive accumulator |
| `product.algo` | Multiplicative factorial / product $\prod_{i=1}^N i$ | Multiplicative accumulator |
| `sumandproduct.algo` | Dual single-pass evaluation of sum and product | Simultaneous two-variable accumulation |
| `howmanyevennumbers.algo` | Counts even integers within range | Modulo test counter increment |
| `howmanyevennumbers2.algo` | Step-skipping even counter | Range stepping without modulo |
| `howmanyoddnumbers.algo` | Counts odd integers within range | Modulo test counter increment |
| `howmanyoddnumbers2.algo` | Step-skipping odd counter | Direct index advancement |
| `howmanysquareseries.algo` | Computes count of square terms up to bound | Quadratic step evaluation |
| `howmanyNpowerN.algo` | Counts terms in self-power sequence | Exponential limit bound |

### 5. Multiplicative Arithmetic & Tabulation
| Specification File | Algorithmic Problem | Output Representation |
| :--- | :--- | :--- |
| `computenpowern.algo` | Scalar exponentiation evaluation $N^N$ | Single numeric value |
| `multiplicationtable.algo` | Standard 10-row product matrix for $N$ | Tabular text grid |
| `tablebook.algo` | Multi-table generation across integer ranges | Iterative nested table progression |

---

## 📐 Formal Structure

Every algorithm adheres to standard procedural conventions:
1. Explicit labeled states (`step-1: start`, `step-2: print ...`, `step-k: stop`).
2. Type and variable initialization (`PrimeCounter = 2`, `Sum = 0`).
3. Explicit conditional branches and jump targets (`if (condition): goto step-X`).
4. Deterministic termination guarantees with no infinite loops.

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
