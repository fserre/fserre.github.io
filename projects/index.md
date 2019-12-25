---
layout: page
title: Projects
---


<div class="row">
  <div class="col-md-12">
    <p>
        <a href="https://github.com/fserre/F2Matrix">F2Matrix</a> <br />
F2Matrix is a linear algebra library for small matrices (of maximal size $8\times 8$) in $\mathbb F2$, i.e. the Galois field with two elements. It supports matrix addition (and therefore subtraction), multiplication, transposition, inversion and rank computation.<br/>

This library aims to provide high performance, an relies heavily on bit manipulation instructions. Particularly, it requires an x64, BMI2 capable processor (e.g. Intel Haswell or newer). It was used for <a href="https://doi.org/10.1109/ICASSP.2019.8682213">searching optimal Walsh-Hadamard transform algorithms for streaming</a>.
    </p>
  </div>
</div>

<div class="row">
  <div class="col-md-12">
    <p>
        <a href="https://acl.inf.ethz.ch/research/hardware/">SGen - A Streaming Hardware Generator</a> <br />
SGen is a generator capable of producing efficient hardware designs operating on *streaming* datasets. “Streaming” means that the dataset is divided into several chunks that are processed during several cycles, thus allowing a reduced use of resources. The size of these chunks is referred as the streaming width. It outputs a Verilog file that can be used for FPGAs.<br/>
<a href="https://acl.inf.ethz.ch/research/hardware/">Project description</a> <br />
<a href="https://github.com/fserre/sgen">Source</a> <br />
    </p>
  </div>
</div>
