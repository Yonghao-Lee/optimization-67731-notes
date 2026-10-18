# Optimization (HUJI 67731): Weekly Notes

Textbook-style study notes for **Optimization** (HUJI 67731, 2026–27). Each week's PDF can be read on its own:

- Every term is defined in plain words before it is used.
- Every proof is broken into numbered steps.
- Every idea comes with a worked numerical example.
- Every recitation exercise is solved in full.
- Common mistakes are flagged in boxes.

You need Linear Algebra 1–2 and calculus.

## Contents

| Week | Notes | What you will learn |
|---|---|---|
| 01 | [**week01.pdf**](week01.pdf) | **Lecture:** norms (ℓ1, ℓ2, ℓ∞, ℓ0), equivalence of norms, Cauchy–Schwarz with proof, eigenvalues and the spectral theorem, positive (semi)definiteness and its tests, Frobenius and spectral norms, linear systems, solving with Cholesky. **Recitation:** Exercises 1.1–1.8 (norm constants, condition number, matrix inner product, PSD entry facts, the PSD order). **LU handout:** Gaussian elimination as PA = LU, partial pivoting, forward and backward substitution, operation counts. Ends with practice problems with full solutions and a one-page cheat sheet. |

New weeks are added as the course goes on.

## How each week is organised

1. **Part A, the lecture**, rewritten as a textbook chapter.
2. **Part B, the recitation**: every exercise solved step by step and extended with numbers.
3. **Part C, extra recitation handouts**, when there are any.
4. **Practice problems** with full solutions, and a **cheat sheet**.

The colour-coded boxes are:

| Box | Colour | Meaning |
|---|---|---|
| DEF | green | definition |
| KEY IDEA | pink | intuition |
| FORMULA | purple | key fact, theorem or algorithm |
| EXAMPLE | blue | worked example or exercise |
| PITFALL | gold | common mistake |

## Building from source

```sh
pdflatex -interaction=nonstopmode week01.tex
pdflatex -interaction=nonstopmode week01.tex   # second run for the contents
```

## Sources and credits

- A. Wiesel, *Optimization – 67731* course notes (2026–27), the lecture and the recitations. The unit-ball figure in `figures/week01/` is Figure 1.1 of those notes.
- S. Boyd and L. Vandenberghe, *Convex Optimization*, used as a reference and cited as [BV].

These are unofficial student notes. If you find an error, please open an issue.
