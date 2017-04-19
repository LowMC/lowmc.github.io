---
title: LowMC
---

_Participate in the on-going [LowMC cryptanalysis challenge](challenge)._

LowMC is a family of block ciphers tailored to minimize their multiplicative
complexity. To serve different optimization needs, it offers a flexible
parameter set that can be tuned to specific applications. It thus offers
minimization of multiplicative depth, total number of multiplications, or
multiplication per encrypted bit.

LowMC utilizes the proven SPN design strategy with some refinements. One such
refinement is that the substitution layer is only partially filled with S-boxes
leaving a part of the state untouched. The linear layers are fixed,
pseudo-random affine mappings. 

Publications
------------
 * _Ciphers for MPC and FHE_ ([eprint](https://eprint.iacr.org/2016/687),
 [Springer](https://link.springer.com/chapter/10.1007/978-3-662-46800-5_17))

