# Data Clustering Software

## CLUTO - Software for Clustering High-Dimensional Datasets

CLUTO is a software package for clustering low- and high-dimensional datasets and for
analyzing the characteristics of the various clusters. CLUTO is well-suited for
clustering data sets arising in many diverse application areas including information
retrieval, customer purchasing transactions, web, GIS, science, and biology.

CLUTO's distribution consists of both stand-alone programs and a library via which an
application program can access directly the various clustering and analysis
algorithms implemented in CLUTO.

**Features**

- Multiple classes of clustering algorithms:
  - partitional, agglomerative, & graph-partitioning based.
- Multiple similarity/distance functions:
  - Euclidean distance, cosine, correlation coefficient, extended Jaccard, user-defined.
- Numerous novel clustering criterion functions and agglomerative merging schemes.
- Traditional agglomerative merging schemes:
  - single-link, complete-link, UPGMA
- Extensive cluster visualization capabilities and output options:
  - postscript, SVG, gif, xfig, etc.
- Multiple methods for effectively summarizing the clusters:
  - most descriptive and discriminating dimensions, cliques, and frequent itemsets.
- Can scale to very large datasets containing hundreds of thousands of objects and tens of thousands of dimensions.


The CLUTO data clustering package is currently distributed as a single file that
contains binary distributions for Linux, OSX, and MS Windows platforms.


**Getting the files**

The first step in getting and using CLUTO is to download the binary distribution
file. CLUTO's distribution is available as either a Unix gziped tar file or as a
Windows zip file.

Available files for download

- Latest experimental release (2.1.2a):
  - [cluto-2.1.2a.tar.gz](/glaros/files/sw/cluto/cluto-2.1.2a.tar.gz).
  - [cluto-2.1.2a.zip](/glaros/files/sw/cluto/cluto-2.1.2a.zip). 

- Latest stable release (2.1.1):
  - [cluto-2.1.1.tar.gz](/glaros/files/sw/cluto/cluto-2.1.1.tar.gz).
  - [cluto-2.1.1.zip](/glaros/files/sw/cluto/cluto-2.1.1.zip).

Older versions of CLUTO can be found [here](/glaros/files/sw/cluto/OLD).

**Installing**

On Unix systems, after downloading CLUTO you need to uncompress and untar it. This is
achieved by executing the following command:

    gunzip cluto-xxx.tar.gz

    tar -xvf cluto-xxx.tar

Of course, 'xxx' is CLUTO's release number that you have downloaded. On Windows
systems, you need to have a zip/unzip program (e.g., winzip) in order to unzip the
files. In general, you just need to double click on "cluto-xxx.zip" and the file will
be unzipped automatically.

At this point you should have a directory named cluto-xxx. This directory contains
CLUTO's library, stand-alone clustering programs, and some test datasets.

**Documentation**

Instructions describing how to use CLUTO can be found at cluto-xxx/manual.pdf. You
can get a PDF copy from [here](/glaros/files/sw/cluto/manual.pdf).

**Converting Documents into CLUTO's Format**

A simple perl script called doc2mat that convertes a set of documents into the
vector-space format used by CLUTO is provided by downloading the following tar file:
[doc2mat-1.0.tar.gz](/glaros/files/sw/cluto/doc2mat-1.0.tar.gz).

You can read its online documentation from
[here](/glaros/files/sw/cluto/doc2mat.html)..

**Datasets**

The various datasets used in evaluating the performance of CLUTO's clustering
algorithms are available by downloading
[datasets.tar.gz](/glaros/files/sw/cluto/datasets.tar.gz).

Finally, the various datasets used in evaluating the Chameleon clustering algorithm
are available by downloading
[chameleon-data.tar.gz](/glaros/files/sw/cluto/chameleon-data.tar.gz).


**Copyright & License Notice**

CLUTO is copyrighted by the Regents of the University of Minnesota. It can be freely
used for educational and research purposes by non-profit institutions and US
government agencies only. Other organizations are allowed to use CLUTO only for
evaluation purposes, and any further uses will require prior approval. The software
may not be sold or redistributed without prior approval. One may make copies of the
software for their use provided that the copies, are not sold or distributed, are
used under the same terms and conditions.

As unestablished research software, this code is provided on an "as is'' basis
without warranty of any kind, either expressed or implied. The downloading, or
executing any part of this software constitutes an implicit agreement to these terms.
These terms and conditions are subject to change at any time without prior notice.


## gCLUTO - Graphical Clustering Toolkit

gCLUTO is a cross-platform graphical application for clustering low- and
high-dimensional datasets and for analyzing the characteristics of the various
clusters. gCLUTO is build on-top of the CLUTO clustering library.

gCLUTO provides tools for visualizing the resulting clustering solutions using tree,
matrix, and an OpenGL-based mountain visualization.

The gCLUTO data clustering package is distributed as a single file that contains
binary distributions for Linux, and MS Windows platforms.

**Getting the files**

The first step in setting up gCLUTO is to download the binary distribution file.
gCLUTO's distribution is available as either a Unix gziped tar file or as a Windows
zip file.

Available files for download:
- [gcluto-1.0.tar.gz](/glaros/files/sw/gcluto/gcluto-1.0.tar.gz).
- [gcluto_1_0.zip](/glaros/files/sw/gcluto/gcluto_1_0.zip).

Older versions of gCLUTO can be found [here](/glaros/files/sw/gcluto/OLD).

**Installing**

On Unix systems, after downloading gCLUTO you need to uncompress and untar it. This
is achieved by executing the following command:

    gunzip gcluto-1.0.tar.gz

    tar -xvf gcluto-1.0.tar

On Windows systems, you need to have a zip/unzip program (e.g., winzip) in order to
unzip the files. In general, you just need to double click on "gcluto_1_0.zip" and
the file will be unzipped automatically.

At this point you should have a directory named gcluto-1.0. This directory contains
gCLUTO's programs and some test datasets.

**Documentation**

Instructions describing how to use gCLUTO can be found at gcluto-1.0/doc/index.html.
You can view a local copy of this documentation by clicking
[here](/glaros/files/sw/cluto/manual/index.html).



