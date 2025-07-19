# 2025-07-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.57974  |       1.0529   |   0.422844 |
| barab-szabi-1        |     0.538899 |       0.402743 |   0.427301 |
| k-d_tree_polars      |     0.555605 |       0.405198 |   0.439155 |
| Bori_Aron_solution-1 |     0.536134 |       0.547207 |   0.543822 |
| k-d_tree_pandas      |     0.567533 |       0.383323 |   0.553564 |
| solution-1           |     7.80889  |       1e-06    |   0.679476 |
| k-d_tree_sklearn     |     2.98909  |       1.41     |   1.0604   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55648  |       0.424878 |   0.430954 |
| barab-szabi-1        |     0.554839 |       0.410441 |   0.435607 |
| k-d_tree_polars      |     0.559741 |       0.437454 |   0.447073 |
| Bori_Aron_solution-1 |     0.563472 |       0.558272 |   0.559637 |
| k-d_tree_pandas      |     0.570059 |       0.40261  |   0.567183 |
| k-d_tree_sklearn     |     0.559503 |       0.994783 |   1.09043  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556673 |       0.43692  |   0.444116 |
| barab-szabi-1        |     0.563493 |       0.438181 |   0.458179 |
| k-d_tree_polars      |     0.568488 |       0.439471 |   0.469003 |
| Bori_Aron_solution-1 |     0.546059 |       0.606028 |   0.572903 |
| k-d_tree_pandas      |     0.562609 |       0.419297 |   0.610386 |
| k-d_tree_sklearn     |     0.578317 |       1.03078  |   1.08937  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567935 |       0.529319 |   0.505178 |
| k-d_tree_polars      |     0.557262 |       0.556735 |   0.548701 |
| barab-szabi-1        |     0.557035 |       0.556957 |   0.559714 |
| Bori_Aron_solution-1 |     0.55443  |       0.770432 |   0.569387 |
| k-d_tree_pandas      |     0.563691 |       0.496756 |   0.735062 |
| k-d_tree_sklearn     |     0.563106 |       1.24659  |   1.14127  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55633  |       0.73367  |   0.492427 |
| Bori_Aron_solution-1 |     0.542784 |       1.40669  |   0.61696  |
| k-d_tree_polars      |     0.577223 |       0.890762 |   0.921019 |
| barab-szabi-1        |     0.552949 |       0.88231  |   0.957718 |
| k-d_tree_pandas      |     0.55878  |       0.759789 |   1.19503  |
| k-d_tree_sklearn     |     0.583503 |       2.11428  |   1.2597   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554043 |        5.51696 |   0.748209 |
| Bori_Aron_solution-1 |     0.547409 |       10.8654  |   0.845165 |
| k-d_tree_sklearn     |     0.559803 |       16.5751  |   1.31113  |
| k-d_tree_polars      |     0.556444 |        5.02713 |   6.81965  |
| barab-szabi-1        |     0.549879 |        4.99737 |   6.83392  |
| k-d_tree_pandas      |     0.549485 |        3.95868 |   7.16515  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546654 |        72.6029 |    2.78291 |
| k-d_tree_sklearn     |     0.68067  |       233.855  |    3.96143 |
| Bori_Aron_solution-1 |     0.546435 |       140.363  |   18.1114  |