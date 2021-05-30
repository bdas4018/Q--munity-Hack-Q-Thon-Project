# Q--munity-Hack-Q-Thon-Project

## Methods to improve the QAOA for Max-Cut

This repository contains Jupyter Notebooks of Qiskit implementations of various variants of QAOA with/without quantum and classical modifications of both weighted and unweighted graphs.
Note that : for analysis of run-time complexity and for analysis of probability of optimal solutions being pulled out, without loss of generality, I considered the implementations of the unweighted graphs. 

# Motivation :
The Max-Cut problem has been of continued research interest and has developed an extensive literature.. The Max-Cut problem is a well-known combinatorial optimization problem which aims to find a division of a vertex set into two parts maximizing the sum of weights over all the edges across the two vertex subsets in a given edge-weighted graph. When applied in various real-world fields, the weight of the cut in the Max-Cut problem has real and concrete implications. For example, for network design, the weight may represent the cost of some infrastructure. The Max-Cut problem has many applications in various fields such as network design, statistical physics and VLSI design, circuit layout design, and data clustering. Hence, in a nutshell, Max-cut has wide applications in various industries such as : Electronics Industry (Circuit design, VLSI design etc.), Finance Industry (Data clustering) etc. The Max-Cut problem is one of the first problems proved to be NP-hard, meaning that there are no strongly efficient exact algorithms. So many researchers turn their attention to find approximate algorithms and heuristic algorithms.
Hence, the main motivation was to improve upon existing heursitic algorithms like QAOA to solve Max-cut by introducing quantum or classical modifications or both.

# Implementations :

Here, the implementations of WS-QAOA and WS-QAOA w/ INTERP (on two simulators, namely : statevector_simulator and
qasm_simulator) are present and later on their performances are analysed in terms of depth (p) and running time complexity while comparing with
standard QAOA and QAOA w/ INTERP. This also contains noisy simulations (wherein a “noise model” from an actual quantum device was incorporated.) of the variants. 
