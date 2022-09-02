Monte Carlo Tree Search Planning
================================

Exercise 1
----------

Teamwork for groups of 2 students. The code must be delivered on Github or an equivalent versioning tool.

You must implement your own MCTS planner in PDDL4J. To that end, please follow the instructions given in the PDDL4J tutorial, section “Implement your own planner”. The code must be written in Java and properly documented. You do not have the implement a SAT solver. Please use SAT4J instead (see https://www.sat4j.org). Thus, your work will focus on the encoding of a planning problem into a SAT problem, and the decoding procedure that expresses the SAT solution as a plan.

Check plan validity with VAL (https://github.com/KCL-Planning/VAL). Details on the coding/decoding procedures are given in this article: xx.

Then, write a script (in bash shell, Python or Java only) to compare the performances of your MCTS planner with that of HSP (PDDL4J A* planner). The comparison will be made using the 4 benchmarks (blocksworld, depot, gripper and logistics) provided in the pddl/ folder of PDDL4J. You will use 2 metrics: the total runtime and the makespan (plan length). Represent your results as follows: problems on X axis ordered from the simplest to the most difficult for HSP. And, on Y axis the results of both HSP and your planner. Make a figure for each domain and each metric (in total, 8 figures). Which one is the best?

Include the script in the Github repository as well as the figures of yours results in a pdf document with the names of all the group students and the link to your repository.

Exercise 2
----------