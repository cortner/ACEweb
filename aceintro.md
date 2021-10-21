+++
title = "ACE Introduction"
hascode = true
rss = "Brief intro to the ACE model"
+++
<!-- @def tags = ["syntax", "code"] -->
<!-- ### Introduction  -->

The Atomic Cluster Expansion (ACE) is a basis for the compact environment of a point, which can represent the geometry of neighbouring points or a continuous field. Its key features are that
- Symmetries can be easily imposed, e.g. permutation of the neighbouring points, or rotational symmetry (2D or 3D)
- The basis is ordered in term of _body order_ (for particles, i.e. 1-particle basis, 2-particle basis, 3-particle basis etc) or _correlation order_ (for continuous fields). This is advantageous because many models that we build using the ACE basis converge fast in this order. 

A particular use of ACE, and this is how it was originally introduced, is for describing the local environments of atoms in atomistic systems (molecules or solids). Very good nteratomic potentials (force fields) can be made as linear (or nonlinear) functions in the ACE basis. 

ACE encompasses (generalises) other local environment descriptors. For example, the Smooth Overlap of Atomic Positions (SOAP) descriptor in the limit of small Gaussian smearing on the neighbour atoms can be seen as the 3-particle component of the ACE basis, i.e. the _power spectrum_. The Spectral Neighbour Analysis Potential is based on the _bispectrum_, which is the 4-particle component of ACE. Moment Tensor Potentials can be obtained from ACE using a linear transformation. 

[Software](/software/)

[Publications](/publications/)