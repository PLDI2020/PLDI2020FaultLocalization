# DeepRL4FL: Improving Fault Localization via Representation Learning

In this paper, we propose DeepRL4FL, a deep learning fault localization (FL) approach that exploits the full details of the code coverage matrix, and the execution paths and data dependencies among statements in order to locate the buggy
code at the statement and method levels. DeepRL4FL first enhance a code coverage matrix by ordering test cases using their relations and marking error-exhibiting code statements using the information from the failing test cases. Second,
DeepRL4FL dynamically and statically builds statement dependencies through execution paths and data-flow graphs. Third, DeepRL4FL combines statement dependencies with the enhanced matrix for better fault localization. Our empirical
studies show that DeepRL4FL can outperform every studied baseline and localize 245 bugs from Defects4J, a wellknown benchmark, which is the most in the FL literature. DeepRL4FL improves the top-1 results of baselines by up
to 491.7%. Furthermore, our sensitivity analysis shows that each of our designed components contributes to DeepRL4FL.

----------
# This repository is still under clearing and re-formating. 

# Run our model

Run main.py

# Gzoltar

Gzoltar is used for code coverage analysis

# Sub-tree

Sub-Tree based code representation tool

