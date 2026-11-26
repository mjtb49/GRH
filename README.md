# The Alpöge–Claude argument for Dirichlet GRH

*From theta derivatives to a zero-free half-plane*

[Read the manuscript (PDF)](manuscript.pdf) · [Standalone LaTeX source](manuscript.tex)

On GitHub, download the PDF and open it in a PDF reader to use the table of contents, cross-references, and Lean source links.

This manuscript gives an exposition of the argument of Levent Alpöge and Claude for the generalized Riemann hypothesis for Dirichlet *L*-functions. The exposition was prepared with OpenAI Codex and follows the readable edition of `grh-lean`. Superscript numbers lead to source notes with links to the corresponding Lean files. Notes headed *Comparison with Lean* explain changes to the argument and identify steps supplied by published theorems. [Upstream repository and attribution at commit `72fead1`](https://github.com/lsernau/grh-lean/tree/72fead102f663d5c7a407964a13dc0cf9d977207)

## Reading the manuscript

For the proof, start with Theorem 1.1 and continue at §2.1 (printed page 5). Chapters 2–3 deduce the assertion about zeros from three arithmetic estimates. Chapters 4–17 establish those estimates.

For an introduction to the method, §1.2 uses a binomial coefficient and the lemniscate sine to illustrate how divisibility can give information about primes. Sections 1.3–1.4 trace the argument in two directions. All numbered examples are optional and are listed on page v.
