# 2026-06-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.46995  |       0.411858 |   0.443287 |
| barab-szabi-2        |     8.66167  |       0.681893 |   0.450086 |
| solution-1           |     8.06021  |       1e-06    |   0.456272 |
| barab-szabi-1        |     0.497661 |       0.432964 |   0.479143 |
| Bori_Aron_solution-1 |     0.472596 |       0.567891 |   0.553702 |
| k-d_tree_pandas      |     0.482919 |       0.391414 |   0.563306 |
| k-d_tree_sklearn     |     3.24248  |       1.18772  |   1.08517  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.475369 |       0.417025 |   0.439988 |
| barab-szabi-2        |     0.47893  |       0.453337 |   0.440332 |
| barab-szabi-1        |     0.472335 |       0.417888 |   0.446454 |
| Bori_Aron_solution-1 |     0.467527 |       0.560816 |   0.556108 |
| k-d_tree_pandas      |     0.478512 |       0.401954 |   0.56409  |
| k-d_tree_sklearn     |     0.498391 |       1.00375  |   1.09635  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474903 |       0.455689 |   0.45906  |
| barab-szabi-1        |     0.481808 |       0.447294 |   0.474738 |
| Bori_Aron_solution-1 |     0.476493 |       0.608268 |   0.569613 |
| k-d_tree_pandas      |     0.478586 |       0.414063 |   0.596638 |
| k-d_tree_polars      |     0.476516 |       0.452547 |   0.602282 |
| k-d_tree_sklearn     |     0.48315  |       1.04181  |   1.11138  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476553 |       0.529492 |   0.491837 |
| k-d_tree_polars      |     0.482763 |       0.572099 |   0.570597 |
| Bori_Aron_solution-1 |     0.475269 |       0.795076 |   0.574113 |
| barab-szabi-1        |     0.479703 |       0.572953 |   0.584545 |
| k-d_tree_pandas      |     0.480494 |       0.5157   |   0.744723 |
| k-d_tree_sklearn     |     0.478994 |       1.29601  |   1.17339  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.470055 |       1.50456  |   0.587355 |
| barab-szabi-2        |     0.490927 |       0.81011  |   0.595246 |
| k-d_tree_polars      |     0.473518 |       0.913044 |   0.965151 |
| barab-szabi-1        |     0.487063 |       0.923911 |   1.03261  |
| k-d_tree_sklearn     |     0.475268 |       2.1745   |   1.19578  |
| k-d_tree_pandas      |     0.473424 |       0.796372 |   1.20627  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47275  |        5.62802 |   0.759344 |
| Bori_Aron_solution-1 |     0.502941 |       11.472   |   0.805732 |
| k-d_tree_sklearn     |     0.473676 |       17.6577  |   1.28173  |
| k-d_tree_polars      |     0.471894 |        5.22522 |   7.42345  |
| k-d_tree_pandas      |     0.473687 |        4.17088 |   7.81529  |
| barab-szabi-1        |     0.494669 |        5.33003 |   7.88067  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472266 |        81.1441 |    2.75842 |
| k-d_tree_sklearn     |     0.710291 |       260.506  |    3.35339 |
| Bori_Aron_solution-1 |     0.48799  |       154.579  |   23.0052  |