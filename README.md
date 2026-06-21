# Fundamental Theorem of Isomorphism in Group Theory

![Topic](https://img.shields.io/badge/Topic-Abstract%20Algebra-blue)
![Field](https://img.shields.io/badge/Field-Group%20Theory-purple)
![Document](https://img.shields.io/badge/Compiled%20With-LaTeX-47A141?style=flat&logo=latex&logoColor=white)
![Institution](https://img.shields.io/badge/Research-NISER%20Bhubaneswar-red)

This repository contains the complete research report, source LaTeX files, and structural chapters compiled during my summer research internship at the **National Institute of Science Education and Research (NISER), Bhubaneswar**.

---

## 📑 Read the Full Report
The complete, professionally typeset research project report can be read directly here:
📄 **[Download/View Project Report PDF](./Fundamental_Theorem_Isomorphism_Report.pdf)**

---

## 🏫 Internship Overview
* **Institution:** School of Mathematical Sciences, National Institute of Science Education and Research (NISER), Bhubaneswar
* **Supervisor:** Dr. Binod Kumar Sahoo
* **Timeline:** 13 May 2024 – 9 July 2024
* **Objective:** A rigorous mathematical investigation into the structural mapping of algebraic groups, culminating in an in-depth analysis of the First, Second, and Third Isomorphism Theorems.

---

## 🧠 Core Mathematical Framework

The core focus of this research centers on the **First Fundamental Theorem of Isomorphism**. 

Let $G$ and $H$ be groups, and let $\phi: G \to H$ be a group homomorphism. The theorem states that the quotient group $G/\ker(\phi)$ is naturally isomorphic to the image $\text{im}(\phi)$. 

This structure is elegantly captured by the following commutative diagram mapping the canonical projection ($\pi$) and the induced isomorphism ($\bar{\phi}$):


\begin{tikzcd}
g \arrow[r] \arrow[d] & \phi(g) \\
Kg \arrow[ur, dashed, "\psi"']
\end{tikzcd}

φ
G ----------> H
|          ^
|          |
π |          | ι
v          |
G/Ker(φ) ----+
~_φ

### Report Roadmap & Structural Chapters:
1. **Introduction to Group Theory:** Establishing foundational axioms, symmetric structures, cyclic groups, and permutation frameworks.
2. **Subgroups:** Examining cyclic behavior, generator bounds, and the structural implications of Lagrange’s Theorem.
3. **Normal Subgroups & Quotient Groups:** Constructing well-defined cosmic structures via kernel-driven normal partitions and coset spaces.
4. **Homomorphisms & Isomorphism Mapping:** Analyzing structure-preserving map invariants, leading directly to the formulation and proofs of the fundamental isomorphism mechanics.

---

## 🛠️ Compiling the Source Code Locally

The document is modularly written using `\include{}` statements to separate chapters for seamless editing. To compile this project report locally from the raw LaTeX files, ensure you have a standard TeX distribution (such as TeX Live or MiKTeX) installed along with the `tikz-cd` and `amsrefs` packages, then execute:

```bash
pdflatex main.tex
```
