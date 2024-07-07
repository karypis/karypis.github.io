# Software tools developed by the lab

Over the years, the research in the lab has resulted in the development of a number
of software tools and libraries for key problems in the areas of parallel processing,
data mining, bioinformatics, and collaborative filtering.

It is our general policy to make these tools available to the research community for
use in their own research and/or non-commercial applications.


## METIS: A Family of Multilevel Partitioning Algorithms

This is a collection of serial and parallel programs & libraries that can be used to
partitioning unstructured graphs, finite element meshes, and hypergraphs, both on
serial as well as on parallel computers. 

Additional information can be found [here](./metis/overview.md).


## CLUTO: Software for Clustering High-Dimensional DataSets

This is a collection of computationally efficient and high-quality data clustering
and cluster analysis programs & libraries, that are well suited for high-dimensional
data sets.

Additional information can be found [here](./cluto/overview.md).


## BDMPI: Big Data Message Passing Interface

BDMPI is a message passing library and associated runtime system for developing
out-of-core distributed computing applications for problems whose aggregate memory
requirements exceed the amount of memory that is available on the underlying
computing cluster.

Additional information can be found [here](./bdmpi/overview.md).


## SLIM - Sparse Linear Methods for Top-N Recommender Systems

This is a library that implements a set of top-N recommendation methods that learn an
item-item similarity matrix using sparse linear models.

SLIM is available on [Github](https://github.com/KarypisLab/SLIM).



## NERSTRAND - Multi-threaded modularity-based graph clustering

This is a program that implements various serial and parallel modularity-based graph
clustering algorithms based on the multilevel paradigm. These algorithms can produce
high-quality clustering solutions and can scale to very large graphs.

NERSTRAND is available on [Github](https://github.com/dlasalle/nerstrand).


## SPLATT - Parallel Sparse Tensor Decomposition

This is a program that implements various serial and parallel modularity-based graph
clustering algorithms based on the multilevel paradigm. These algorithms can produce
high-quality clustering solutions and can scale to very large graphs.

SPLATT is available on [Github](https://github.com/ShadenSmith/splatt).


## L2AP - Fast Cosine Similarity Search With Prefix L-2 Norm Bounds

This is a program that implements various fast algorithms for for finding the set of
all pairs of similar vectors (e.g., documents) whose similarity is greater than a
user-specified threshold.

L2AP is available [here](https://davidanastasiu.net/software/l2ap/).


## L2Knng - Fast K-Nearest Neighbor Graph Construction with L2-Norm Pruning

This is a program that provides high-performance implementations of several methods
for constructing the K-nearest neighbor graph of a set of vectors based on cosine
similarity.

L2Knng is available [here](https://davidanastasiu.net/software/l2knng/).


## PAFI: Software for Finding Patterns in Diverse Datasets

This is a collection of computationally efficient programs for finding frequent
patterns in transactional, sequential, and graph datasets.

Additional information can be found [here](./pafi/overview.md).


## AFGen: Fragment-based Descriptors for Chemical Compounds

AFGen is a program that takes as input a set of chemical compounds and generates
their vector-space representation based on the set of fragment-based descriptors they
contain. The descriptor space consists of graph fragments that can have three
different types of topologies: paths (PF), acyclic subgraphs (AF), and arbitrary
topology subgraphs (GF). This vector-based representation can be used for different
tasks in cheminformatics including similarity search, virtual screening, and library
design.

These descriptors are quite effective in capturing the structural characteristics of
chemical compounds. Experiments in the context of SVM-based classification and
ranked-retrieval show that these descriptors consistently and statistically
outperform previously developed schemes based on the widely used fingerprint- and
Maccs keys-based descriptors, as well as recently introduced descriptors obtained by
mining and analyzing the structure of the molecular graphs.

**Getting the files**

* [afgen-2.0.0.tar.gz Linux (i686/x86_64)](files/afgen/afgen-2.0.0.tar.gz)

**Installing**

On Unix systems, after downloading AFGen you need to uncompress and untar it. This is
achieved by executing the following command:

    gunzip afgen-2.0.0.tar.gz
    tar -xvf afgen-2.0.0.tar

At this point you should have a directory named afgen-2.0.0. This directory contains
AFGen's stand-alone programs, its documentation, and a sample dataset.

**Documentation**

Instructions describing how to use AFGen can be found at afgen-2.0/doc/index.html.



## SUGGEST: A top-N Recommender Engine

SUGGEST is a Top-N recommendation engine that implements a variety of recommendation
algorithms. Top-N recommender systems, a personalized information filtering
technology, are used to identify a set of N items that will be of interest to a
certain user. In recent years, top-N recommender systems have been used in a number
of different applications such to recommend products a customer will most likely buy;
recommend movies, TV programs, or music a user will find enjoyable; identify
web-pages that will be of interest; or even suggest alternate ways of searching for
information.

The algorithms implemented by SUGGEST are based on collaborative filtering that is
the most successful and widely used framework for building recommender systems.
SUGGEST implements two classes of collaborative filtering-based top-N recommendation
algorithms, called user-based and item-based.

SUGGEST is currently distributed in a binary format and consists a stand-alone
executable program and a library, which can be used to call SUGGEST's routines
directly from another application.

**Getting the files**

The first step in using SUGGEST is to download the distribution file for your architecture.

- [suggest-1.0-linux.tar.gz](/glaros/files/sw/suggest/suggest-1.0-linux.tar.gz).
- [suggest-1.0-win32.zip](/glaros/files/sw/suggest/suggest-1.0-win32.zip).

**Installing**

After downloading SUGGEST you need to uncompress and untar it. This is achieved by executing the following command:

    gunzip suggest-1.0-xxxxx.tar.gz
    tar -xvf suggest-1.0-xxxxx.tar

At this point you should have a directory named suggest-1.5-xxxxx. This directory
contains SUGGEST's stand-alone programs and its user-callable library.

**Documentation**

Instructions describing how SUGGEST is used can be found at suggest-1.0-xxxxx/manual.pdf.
You can get a local copy of this manual in PDF format from
[here](/glaros/files/sw/suggest/manual.pdf)..



## MGridGen: Multilevel Serial & Parallel Coarse Grid Construction Library

MGridGen is a parallel library written entirely in ANSI C that implements (serial)
algorithms for obtaining a sequence of successive coarse grids that are well-suited
for geometric multigrid methods. The quality of the elements of the coarse grids is
optimized using a multilevel framework. It is portable on most Unix systems that have
an ANSI C compiler.

An MPI-based parallel version of MGridGen, called ParMGridGen, has also been
developed that extends the functionality provided by MGridGen and is especially
suited for large scale numerical simulations. It is written entirely in ANSI C and
MPI and is portable on most parallel computers that support MPI.

[Source code](https://github.com/mrklein/ParMGridGen)



## PSPASES: A Parallel Sparse Direct Solver

PSPASES (Parallel SPArse Symmetric dirEct Solver) is a high performance, scalable,
parallel, MPI-based library, intended for solving linear systems of equations
involving sparse symmetric positive definite matrices. The library provides various
interfaces to solve the system using four phases of direct method of solution:
compute fill-reducing ordering, perform symbolic factorization, compute numerical
factorization, and solve triangular systems of equations. The library efficiently
implements the scalable parallel algorithms developed by lab members and our
collaborators, to compute each of the phases.





