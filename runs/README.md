# 2025-12-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.469175 |       0.370394 |   0.396656 |
| barab-szabi-2        |     0.455407 |       0.455154 |   0.396799 |
| k-d_tree_polars      |     0.469752 |       0.369904 |   0.397401 |
| solution-1           |     6.90827  |       1e-06    |   0.414612 |
| Bori_Aron_solution-1 |     0.462628 |       0.493533 |   0.498749 |
| k-d_tree_pandas      |     7.77401  |       0.378467 |   0.627882 |
| k-d_tree_sklearn     |     2.96741  |       0.983508 |   0.943682 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470065 |       0.396254 |   0.397719 |
| barab-szabi-1        |     0.470129 |       0.389633 |   0.400867 |
| k-d_tree_polars      |     0.470133 |       0.374889 |   0.401911 |
| Bori_Aron_solution-1 |     0.462473 |       0.507705 |   0.497825 |
| k-d_tree_pandas      |     0.536538 |       0.356697 |   0.505926 |
| k-d_tree_sklearn     |     0.470955 |       0.870349 |   0.964447 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465233 |       0.412711 |   0.406668 |
| k-d_tree_polars      |     0.471148 |       0.400105 |   0.425063 |
| barab-szabi-1        |     0.469649 |       0.409661 |   0.425769 |
| Bori_Aron_solution-1 |     0.461162 |       0.541497 |   0.500235 |
| k-d_tree_pandas      |     0.466889 |       0.371798 |   0.549628 |
| k-d_tree_sklearn     |     0.469821 |       0.91258  |   0.96661  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466996 |       0.46497  |   0.435425 |
| k-d_tree_polars      |     0.469043 |       0.511489 |   0.504678 |
| Bori_Aron_solution-1 |     0.463343 |       0.697486 |   0.515534 |
| barab-szabi-1        |     0.470847 |       0.512351 |   0.516692 |
| k-d_tree_pandas      |     0.469772 |       0.462974 |   0.661848 |
| k-d_tree_sklearn     |     0.472902 |       1.15105  |   1.01186  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466994 |       0.695705 |   0.472579 |
| Bori_Aron_solution-1 |     0.461573 |       1.27611  |   0.545956 |
| k-d_tree_polars      |     0.468278 |       0.83378  |   0.807707 |
| barab-szabi-1        |     0.46952  |       0.83689  |   0.846699 |
| k-d_tree_pandas      |     0.466656 |       0.710466 |   1.04008  |
| k-d_tree_sklearn     |     0.469346 |       1.86233  |   1.07624  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467568 |        4.62392 |   0.672063 |
| Bori_Aron_solution-1 |     0.463481 |        9.49731 |   0.878782 |
| k-d_tree_sklearn     |     0.47366  |       13.2835  |   1.22297  |
| barab-szabi-1        |     0.468225 |        4.77684 |   5.66826  |
| k-d_tree_polars      |     0.469241 |        4.80554 |   5.72906  |
| k-d_tree_pandas      |     0.470436 |        3.76015 |   6.07175  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471165 |        82.3597 |    2.66889 |
| k-d_tree_sklearn     |     0.478822 |       168.185  |    4.21963 |
| Bori_Aron_solution-1 |     0.579393 |       134.772  |   17.4406  |