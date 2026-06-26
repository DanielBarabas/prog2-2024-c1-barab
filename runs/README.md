# 2026-06-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     9.38729  |       0.883564 |   0.473943 |
| barab-szabi-1        |     0.527796 |       0.454381 |   0.478282 |
| k-d_tree_polars      |     0.500059 |       0.431461 |   0.488489 |
| solution-1           |     8.13932  |       1e-06    |   0.529254 |
| k-d_tree_pandas      |     0.508296 |       0.404356 |   0.605889 |
| Bori_Aron_solution-1 |     0.49248  |       0.594199 |   0.6142   |
| k-d_tree_sklearn     |     3.5201   |       1.25968  |   1.17391  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.505144 |       0.453411 |   0.464216 |
| barab-szabi-2        |     0.512965 |       0.488501 |   0.487803 |
| barab-szabi-1        |     0.512068 |       0.467781 |   0.495755 |
| k-d_tree_pandas      |     0.492395 |       0.405689 |   0.584417 |
| Bori_Aron_solution-1 |     0.514697 |       0.609829 |   0.602266 |
| k-d_tree_sklearn     |     0.488264 |       1.04631  |   1.13594  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482252 |       0.472869 |   0.488    |
| barab-szabi-1        |     0.495983 |       0.471244 |   0.501439 |
| k-d_tree_polars      |     0.523885 |       0.473722 |   0.505676 |
| Bori_Aron_solution-1 |     0.488517 |       0.643831 |   0.607099 |
| k-d_tree_pandas      |     0.501819 |       0.431809 |   0.614729 |
| k-d_tree_sklearn     |     0.507506 |       1.11732  |   1.21387  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477826 |       0.525044 |   0.494331 |
| Bori_Aron_solution-1 |     0.476693 |       0.778905 |   0.571676 |
| k-d_tree_polars      |     0.478001 |       0.562494 |   0.575482 |
| barab-szabi-1        |     0.477427 |       0.564105 |   0.586532 |
| k-d_tree_pandas      |     0.477829 |       0.509452 |   0.75372  |
| k-d_tree_sklearn     |     0.483077 |       1.27397  |   1.16776  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488394 |       0.741535 |   0.517183 |
| Bori_Aron_solution-1 |     0.473094 |       1.45684  |   0.601074 |
| k-d_tree_polars      |     0.481922 |       0.935374 |   0.962373 |
| barab-szabi-1        |     0.477152 |       0.93145  |   0.990991 |
| k-d_tree_pandas      |     0.479654 |       0.812757 |   1.21377  |
| k-d_tree_sklearn     |     0.48724  |       2.15713  |   1.24492  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481977 |        5.01837 |   0.7667   |
| Bori_Aron_solution-1 |     0.484797 |       10.9739  |   0.822196 |
| k-d_tree_sklearn     |     0.479949 |       16.8211  |   1.32791  |
| k-d_tree_polars      |     0.476677 |        5.36814 |   6.63326  |
| barab-szabi-1        |     0.475319 |        5.40572 |   6.69353  |
| k-d_tree_pandas      |     0.474123 |        4.36714 |   6.98411  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477617 |        72.0921 |    2.86415 |
| k-d_tree_sklearn     |     0.822977 |       251.358  |    4.07148 |
| Bori_Aron_solution-1 |     0.481913 |       154.146  |   17.9304  |