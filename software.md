@def title = "Software"


The following is an incomplete list of implementations of the ACE model or closely related models that we are aware of. Different implementations focus on different aspects, e.g. evaluation or parameterisation, linear vs nonlinear models, and may incorporate different physics (charge transfer, magnetism, polarisation, etc). 

* [PACE](https://docs.lammps.org/pair_pace.html) : "Performant implementation of the atomic cluster expansion"
  - C++ evaluation-only code with LAMMPs interface
  - currently supports the original linear ACE model (Drautz, 2019)
  - fitting methodology provided through related python packages, and ACE.jl
* [pacemaker](https://github.com/ICAMS/python-ace)
  - Python package for fitting ACE potentials
  - compatible with PACE
  - using [tensorpotential](https://github.com/ICAMS/TensorPotential) - an implementation of ACE in Tensorflow
  - Paper:  [Bochkarev, A., Lysogorskiy, Y., Menon, S., Qamar, M., Mrovec, M. and Drautz, R. Efficient parametrization of the atomic cluster expansion. Physical Review Materials 6(1) 013804 (2022)](https://journals.aps.org/prmaterials/abstract/10.1103/PhysRevMaterials.6.013804)
* [ACE.jl and ACEsuit](https://acesuit.github.io) 
   - open source Julia implementation for rapid prototyping
   - abstractions to enable applications in different domains
   - invariant as well and equivariant properties 
   - WIP: general symmetry groups
   - WIP: integration with Flux.jl for general nonlinearities
* ace-flow: WIP     
   - Implementation of ACE in Tensorflow
   - implements original ACE and recursive ACE 
* ace-torch: WIP 
   - builds on graph-NN facilities in torch

<!--
## Feature List 

|               | FS | Rnl | layers | cov |
|---            |--- |---  |---|--- |
|PACE           | y  | y   | n | n  |
|ACE.jl-stable  | n  | n   | n | n  |
|ACE.jl-dev     | y  | y   | ? | y  |
|ace-flow       | y  | y   | y | ?  |

Description of features: 
-->

## Related Models and Software 

* MTP : Moment Tensor Potentials
   - Alternative implementation of symmetric polynomials using moments instead of spherical harmonics; [Shapeev, SIAM Multiscale Modelling and Simulation, 2016](https://epubs.siam.org/doi/abs/10.1137/15M1054183)
   - [gitlab repository](http://gitlab.skoltech.ru/shapeev/mlip/); also available with [QuantumATK](https://www.synopsys.com/silicon/quantumatk.html)
