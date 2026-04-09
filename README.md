[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmahi97%2FEE632-InformationTheory&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

# EE623 – Information Theory (KAIST, Fall 2020)

Problem set solutions for **EE623 Information Theory** at the Korea Advanced Institute of Science and Technology (KAIST).

---

## Course Overview

Information Theory, founded by Claude Shannon, provides the mathematical foundations for data compression, reliable communication, and the fundamental limits of information processing. This course covers classical topics from entropy and channel capacity to source–channel coding and the method of types.

**Student:** Mohammad Mahdi Rahimi  
**Student ID:** 20208244  
**Email:** mahi@kaist.ac.kr  
**Semester:** Fall 2020

---

## Repository Structure

Each folder contains a LaTeX source file (`main.tex`) with the full derivations and proofs for the corresponding problem set.

| Folder  | Assignment | Topics Covered |
|---------|-----------|----------------|
| `PSET1` | PSET 1    | Introduction & setup |
| `PSET2` | PSET 2    | KL Divergence, Data Processing Inequality, Fano's Inequality |
| `PSET3` | PSET 3    | Huffman Coding, Asymptotic Equipartition Property (AEP), Typical Sets |
| `PSET4` | PSET 4    | Source Coding with Side Information (Slepian–Wolf Theorem), Achievability & Converse |
| `PSET5` | PSET 5    | Strong vs. Weak Typicality |
| `PSET6` | PSET 6    | Channel Capacity, Optimal Input Distribution |
| `PSET7` | PSET 7    | Joint Typicality, Proofs of Information-Theoretic Inequalities |
| `PSET8` | PSET 8    | Decoding Error Probability, Fano's Theorem |
| `PSET9` | PSET 9    | Source–Channel Separation Theorem (Achievability & Converse) |
| `PSETA` | PSET 10   | Method of Types, Joint Type Classes, Type Counting |

---

## Building the PDFs

The solutions are typeset in LaTeX using the custom `aga-homework.cls` class included in the repository root.

**Prerequisites:**
- A standard LaTeX distribution (e.g., [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/))
- The following LaTeX packages: `amsmath`, `amssymb`, `amsthm`, `tikz`, `pgfplots`, `algorithm2e`, `graphviz`, `mathpazo`

**To compile a single problem set:**
```bash
cd PSET3
pdflatex main.tex
```

> **Note:** Some problem sets use `\tikzexternalize` for faster compilation of TikZ figures. Run `pdflatex` twice if figures do not appear on the first pass.

---

## Topics at a Glance

- **Entropy & Information Measures** – Shannon entropy, conditional entropy, mutual information, KL divergence
- **Data Processing & Inequalities** – Data processing inequality, log-sum inequality, Fano's inequality
- **Typical Sequences** – Weak and strong typicality, AEP, jointly typical sets
- **Source Coding** – Huffman coding, lossless compression limits, Slepian–Wolf coding
- **Channel Coding** – Channel capacity, achievability and converse, error exponents
- **Source–Channel Separation** – Joint source–channel coding theorem
- **Method of Types** – Type classes, exponential counting, large deviations

---

## References

- T. M. Cover and J. A. Thomas, *Elements of Information Theory*, 2nd ed., Wiley, 2006.
- Lecture notes for EE623, KAIST, Fall 2020.

---

## License

This repository contains personal coursework solutions shared for educational reference. Please do not submit these solutions as your own work.
