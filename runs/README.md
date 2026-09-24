# 2026-09-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.30706  |       1e-06    |   0.424363 |
| barab-szabi-2        |     0.470505 |       0.483266 |   0.451785 |
| k-d_tree_polars      |     0.469301 |       0.410155 |   0.464527 |
| Bori_Aron_solution-1 |     0.452417 |       0.540039 |   0.553265 |
| k-d_tree_pandas      |     0.466805 |       0.386416 |   0.555582 |
| barab-szabi-1        |     8.07997  |       0.470366 |   0.612479 |
| k-d_tree_sklearn     |     3.01604  |       1.24489  |   1.06983  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473685 |       0.458034 |   0.44743  |
| barab-szabi-1        |     0.481413 |       0.426308 |   0.458878 |
| k-d_tree_polars      |     0.488039 |       0.433257 |   0.463092 |
| Bori_Aron_solution-1 |     0.471975 |       0.554358 |   0.555609 |
| k-d_tree_pandas      |     0.492225 |       0.395519 |   0.566196 |
| k-d_tree_sklearn     |     0.484477 |       1.03316  |   1.09216  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470256 |       0.458908 |   0.476004 |
| k-d_tree_polars      |     0.486988 |       0.451279 |   0.48468  |
| barab-szabi-1        |     0.482325 |       0.45639  |   0.485255 |
| Bori_Aron_solution-1 |     0.490323 |       0.610763 |   0.552579 |
| k-d_tree_pandas      |     0.47861  |       0.421836 |   0.604943 |
| k-d_tree_sklearn     |     0.501585 |       1.05585  |   1.11951  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477373 |       0.534312 |   0.497957 |
| Bori_Aron_solution-1 |     0.461986 |       0.780104 |   0.578289 |
| k-d_tree_polars      |     0.484731 |       0.577075 |   0.580782 |
| barab-szabi-1        |     0.480194 |       0.57589  |   0.591007 |
| k-d_tree_pandas      |     0.47622  |       0.508405 |   0.739082 |
| k-d_tree_sklearn     |     0.489017 |       1.29889  |   1.1726   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479711 |       0.736805 |   0.521625 |
| Bori_Aron_solution-1 |     0.472911 |       1.44971  |   0.593547 |
| k-d_tree_polars      |     0.475187 |       0.931984 |   0.934478 |
| barab-szabi-1        |     0.473352 |       0.935311 |   0.985619 |
| k-d_tree_pandas      |     0.469118 |       0.805568 |   1.19822  |
| k-d_tree_sklearn     |     0.480651 |       2.09774  |   1.21525  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473353 |        5.05543 |   0.754181 |
| Bori_Aron_solution-1 |     0.473597 |       10.8655  |   0.815903 |
| k-d_tree_sklearn     |     0.479618 |       16.8772  |   1.33085  |
| barab-szabi-1        |     0.470641 |        5.26719 |   6.60992  |
| k-d_tree_polars      |     0.470695 |        5.39603 |   6.64347  |
| k-d_tree_pandas      |     0.486959 |        4.35754 |   6.989    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.636906 |        71.2693 |    2.8253  |
| k-d_tree_sklearn     |     0.625267 |       236.515  |    3.98825 |
| Bori_Aron_solution-1 |     0.471656 |       153.639  |   15.2626  |