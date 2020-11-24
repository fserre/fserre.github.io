---
layout: publication
type: project
showInHomepage: false
title: "F2Matrix"
language: "C++"
img: "/img/f2matrix.png"
source: https://github.com/fserre/F2Matrix
abstract: |
            F2Matrix is a linear algebra library for small matrices (of maximal size 8$\times$8) in $\mathbb F_2$, i.e. the Galois field with two elements. It supports matrix addition (and therefore subtraction), multiplication, transposition, inversion and rank computation.<br/> This library aims to provide high performance, an relies heavily on bit manipulation instructions. Particularly, it requires an x64, BMI2 capable processor (e.g. Intel Haswell or newer). It was used for <a href="https://doi.org/10.1109/ICASSP.2019.8682213">searching optimal Walsh-Hadamard transform algorithms for streaming</a>.
---
