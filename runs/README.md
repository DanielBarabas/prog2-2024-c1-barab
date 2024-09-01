# 2024-09-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.82273  |       0.518903 |   0.375531 |
| barab-szabi-1        |     0.591944 |       0.388561 |   0.379948 |
| k-d_tree_polars      |     0.590577 |       0.394199 |   0.387012 |
| solution-1           |     7.55005  |       1e-06    |   0.492755 |
| Bori_Aron_solution-1 |     0.600328 |       0.517994 |   0.509145 |
| k-d_tree_pandas      |     0.596155 |       0.445405 |   0.523261 |
| k-d_tree_sklearn     |     3.01494  |       0.919163 |   0.697825 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597862 |       0.386872 |   0.381769 |
| barab-szabi-1        |     0.608871 |       0.396749 |   0.389705 |
| k-d_tree_polars      |     0.624787 |       0.396766 |   0.391349 |
| Bori_Aron_solution-1 |     0.624569 |       0.525572 |   0.51277  |
| k-d_tree_pandas      |     0.607839 |       0.375262 |   0.526716 |
| k-d_tree_sklearn     |     0.606846 |       0.877974 |   0.695591 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.6061   |       0.400006 |   0.39073  |
| k-d_tree_polars      |     0.605141 |       0.419858 |   0.416898 |
| barab-szabi-1        |     0.610381 |       0.422724 |   0.418146 |
| Bori_Aron_solution-1 |     0.598528 |       0.560678 |   0.519595 |
| k-d_tree_pandas      |     0.604275 |       0.394787 |   0.569829 |
| k-d_tree_sklearn     |     0.611031 |       0.933302 |   0.726561 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600666 |       0.464096 |   0.423633 |
| k-d_tree_polars      |     0.603703 |       0.554545 |   0.518559 |
| barab-szabi-1        |     0.610729 |       0.530509 |   0.524983 |
| Bori_Aron_solution-1 |     0.594867 |       0.739092 |   0.530554 |
| k-d_tree_pandas      |     0.604181 |       0.476152 |   0.700605 |
| k-d_tree_sklearn     |     0.603757 |       1.14126  |   0.77275  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60612  |       0.705887 |   0.459017 |
| Bori_Aron_solution-1 |     0.590204 |       1.36424  |   0.553253 |
| k-d_tree_polars      |     0.608776 |       0.843917 |   0.850526 |
| k-d_tree_sklearn     |     0.610315 |       1.94664  |   0.872266 |
| barab-szabi-1        |     0.607558 |       0.851162 |   0.885671 |
| k-d_tree_pandas      |     0.603674 |       0.737637 |   1.12906  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603592 |        5.12074 |   0.726079 |
| Bori_Aron_solution-1 |     0.594902 |       10.6193  |   0.810443 |
| k-d_tree_sklearn     |     0.604996 |       15.5616  |   0.989151 |
| k-d_tree_polars      |     0.603172 |        4.81368 |   6.38309  |
| barab-szabi-1        |     0.602955 |        4.84454 |   6.40032  |
| k-d_tree_pandas      |     0.601757 |        3.88233 |   6.72466  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605295 |        71.9115 |    3.0195  |
| k-d_tree_sklearn     |     0.625906 |       227.808  |    3.86099 |
| Bori_Aron_solution-1 |     0.651505 |       144.679  |   17.267   |