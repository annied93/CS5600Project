Project Summary: 

We are trying to study the performance of various algorithms. We will be doing a quantitive study on various parameters such as efficiency in cache memory, execution time, and how performance varies according to the workload.

Minimum Deliverables:

We will build a tool that will take in a binary for different algorithms and we will generate a report on the performance of these algorithms. We initially have planned to implement the following parameters:

- Time taken
- Time and Space Complexity Analysis
- Cache Hits
- Page Faults
- Branch Misprediction

Maximumm Deliverables:

Given a number of algorithms with different work loads, we will classify the algorithms and compare each class of algorithm against one another. We will then create graphs to visually the display results of each parameter we mention above.

Tools and Environment

We will be using C99, gdb for debugging and test on Ubuntu 16.04

Steps

First we will write a sample algorithm, make test data for it, and try to measure performance using the tools already present.

Find at least one related publication or tool and reference it here.

- https://www.openu.ac.il/personal_sites/download/galezer/efficiency.pdf 
- http://www.ams.org/notices/200103/fea-mcgeoch.pdf 
- https://ieeexplore.ieee.org/document/814600/?tp=&arnumber=814600&queryText%3Dcache%20oblivious 
- http://wgropp.cs.illinois.edu/projects/perf.htm

Performance analysis tools for Linux perf

Some Potential Problems:

We may have to build tools to improve the accuracy of our measurements and possibly make them OS and hardware independent.
