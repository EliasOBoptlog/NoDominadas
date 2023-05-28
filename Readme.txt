//////
Reads Pareto front solutions from the input file,
and writes the non-dominated solutions to the output file.
This program cleans a set of multiobjective solutions
It returns only the non-dominated and non-repeated solutions
It supports up to 999 solutions and 6 objective functions
It only supports minimization. Thus, for maximization multiply your objective value by -1
It reads a file named originalFront.dat, and the output goes to a file named efficientFront.dat
Elias Olivares-Benitez, March 17 2023
//////

This is the information required and structure in the data file (see the example file):

#solutions
#objectives
solution#	objective1	objective2	objective3 ...
...
