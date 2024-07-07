# BDMPI - Big Data Message Passing Interface
*Current version: 0.2, 8/15/2015*

BDMPI is a message passing library and associated runtime system for developing
out-of-core distributed computing applications for problems whose aggregate memory
requirements exceed the amount of memory that is available on the underlying
computing cluster. BDMPI is based on the Message Passing Interface (MPI) and provides
a subset of MPI's API along with some extensions that are designed for BDMPI's memory
and execution model.

A BDMPI-based application is a standard memory-scalable parallel MPI program that was
developed assuming that the underlying system has enough computational nodes to allow
for the in-memory execution of the computations. This program is then executed using
a sufficiently large number of processes so that the per-process memory fits within
the physical memory available on the underlying computational node(s). BDMPI maps one
or more of these processes to the computational nodes by relying on the OS's virtual
memory management to accommodate the aggregate amount of memory required by them.
BDMPI prevents memory thrashing by coordinating the execution of these processes
using node-level co-operative multi-tasking that limits the number of processes that
can be running at any given time. This ensures that the currently running process(es)
can establish and retain memory residency and thus achieve efficient execution. BDMPI
exploits the natural blocking points that exist in MPI programs to transparently
schedule the co-operative execution of the different processes. In addition, BDMPI's
implementation of MPI's communication operations is done so that to maximize the time
over which a process can execute between successive blocking points. This allows it
to amortize the cost of loading data from disk over the maximal amount of
computations that can be performed.

Since BDMPI is based on the standard MPI library, it also provides a framework that
allows the automated out-of-core execution of existing MPI applications. BDMPI is
implemented in such a way so that to be a drop-in replacement of existing MPI
implementations and allow existing codes that utilize the subset of MPI functions
implemented by BDMPI to compile unchanged.

> The distribution of BDMPI contains a number of source files written entirely in ANSI C, and is currently designed for Linux systems.
> Getting the files
> 
> Latest stable release:
>  - [bdmpi-0.2.0.tar.gz](/glaros/files/sw/bdmpi/bdmpi-0.2.0.tar.gz).
> 
> After downloading BDMPI you need to uncompress it and untar it. This is achieved by
> executing the following command:
> 
>     tar -xzf bdmpi-x.y.z.tar.gz
> 
> At this point you should have a directory named bdmpi-x.y.z, This directory contains
> BDMPI's source code. To build BDMPI, follow the instructions in bdmpi-x.y.z/README.
> 
> Instructions describing how to use BDMPI can be found at
> [bdmpi-x.y.z/doc/refmap.pdf](/glaros/files/sw/bdmpi/doc/refmap.pdf)
> or [bdmpi-x.y.z/doc/html/index.html](/glaros/files/sw/bdmpi/doc/html/index.html)..

