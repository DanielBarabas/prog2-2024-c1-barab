# 2026-07-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.0991   |       1e-06    |   0.43188  |
| barab-szabi-2        |     8.66984  |       0.700325 |   0.44237  |
| barab-szabi-1        |     0.461204 |       0.411881 |   0.456167 |
| k-d_tree_polars      |     0.465094 |       0.422098 |   0.479572 |
| k-d_tree_pandas      |     0.474375 |       0.383792 |   0.548537 |
| Bori_Aron_solution-1 |     0.460349 |       0.546328 |   0.559138 |
| k-d_tree_sklearn     |     3.24412  |       1.17837  |   1.07976  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476838 |       0.449331 |   0.45139  |
| k-d_tree_polars      |     0.485174 |       0.430847 |   0.455236 |
| barab-szabi-1        |     0.48567  |       0.424883 |   0.457978 |
| k-d_tree_pandas      |     0.471929 |       0.393521 |   0.557065 |
| Bori_Aron_solution-1 |     0.47498  |       0.577603 |   0.570691 |
| k-d_tree_sklearn     |     0.477642 |       1.02515  |   1.08787  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471993 |       0.458745 |   0.46369  |
| k-d_tree_polars      |     0.467967 |       0.453958 |   0.469836 |
| barab-szabi-1        |     0.467299 |       0.456848 |   0.479758 |
| Bori_Aron_solution-1 |     0.479166 |       0.597503 |   0.553573 |
| k-d_tree_pandas      |     0.477354 |       0.410435 |   0.601577 |
| k-d_tree_sklearn     |     0.481023 |       1.06067  |   1.09099  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471451 |       0.52252  |   0.490663 |
| Bori_Aron_solution-1 |     0.471877 |       0.795724 |   0.563783 |
| k-d_tree_polars      |     0.471335 |       0.576975 |   0.57233  |
| barab-szabi-1        |     0.473489 |       0.563704 |   0.584471 |
| k-d_tree_pandas      |     0.475359 |       0.497534 |   0.734605 |
| k-d_tree_sklearn     |     0.479741 |       1.3122   |   1.17227  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47303  |       0.731246 |   0.527799 |
| Bori_Aron_solution-1 |     0.460353 |       1.44943  |   0.587537 |
| k-d_tree_polars      |     0.475781 |       0.951543 |   0.927271 |
| barab-szabi-1        |     0.482028 |       0.919088 |   0.961356 |
| k-d_tree_pandas      |     0.474253 |       0.80125  |   1.1703   |
| k-d_tree_sklearn     |     0.477377 |       2.14692  |   1.23047  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466262 |        5.02039 |   0.736888 |
| Bori_Aron_solution-1 |     0.476313 |       10.7119  |   0.807093 |
| k-d_tree_sklearn     |     0.473537 |       16.2175  |   1.31312  |
| k-d_tree_polars      |     0.473648 |        5.35786 |   6.50383  |
| barab-szabi-1        |     0.470528 |        5.39101 |   6.64023  |
| k-d_tree_pandas      |     0.475714 |        4.34037 |   6.86147  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473225 |        70.1909 |    2.6555  |
| k-d_tree_sklearn     |     0.757555 |       234.91   |    4.17805 |
| Bori_Aron_solution-1 |     0.464271 |       149.494  |   27.2124  |