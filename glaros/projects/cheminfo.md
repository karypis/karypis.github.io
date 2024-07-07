## Chemical Informatics

Discovering new drugs is an expensive and challenging process. Any new drug should
not only produce the desired response to the disease but should do so with minimal
side effects and be superior to the existing drugs in the market. The goal of this
project is to develop effective and efficient algorithms for analyzing chemical
compound databases and identifying biologically active compounds.

One of the key steps in the drug design process is the identification of the chemical
compounds (hit compounds) that display the desired and reproducible behavior against
the specific biomolecular target and represents a significant hurdle in the early
stages of drug discovery. The 1990s saw the widespread adoption of high-throughput
screening (HTS), which use highly automated techniques to conduct the biological
assays and can be used to screen a large number of compounds. Although the number of
compounds that can be evaluated by these methods is very large, these numbers are
small in comparison to the millions of drug-like compounds that exist or can be
synthesized by combinatorial chemistry methods. Moreover, in most cases it is hard to
find all desirable properties in a single compound and medicinal chemists are
interested in not just identifying the hits but studying what part of the chemical
compound leads to desirable behavior, so that new compounds can be rationally
synthesized (lead development).

Computational techniques that build models to correctly assign chemical compounds to
various classes of interest can address these limitations, have extensive
applications in pharmaceutical research, and they are used extensively to replace or
supplement HTS-based approaches.

Our most recent research is currently concentrated on the following areas:

* Develop computationally efficient algorithms to mine large databases of molecular 
  graphs and identify key substructures present in active (inactive) compounds.

* Develop sophisticated feature selection and generation algorithms that combine
multiple criteria to identify and synthesize a set of substructure-based features
that simultaneously simplify the representation of the original compounds while
retaining and exposing their key features.

* Develop kernel-based clustering and classification approaches that take into
  account the relationships between these substructures at different levels of
  granularity and complexity.

The research over the years has been funded by a number of Federal agencies including
NIH (primary agency), ARL, and NSF.

### Software

Our research thus far has resulted in the development of computationally efficient
algorithms to find frequent substructures in molecular graphs (either topological or
geometric). The topological version of this algorithm, called FSG, is currently
available as part of our pattern discovery toolkit PAFI, which can be downloaded and
used for educational and research purposes.

Another recent development is the [AFGen](../software/overview.md) program that
operates on a database of chemical compounds and generates their descriptor-based
representation by considering all bounded length acyclic fragments that they contain.
These descriptors are quite effective in capturing the structural characteristics of
chemical compounds. Experiments in the context of SVM-based classification and
ranked-retrieval show that these descriptors consistently and statistically
outperform previously developed schemes based on the widely used fingerprint- and
Maccs keys-based descriptors, as well as recently introduced descriptors obtained by
mining and analyzing the structure of the molecular graphs.
