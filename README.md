# GA based CFLP solver

## A software for optimal allocation of cost centers given a set of open centers using genetic algorithm.

### About

The solution consist of a heuristic algorithm (**Genetic Algorithm**), which will be in charge of searching for good combinations of centers, and an exact algorithm (**AMPL + Gurobi**) which will be in charge to find the optimal assignment given a set of open centers. The algorithm should have as termination criteria a maximum number of iterations, entered by the user.

### Setup
In order to run this program you must follow the instruction below.

- Set an ampl path in the ```config.py``` file
- Install required packages with ```python -m pip install -r requirements.txt```

Important: Note that an AMPL license is mandatory in order to find solutions for linear problems with more than 500 variables, 500 constraints and objectives (after presolve) for linear problems.


*Homework for the Operations Research course (2022).*
