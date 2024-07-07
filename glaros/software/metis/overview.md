# Family of Graph and Hypergraph Partitioning Software

## METIS - Serial Graph Partitioning and Fill-reducing Matrix Ordering
 *METIS stable version: 5.1.0, 3/30/2013; MT-METIS version: 0.7.3, 6/4/2020*

METIS is a set of serial programs for partitioning graphs, partitioning finite
element meshes, and producing fill reducing orderings for sparse matrices. The
algorithms implemented in METIS are based on the multilevel recursive-bisection,
multilevel k-way, and multi-constraint partitioning schemes developed in our lab.

The distribution of METIS 5.x contains a number of files that total to over 35,000
lines of code. It is written entirely in ANSI C, and is portable on most Unix systems
that have an ANSI C compiler (the GNU C compiler will do).

The first step in getting and using METIS is to download the distribution file for
your architecture.

- Latest stable release (5.1.0):
  [metis-5.1.0.tar.gz](/glaros/files/sw/metis/metis-5.1.0.tar.gz)

- Latest release of an OpenMP version of Metis' partitioning and ordering routines (0.6.0):
  [mt-metis-0.7.2.tar.gz](/glaros/files/sw/metis/mt-metis-0.7.2.tar.gz)

Older versions of METIS can be found [here](/glaros/files/sw/metis/OLD).

After downloading METIS you need to uncompress it and untar it. This is achieved by
executing the following commands:

    gunzip metis-5.x.y.tar.gz

    tar -xvf metis-5.x.y.tar

At this point you should have a directory named metis-5.x.y. This directory contains
METIS's source code. To build METIS, follow the instructions in the file
metis-5.x.y/Install.txt.

Instructions describing how to use METIS can be found at metis-5.x.y/manual/manual.pdf.
You can get a PDF copy from [here](/glaros/files/sw/metis/manual.pdf).



## ParMETIS - Parallel Graph Partitioning and Fill-reducing Matrix Ordering
*Current stable version: 4.0.3, 3/30/2013*

ParMETIS is an MPI-based parallel library that implements a variety of algorithms for
partitioning unstructured graphs, meshes, and for computing fill-reducing orderings
of sparse matrices. ParMETIS extends the functionality provided by METIS and includes
routines that are especially suited for parallel AMR computations and large scale
numerical simulations. The algorithms implemented in ParMETIS are based on the
parallel multilevel k-way graph-partitioning, adaptive repartitioning, and parallel
multi-constrained partitioning schemes developed in our lab.

The distribution of ParMETIS contains a number of files. It is written entirely in
ANSI C and MPI and is portable on most parallel computers that support MPI.


ParMETIS's distribution is available as a Unix gziped tar file.

Latest stable release: 
- [parmetis-4.0.3.tar.gz](/glaros/files/sw/parmetis/parmetis-4.0.3.tar.gz).

Older versions of ParMETIS can be found [here](/glaros/files/sw/parmetis/OLD).

After downloading ParMETIS you need to uncompress it and untar it. You can achieve
this by executing the following commands: 

    gunzip parmetis-4.x.y.tar.gz
    tar -xvf parmetis-4.x.y.tar

At this point you should have a directory named parmetis-4.x.y. This directory
contains ParMETIS's source code as well as a sample graph used for testing. To build
ParMETIS, follow the instructions in the file parmetis-4.x.y/Install.txt.

ParMETIS's manual that contains instructions on how to use ParMETIS can be found in the directory parmetis-4.x.y/manual.
You can get a PDF copy from [here](/glaros/files/sw/parmetis/manual.pdf).

**Copyright & License Notice**

ParMETIS is copyrighted by the Regents of the University of Minnesota. It can be
freely used for educational and research purposes by non-profit institutions and US
government agencies only. Other organizations are allowed to use ParMETIS only for
evaluation purposes, and any further uses will require prior approval. The software
may not be sold or redistributed without prior approval. One may make copies of the
software for their use provided that the copies, are not sold or distributed, are
used under the same terms and conditions.

As unestablished research software, this code is provided on an "as is'' basis
without warranty of any kind, either expressed or implied. The downloading, or
executing any part of this software constitutes an implicit agreement to these terms.
These terms and conditions are subject to change at any time without prior notice.




## hMETIS - Hypergraph & Circuit Partitioning
*Current version: 1.5.3, 11/22/98 [Alpha version: 2.0pre1, 5/24/07]*

hMETIS is a set of programs for partitioning hypergraphs such as those corresponding
to VLSI circuits. The algorithms implemented by hMETIS are based on the multilevel
hypergraph partitioning schemes developed in our lab.

hMETIS is distributed in a binary format and consists of a pair of stand-alone
executable programs and a library, which can be used to call hMETIS's partitioning
routines directly from another application.

The first step in getting and using hMETIS is to download the distribution file for
your architecture. The distribution of hMETIS consists of a Unix gziped tar file
(except the Win32 binary which is zip file).

Latest stable release (1.5.3):
  - [hmetis-1.5-linux.tar.gz](/glaros/files/sw/hmetis/hmetis-1.5-linux.tar.gz).
  - [hmetis-1.5-osx-i686.tar.gz](/glaros/files/sw/hmetis/hmetis-1.5-osx-i686.tar.gz).
  - [hmetis-1.5.3-WIN32.zip](/glaros/files/sw/hmetis/hmetis-1.5.3-WIN32.zip).

Latest experimental release (2.0pre1):
  - [hmetis-2.0pre1.tar.gz](/glaros/files/sw/hmetis/hmetis-2.0pre1.tar.gz).

Older versions of hMETIS can be found [here](/glaros/files/sw/hmetis/OLD)..

After downloading hMETIS you need to uncompress and untar it. This is achieved by
executing the following command:

    gunzip hmetis-1.5-xxxxx.tar.gz
    tar -xvf hmetis-1.5-xxxxx.tar

At this point you should have a directory named hmetis-1.5-xxxxx. This directory
contains hMETIS's stand-alone programs and hMETIS's user-callable library.

Instructions describing how hMETIS is used can be found at hmetis-1.5-xxxxx/manual.ps.
You can get a PDF copy from [here](/glaros/files/sw/hmetis/manual.pdf).


**Copyright & License Notice**

hMETIS is copyrighted by the Regents of the University of Minnesota. It can be freely
used for educational and research purposes by non-profit institutions and US
government agencies only. Other organizations are allowed to use hMETIS only for
evaluation purposes, and any further uses will require prior approval. The software
may not be sold or redistributed without prior approval. One may make copies of the
software for their use provided that the copies, are not sold or distributed, are
used under the same terms and conditions.

As unestablished research software, this code is provided on an "as is'' basis
without warranty of any kind, either expressed or implied. The downloading, or
executing any part of this software constitutes an implicit agreement to these terms.
These terms and conditions are subject to change at any time without prior notice.


