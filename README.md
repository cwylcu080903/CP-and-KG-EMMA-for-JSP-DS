# CP-and-KG-EMMA-for-JSP-DS

This repository contains the source code for the paper:

**Knowledge Graph-enhanced Evolutionary Multitasking Matheuristic Algorithm for Job Shop Scheduling Problem with Discrete Operation Sequence Flexibility**

## Overview

This paper studies the Job Shop Scheduling Problem with Discrete Operation Sequence Flexibility (JSPDS) and proposes:
(1) A novel CP model is formulated. To the best of our knowledge, this is the first CP model for the JSPDS, outperforming existing MILP model.
(2) A knowledge graph-enhanced evolutionary multitasking optimization (EMTO) framework is designed. The EMTO expands search knowledge from a single task to multiple tasks, providing more search knowledge than a single evolutionary algorithm. To avoid negative knowledge transfer from unrelated tasks, a knowledge graph is used to measure task relatedness, allowing the target task to select a suitable assisted task.
(3) A dual statistical learning-assisted local search is introduced. This technique controls the application of low-density and high-density search operators during the algorithm's execution, while also ensuring that individuals select the appropriate search operators.
(4) A CP-assisted evolutionary operator, as a kind of a matheuristic approach, is designed to overcome the limitations of the encoding and decoding scheme. It leverages the advantages of the mathematical model, where satisfying constraints naturally enable exploration of the entire solution space.


The proposed framework is referred to as **KG-EMMA**.
## Code Availability

The repository is currently under preparation.

The complete source code, experimental settings, and supplementary materials will be released after the acceptance of the corresponding manuscript.

## Benchmark Instances

The benchmark instances used in this work are publicly available at:

https://github.com/sdadaawa/JSPDS
