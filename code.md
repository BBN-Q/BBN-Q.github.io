---
title: Code repositories
layout: posts
permalink: /code/
show_excerpts: false
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

Controlling quantum systems is a challenge. To address this challenge, BBN has developed many tools for the collection and analysis of experimental data relating to quantum information. Below is a brief and incomplete list of some software you'll find in our Github organization.

# Quantum control

## Software

  * [Auspex](https://github.com/BBN-Q/Auspex) -- a generic experimental framework for controlling instruments
  * [QGL](https://github.com/BBN-Q/QGL) -- Quantum Gate Language for creating quantum computing experiments 
  * [bbndb](https://github.com/BBN-Q/bbndb) -- experimental database supporting _Auspex_ and _QGL_


## Control hardware

Gateware and drivers for controlling BBN Advanced Pulse Sequencer (APS) instruments and COTS digitizers from [Alazar](https://www.alazartech.com/en/) and [Interconnect Systems](https://isipkg.com/solutions/sensor-processing/xmc-fpga-cards/)

  * [libaps2](https://github.com/BBN-Q/libaps2) -- control software and drivers for the current generation APS
  * [libaps](https://github.com/BBN-Q/libaps) -- control software and drivers for first generation APS
  * [libx6](https://github.com/BBN-Q/libx6) -- firmware and drivers for the X6-1000M transceiver card
  * [libalazar](https://github.com/BBN-Q/libalazar) -- firmware and drivers for the ATS9870 Alazar digitizer

# Analysis

Code for analysis and exploration of quantum Information

  * [Qlab.jl](https://github.com/BBN-Q/Qlab.jl) -- qubit experimental analysis code
  * [Cliffords.jl](https://github.com/BBN-Q/Cliffords.jl) -- Julia library for the Clifford group
  * [RandomQuantum.jl](https://github.com/BBN-Q/RandomQuantum.jl) -- tools for generating random quantum objects
  * [QuantumInformation.jl](https://github.com/BBN-Q/QuantumInformation.jl) -- quantum information tools written in Julia
  * [SchattenNorms.jl](https://github.com/BBN-Q/SchattenNorms.jl) -- completely bounded Schatten norms

# Simulation

  * [MESolve.jl](https://github.com/BBN-Q/MESolve.jl) -- a Lindblad master-equation solver
  * [QSimulator.jl](https://github.com/BBN-Q/QSimulator.jl) -- a simulator focused on qubit control
