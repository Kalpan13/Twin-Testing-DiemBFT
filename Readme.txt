phase 4: Implementation of Twins and Testing of diemBFT

PLATFORM:

The software platforms that are used in testing the algorithm are:


OS: 
Windows-10 : WSL2 (Windows Sub-System for Linux)

Python Implementation:
CPython


Python Versions used to test:
Python 3.7.12


DistAlgo Version used for implementation:
1.1.0b15


Type of host:
Laptop


BUGS AND LIMITATIONS:
-- Sync up of validators is not possible
–- Depending on the system processing performance, the value of delta(highest time for executing one round) can change. Adjust the value of delta depending on the delta


MAIN FILES:
-- Scenario Executer : <path_of_project_folder>/src/scenario_executor.da
-- Scenario Generator: <path_of_project_folder>/test_generator.py
-- Network Playground : <path_of_project_folder>/src/network_playground.da
-- Validator(Replica): <path_of_project_folder>/src/validator.da


CODE SIZE:

1. Non-blank Non-comment lines of code:	1750	(Total)
2. Count was obtained using cloc command - cloc --force-lang="Python",da .


LANGUAGE FEATURE USAGE:
Project uses approximately 21 dictionary comprehensions, 11 set comprehensions, 6 list comprehensions, 6 await statements and about 9 receive handlers.


CONTRIBUTIONS:

Kalpan Tumdi: 
-- Designed Scenario Executer 
-- Designed Network Playground

Swetang Finviya:
-- Designed Scenario Generator 

Devansh Shah:
-- Devansh's Contribution.pdf  [The PDF contains psuedo code inspired by Phase 3 -
                                Scenario Executer submitted by Kalpan Tumdi]
-- As the file contains psuedo code, we were unable to incorporate the same in actual code.