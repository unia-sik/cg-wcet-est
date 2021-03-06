# CG Timing Analysis
The CG benchmark originates from the NAS Parallel Benchmark Suite (Homepage: http://www.nas.nasa.gov/Software/NPB/ ) [1]. It implements "a conjugate gradient method used to compute an approximation to the smallest eigenvalue of a large, sparse, symmetric positive definite matrix. This kernel is typical of unstructured grid computations in that it tests irregular long-distance communication, using unstructured matrix-vector multiplication" [2].

We ported the CG benchmark to C, optimised it for better static timing analysability (in our case, we used OTAWA, see www.otawa.fr [3]) and made a timing analysis, which is described in [4]. Different parameters can be evaluated with the OpenDocument Spreadsheet.

 

[1] D. H. Bailey, E. Barszcz, J. T. Barton, D. S. Browning, R. L. Carter, L. Dagum, R. A. Fatoohi, P. O. Frederickson, T. A. Lasinski, R. S. Schreiber, H. D. Simon, V. Venkatakrishnan and S. K. Weeratunga. The NAS Parallel Benchmarks – Summary and Preliminary Results. In Proceedings of the 1991 ACM/IEEE Conference on Supercomputing, Supercomputing’91, pages 158–165, New York, NY, USA, 1991. ACM.

[2] D. H. Bailey, E. Barszcz, J. T. Barton, D. S. Browning, R. L. Carter, L. Dagum, R. A. Fatoohi, P. O. Frederickson, T. A. Lasinski, R. S. Schreiber, H. D. Simon, V. Venkatakrishnan and S. K. Weeratunga. The NAS parallel benchmarks. International Journal of High Performance Computing Applications, 5(3):63–73, 1991.

[3] C. Ballabriga, H. Cassé, C. Rochange and P. Sainrat. OTAWA: An Open Toolbox for Adaptive WCET Analysis. In Software Technologies for Embedded and Ubiquitous Systems, volume 6399 of LNCS, pages 35–46. Springer Berlin Heidelberg, 2011.

[4] M. Frieb, A. Stegmeier, J. Mische and T. Ungerer. Employing MPI Collectives for Timing Analysis on Embedded Multi-Cores. In 16th International Workshop on Worst-Case Execution Time Analysis (WCET 2016), OpenAccess Series in Informatics (OASIcs), Volume 55, Dagstuhl, Germany, 2016.
