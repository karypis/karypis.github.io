## Graph Partitioning

This project is the longest running research activity in the lab and dates back to
the time of George's PhD work. The fundamental problem that is trying to solve is
that of splitting a large irregular graphs into k parts. This problem has
applications in many different areas including, parallel/distributed computing (load
balancing of computations), scientific computing (fill-reducing matrix re-orderings),
EDA algorithms for VLSI CAD (placement), data mining (clustering), social network
analysis (community discovery), pattern recognition, relationship network analysis,
etc.

The partitioning is usually done so that it satisfies certain constraints and
optimizes certain objectives. The most common constraint is that of producing
equal-size partitions, whereas the most common objective is that of minimizing the
number of cut edges (i.e., the edges that straddle partition boundaries). However, in
many cases, different application areas tend to require their own type of constraints
and objectives; thus, making the problem all that more interesting and challenging!

The research in the lab is focusing on a class of algorithms that have come to be
known as multilevel graph partitioning algorithms. These algorithms solve the problem
by following an approximate-and-solve paradigm, which is very effective for this as
well as other (combinatorial) optimization problems.

Over the years we focused and produced good solutions for a number of
graph-partitioning related problems. This includes partitioning algorithms for graphs
corresponding to finite element meshes, multilevel nested dissection, parallel
graph/mesh partitioning, dynamic/adaptive graph repartitioning, multi-constraint and
multi-objective partitioning, and circuit and hypergraph partitioning.

Our latest research is focusing on three key areas:

* Mesh/graph partitioning algorithms that take into the fine-grain characteristics of
the underlying parallel computer and can deal with heterogeneous computing and
communication capabilities.

* Partitioning/load-balancing algorithms for mesh-less or mesh/particles scientific
simulations.

* Partitioning algorithms for scale-free graphs and/or graphs whose degree distribution
follows a power-low curve.

The research over the years has been funded by a number of Federal agencies including
DOE, ARO, ARL, NSF and companies including IBM, SGI, and Cray.


### Software

A direct outcome of our graph partitioning research is the development of the METIS
family of multilevel partitioning programs and libraries. This includes
computationally efficient and highly effective tools for partitioning very large
graphs on serial and parallel computers as well as tools for partitioning
hypergraphs, especially those corresponding to netlists of VLSI circuits.

In addition, some ideas inspired from the multilevel optimization algorithms
developed for graph partitioning found their way on two other research projects. The
first is the work on MGridGen, a tool to generate a sequence of coarse grids for
geometric multigrid-based precoditioners. The second is the work on CLUTO, our data
clustering tool, which contains effective graph-partitioning based clustering
algorithms. In fact, the quality of the partitionings produced by CLUTO are in
general better than those produced by the serial graph partitioning algorithm in
METIS.

All of these tools are available for download from our [Software
page](../software/overview.md).
