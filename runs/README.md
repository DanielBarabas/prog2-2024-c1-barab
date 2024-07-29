# 2024-07-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559604 |       0.402671 |   0.398702 |
| k-d_tree_polars      |     0.580892 |       0.414978 |   0.4163   |
| solution-1           |     8.12975  |       1e-06    |   0.419381 |
| barab-szabi-1        |     8.81301  |       0.472539 |   0.516899 |
| Bori_Aron_solution-1 |     0.585264 |       0.558718 |   0.556002 |
| k-d_tree_pandas      |     0.584065 |       0.401299 |   0.561108 |
| k-d_tree_sklearn     |     3.1178   |       1.08984  |   0.740587 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591439 |       0.395534 |   0.402143 |
| barab-szabi-1        |     0.580445 |       0.424395 |   0.414114 |
| k-d_tree_polars      |     0.606961 |       0.433817 |   0.415524 |
| k-d_tree_pandas      |     0.62028  |       0.429846 |   0.562586 |
| Bori_Aron_solution-1 |     0.573977 |       0.567481 |   0.565729 |
| k-d_tree_sklearn     |     0.607971 |       0.944755 |   0.779483 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583581 |       0.41467  |   0.413986 |
| k-d_tree_polars      |     0.603709 |       0.439157 |   0.419516 |
| barab-szabi-1        |     0.569958 |       0.439082 |   0.425376 |
| Bori_Aron_solution-1 |     0.556256 |       0.585638 |   0.531854 |
| k-d_tree_pandas      |     0.573697 |       0.409246 |   0.581188 |
| k-d_tree_sklearn     |     0.58889  |       1.00918  |   0.780842 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570553 |       0.489728 |   0.447048 |
| barab-szabi-1        |     0.568466 |       0.539405 |   0.529776 |
| k-d_tree_polars      |     0.594173 |       0.559296 |   0.532181 |
| Bori_Aron_solution-1 |     0.583055 |       0.806581 |   0.576158 |
| k-d_tree_pandas      |     0.588962 |       0.480834 |   0.717845 |
| k-d_tree_sklearn     |     0.569406 |       1.19027  |   0.809673 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597254 |       0.73749  |   0.480052 |
| Bori_Aron_solution-1 |     0.582506 |       1.46902  |   0.610819 |
| k-d_tree_sklearn     |     0.58357  |       2.16185  |   0.886646 |
| k-d_tree_polars      |     0.589208 |       0.869674 |   0.896369 |
| barab-szabi-1        |     0.572791 |       0.89878  |   0.988842 |
| k-d_tree_pandas      |     0.58958  |       0.74989  |   1.1868   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.595687 |        5.78374 |   0.751671 |
| Bori_Aron_solution-1 |     0.575544 |       10.9821  |   0.892082 |
| k-d_tree_sklearn     |     0.597633 |       16.6117  |   1.0376   |
| barab-szabi-1        |     0.570266 |        4.94682 |   6.80649  |
| k-d_tree_polars      |     0.605996 |        4.96421 |   7.02876  |
| k-d_tree_pandas      |     0.604532 |        3.92748 |   7.15949  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589762 |        74.9747 |    3.03599 |
| k-d_tree_sklearn     |     0.605501 |       235.42   |    3.94824 |
| Bori_Aron_solution-1 |     0.646958 |       151.643  |   15.8043  |