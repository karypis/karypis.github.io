# PAFI Software Package for Finding Frequent Patterns in Diverse Datasets

*Current version: 1.0.1, 7/7/2003*

PAFI is a software package that contains a set of programs that can be used to find
frequent patterns in large and diverse databases.

The current release of PAFI includes three different pattern discovery programs:

-**LPMiner**: It is designed to find patterns corresponding to itemsets in a
transaction database.

-**SLPMiner**: It is designed to find patterns corresponding to sub-sequences in a
sequential database.

-**FSG**: It is designed to find patterns corresponding to connected undirected
subgraphs in an undirected graph database.

These programs can be used to mine a wide-range of datasets arising in commercial,
information retrieval, and scientific applications.

All three programs can be used to find patterns that satisfy a constant minimum
support. A key feature of LPMiner and SLPMiner is that they can find long frequent
patterns without finding a large number of short patterns that are often useless.
This is achieved by using length-decreasing support constraints, where the minimum
occurrence frequency of a pattern is given as a non-increasing function of pattern
length.

PAFI's pattern discovery programs usually provide three additional functionalities.
First, all three programs can generate maximal frequent patterns. A maximal frequent
pattern is a frequent pattern that is not contained by any other frequent patterns.
Generally, the number of maximal frequent patterns is much smaller than the number of
all the frequent patterns, leading to higher readability of frequent pattern files.
Second, SLPMiner and FSG can generate transaction-ID lists (TID-lists) indicating
which sequences or graph transactions support a particular frequent pattern. Third,
all three programs can generate parent-children lists (PC-lists) that can be used to
construct the frequent pattern lattice.

The PAFI pattern discovery package is currently distributed as a single file that contains binary distributions for Linux and Sun platforms.

Available files for download:
-[pafi-1.0.1.tar.gz](/glaros/files/sw/pafi/pafi-1.0.1.tar.gz).
-[pafi-1.0.1.zip](/glaros/files/sw/pafi/pafi-1.0.1.zip). 

Older versions of PAFI can be found [here](/glaros/files/sw/pafi/OLD).

On Unix systems, after downloading PAFI you need to uncompress and untar it. This is achieved by executing the following command:

    gunzip pafi-1.0.1.tar.gz
    tar -xvf pafi-1.0.1.tar

On Windows systems, you need to have a zip/unzip program (e.g., winzip) in order to
unzip the files. In general, you just need to double click on "pafi-1.0.1.zip" and
the file will be unzipped automatically.

At this point you should have a directory named pafi-1.0.1. This directory contains
PAFI's programs and some test datasets.

Instructions describing how to use PAFI can be found at pafi-1.0.1/manual.pdf. You
can get a local copy of this documentation from
[here](/glaros/files/sw/pafi/manual.pdf).
