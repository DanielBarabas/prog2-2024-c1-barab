# 2026-05-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.62469  |       1e-06    |   0.45594  |
| barab-szabi-2        |     0.491353 |       0.473422 |   0.461174 |
| k-d_tree_polars      |     0.483046 |       0.433978 |   0.461492 |
| k-d_tree_pandas      |     0.463626 |       0.40364  |   0.587703 |
| Bori_Aron_solution-1 |     0.52477  |       0.716821 |   0.610209 |
| barab-szabi-1        |     8.06088  |       0.509671 |   0.663165 |
| k-d_tree_sklearn     |     2.99397  |       1.18165  |   1.19259  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530721 |       0.52782  |   0.498303 |
| barab-szabi-1        |     0.517025 |       0.450917 |   0.514352 |
| k-d_tree_polars      |     0.513414 |       0.46988  |   0.516331 |
| Bori_Aron_solution-1 |     0.486724 |       0.577836 |   0.566038 |
| k-d_tree_pandas      |     0.540967 |       0.426846 |   0.595171 |
| k-d_tree_sklearn     |     0.500823 |       1.02524  |   1.15165  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.514314 |       0.461222 |   0.487835 |
| barab-szabi-2        |     0.555766 |       0.532817 |   0.506012 |
| k-d_tree_polars      |     0.482206 |       0.52799  |   0.559606 |
| Bori_Aron_solution-1 |     0.531566 |       0.70757  |   0.695387 |
| k-d_tree_pandas      |     0.536286 |       0.484667 |   0.711135 |
| k-d_tree_sklearn     |     0.603258 |       1.28327  |   1.33135  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.520721 |       0.564286 |   0.529406 |
| Bori_Aron_solution-1 |     0.522354 |       0.859523 |   0.625969 |
| k-d_tree_polars      |     0.524858 |       0.629578 |   0.639451 |
| barab-szabi-1        |     0.585585 |       0.646104 |   0.653784 |
| k-d_tree_pandas      |     0.539767 |       0.541464 |   0.814198 |
| k-d_tree_sklearn     |     0.5152   |       1.48014  |   1.34169  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47772  |       0.770485 |   0.525619 |
| Bori_Aron_solution-1 |     0.473736 |       1.50357  |   0.625922 |
| k-d_tree_polars      |     0.522941 |       0.933702 |   0.955415 |
| barab-szabi-1        |     0.541778 |       0.988205 |   1.08435  |
| k-d_tree_sklearn     |     0.538807 |       2.33394  |   1.26575  |
| k-d_tree_pandas      |     0.484698 |       0.831467 |   1.28869  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51637  |        5.14262 |   0.76741  |
| Bori_Aron_solution-1 |     0.461414 |       10.9603  |   0.816234 |
| k-d_tree_sklearn     |     0.476939 |       16.8602  |   1.31451  |
| k-d_tree_pandas      |     0.471187 |        4.50406 |   7.04331  |
| barab-szabi-1        |     0.491215 |        5.64033 |   7.36301  |
| k-d_tree_polars      |     0.529588 |        5.59506 |   7.61548  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471678 |        78.3391 |    2.77111 |
| k-d_tree_sklearn     |     0.483514 |       245.275  |    3.70086 |
| Bori_Aron_solution-1 |     0.469688 |       154.519  |   24.1829  |