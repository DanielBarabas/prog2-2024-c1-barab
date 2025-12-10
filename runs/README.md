# 2025-12-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.540339 |       0.401179 |   0.436475 |
| barab-szabi-2        |     0.518647 |       0.519587 |   0.441585 |
| k-d_tree_polars      |     0.539505 |       0.43298  |   0.444049 |
| solution-1           |     7.59189  |       1e-06    |   0.480983 |
| Bori_Aron_solution-1 |     0.518214 |       0.55218  |   0.558989 |
| k-d_tree_pandas      |     8.75732  |       0.441922 |   0.66275  |
| k-d_tree_sklearn     |     3.18022  |       1.11513  |   1.09009  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532131 |       0.435256 |   0.431269 |
| barab-szabi-1        |     0.526302 |       0.411453 |   0.440969 |
| k-d_tree_polars      |     0.528641 |       0.416608 |   0.443665 |
| Bori_Aron_solution-1 |     0.524946 |       0.565449 |   0.559023 |
| k-d_tree_pandas      |     0.532093 |       0.402655 |   0.57177  |
| k-d_tree_sklearn     |     0.542687 |       0.961978 |   1.05609  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530358 |       0.452591 |   0.445726 |
| barab-szabi-1        |     0.532977 |       0.441287 |   0.462773 |
| k-d_tree_polars      |     0.53522  |       0.437813 |   0.462986 |
| Bori_Aron_solution-1 |     0.530464 |       0.607024 |   0.567688 |
| k-d_tree_pandas      |     0.538174 |       0.431124 |   0.593307 |
| k-d_tree_sklearn     |     0.542572 |       1.04266  |   1.22883  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530935 |       0.512128 |   0.479784 |
| k-d_tree_polars      |     0.549405 |       0.561092 |   0.569356 |
| Bori_Aron_solution-1 |     0.524886 |       0.796194 |   0.576637 |
| barab-szabi-1        |     0.55297  |       0.580787 |   0.584292 |
| k-d_tree_pandas      |     0.538002 |       0.510721 |   0.740946 |
| k-d_tree_sklearn     |     0.54207  |       1.30135  |   1.17828  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539623 |       0.751469 |   0.535871 |
| Bori_Aron_solution-1 |     0.543571 |       1.4803   |   0.595158 |
| k-d_tree_polars      |     0.536385 |       0.929098 |   0.929198 |
| barab-szabi-1        |     0.538484 |       0.937102 |   0.974155 |
| k-d_tree_pandas      |     0.533464 |       0.827003 |   1.20498  |
| k-d_tree_sklearn     |     0.552791 |       2.18494  |   1.23678  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540494 |        4.99976 |   0.759077 |
| Bori_Aron_solution-1 |     0.523591 |       11.0178  |   0.838771 |
| k-d_tree_sklearn     |     0.542667 |       16.2068  |   1.30228  |
| barab-szabi-1        |     0.526154 |        5.42486 |   6.55074  |
| k-d_tree_polars      |     0.525236 |        5.42884 |   6.75431  |
| k-d_tree_pandas      |     0.533208 |        4.48497 |   7.08032  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522506 |        77.1914 |    2.73411 |
| k-d_tree_sklearn     |     0.543767 |       241.101  |    4.27877 |
| Bori_Aron_solution-1 |     0.704257 |       149.109  |   18.2035  |