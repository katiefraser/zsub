This software package implements the semantic subspace distance proposed in (1,2), is freely available and completely open source. This project has been developed thanks to the invaluable support from Zirak (www.zirak.it).

The software has been written in C++ and comprises tools for creating semantic spaces (using HAL - Hyperspace Analogous to Language), deriving their subspace representation using NMF (Non-Negative Matrix Factorisation), and ultimately computing the distance.

Included into the package there are also:
- implementation of Euclidean distance to measure distances between word occurrences in semantic spaces/subspaces
- a classifier based on the semantic subspace distance and the Euclidean distance.

The software package relies on Boost for some mathematical computations and Lemur for text processing.


References:

(1) "Semantic Spaces: Measuring the Distance between Different Subspaces"; by G. Zuccon, L. Azzopardi, C.J. van Rijsbergen; in QI 2009
(2) "Investigating Subspace Distances in Semantic Spaces"; by G. Zuccon, L. Azzopardi, E. Gasco; in IIR 2011.