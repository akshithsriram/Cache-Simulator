# Cache-Simulator

This project involved the creation of a Cache Simulator. 

Given a list of instructions (Hexadecimal Format), it creates a virtual demonstration of a cache by implementing the replacement policy (also given in the input).
(Refer to [Problem_Statement.pdf](https://github.com/akshithsriram/Cache-Simulator/blob/main/Problem_Statement.pdf) for complete details)

Various details like no. of cache misses, no. of write accesses, no. of dirty blocks evicted are also written to the output file.

This simulator (through the various parameter values it outputs) helps understand the behaviour of a cache with different combinations of block sizes, associativity, and replacement policies. 

This can help understand which combinations are best suited to execute a given class of applications.

Project created as a part of the course CS2610: Computer Architecture and Organization.

Skills involved:
- Knowledge of various replacement policies
- Constructing a re-sizable cache after calculating required parameters.
- File I/O
- Decoding input instructions to obtain type of the instruction and memory addresses. 

