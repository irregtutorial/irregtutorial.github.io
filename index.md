**Tutorial:** Extending Loop Transformation Frameworks to Irregular Applications

**Location:** PPoPP’20 tutorial, San Diego, CA

**Date:** Sunday February 23, 2020 from 1pm PT to 5pm PT [Agenda link](https://ppopp20.sigplan.org/program/program-PPoPP-2020?date=Sun%2023%20Feb%202020)

Loop transformation frameworks such as the polyhedral model enable expressing complex loop
nests and composing transformations on such loop nests. The transformations enable
parallelism and improve data locality by modifying the schedule of the loop and in some cases
transformations are applied to the underlying data as well. The limit that such transformation
frameworks are only applicable when loop bounds and memory accesses are affine is starting
to be overcome with transformation frameworks that cater to various forms of irregular
computations. The general concepts of modeling the set of computation with an iteration space,
modeling how “iterations” access data, and then providing transformation specifications that can
be checked for correctness are similar. What is new is how information that is not known until
runtime is represented and transformed at compile time.

This tutorial will review the concept of representing computations as sets and loop
transformations being applied to those set. There will then be three different perspectives for
representing and transforming sparse computations, based on three recent lines of work: the
Sparse Polyhedral Framework, which builds inspector-executor frameworks for handling sparse
computations through runtime scheduling; decomposing sparse irregular computations into sets
of regular computations to enable compile-time transformation; and the PolyRec framework,
which handles certain recursive irregular computations at compile time through new
representations of iterations and transformations. We will provide high level overviews of at
least two frameworks and provide examples of the uses of each, including discussions of when
each framework might be applicable.

An outline of tutorial content and objectives
1. Introduction to concepts for analyzing and transforming affine programs, and discussion
of limitations
2. introduction to Sparse-immutable computations, and their optimization with the polyhedral framework
2. Introduction to the Sparse Polyhedral framework for loop-based sparse computations, discussion of applicability, and examples
3. Introduction to PolyRec for recursive computations, discussion of applicability, and examples


More information, including material to be presented at the tutorial will be posted prior to Feb. 23, 2020.

## Presenters

Milind Kulkarni is an associate professor in electrical and computer engineering at Purdue
University. His research focuses on analyzing, transforming, and parallelizing irregular
applications. His recent work focuses on how to adapt transformations that arise in the world of
affine loop programs to work for recursive, irregular applications. For his work on irregular
programs, he has received an NSF Career Award, a DOE Early Career Award, and the
Presidential Early Career Award for Scientists and Engineers.


Louis-Noel Pouchet is an Associate Professor of Computer Science at Colorado State University, with a Joint Appointment in the Electrical and Computer Engineering department at CSU. He works on a variety of topics for high-performance computing, including optimizing compilers for CPUs, GPUs and FPGAs, domain-specific languages and optimizations, machine learning, high-level synthesis, and distributed systems for large-scale scientific computing. Pouchet is a leading expert in polyhedral compilation, a mathematical framework for program optimization. His research is funded by the U.S. National Science Foundation, the U.S. Department of Energy, and Intel. He is the main author of the PoCC polyhedral compiler, of the ROSE ⁄ PolyOpt software toolset (a complete polyhedral compilation framework for the LLNL ROSE compiler), and of the popular PolyBench ⁄ C benchmarking suite, which has been used in 200+ publications so far. 


Michelle Strout is a professor in the Department of Computer Science at the University of Arizona.
Prof. Strout's main research area is high performance computing and her research interests
include compilers and run-time systems, scientific computing, and software engineering.
Michelle received an NSF CAREER Award for her research in parallelization techniques for
irregular applications, such as molecular dynamics simulations. She received a DOE Early
Career award to fund her research in separating the specification of scientific computing
applications from the specification of implementation details such as how to parallelize such
computations. Some of Prof. Strout's research contributions include the Universal Occupancy
Vector (UOV) for determining storage mappings for any legal schedule in a stencil computation,
the Sparse Polyhedral Framework (SPF) for specifying inspector-executor loop transformations,
dataflow analysis for MPI programs, parameterized and full versus partial tiling with the outset
and insets, and loop chaining for scheduling across stencil loops.

