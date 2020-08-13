# `ASTRAGAL`

`A` `STR`assen-like `A`lgorithm for `G`eneral m`A`trix multiplication with pee`L`ing

---

This repository contains a (tentatively) *high-performance*, *non-SIMD* implementation of a *Strassen-like* recursive-partitioning-based algorithm for general matrix multiplication.  

More in detail, the following approaches are exploited:

- Binary block-wise partitioning over *even dimensions*;
- *Peeling* as the *even-ification* strategy of choice.

The *peeling* implementation closely follows that described in [Huss-Lederman et al., 1996](https://ieeexplore.ieee.org/document/1392903).

---

This work has been originally produced in partial fulfilment of the requirements for the *2nd part* of the course on *Advanced Programming and Algorithmic Design* held at the University of Trieste (Spring Semester, 2020) by prof. Alberto Casagrande.  

Furthermore, such implementation is derived from [original work](https://github.com/albertocasagrande/AD_strassen_template) by prof. Alberto Casagrande, released under the [MIT License](https://github.com/albertocasagrande/AD_strassen_template/blob/master/LICENSE).
