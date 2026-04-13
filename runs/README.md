# 2026-04-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.45819  |       1e-06    |   0.419033 |
| barab-szabi-1        |     0.456491 |       0.39609  |   0.424137 |
| barab-szabi-2        |     0.452469 |       0.428302 |   0.429843 |
| k-d_tree_polars      |     0.454689 |       0.390643 |   0.432418 |
| Bori_Aron_solution-1 |     0.442478 |       0.532489 |   0.537295 |
| k-d_tree_pandas      |     0.462542 |       0.374899 |   0.54555  |
| k-d_tree_sklearn     |    10.101    |       1.1232   |   1.06075  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.457221 |       0.403782 |   0.429302 |
| barab-szabi-2        |     0.449635 |       0.428365 |   0.430109 |
| barab-szabi-1        |     0.453352 |       0.399433 |   0.432944 |
| Bori_Aron_solution-1 |     0.445527 |       0.542443 |   0.532849 |
| k-d_tree_pandas      |     0.458851 |       0.382918 |   0.54284  |
| k-d_tree_sklearn     |     0.452335 |       1.00099  |   1.07927  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.449541 |       0.425454 |   0.455547 |
| barab-szabi-1        |     0.452801 |       0.431722 |   0.458286 |
| barab-szabi-2        |     0.450259 |       0.445177 |   0.464662 |
| Bori_Aron_solution-1 |     0.449045 |       0.581042 |   0.538389 |
| k-d_tree_pandas      |     0.452701 |       0.404611 |   0.586816 |
| k-d_tree_sklearn     |     0.453356 |       1.00717  |   1.06502  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.451508 |       0.498127 |   0.46309  |
| k-d_tree_polars      |     0.451218 |       0.549082 |   0.549351 |
| Bori_Aron_solution-1 |     0.447553 |       0.769129 |   0.562236 |
| barab-szabi-1        |     0.453589 |       0.551543 |   0.574095 |
| k-d_tree_pandas      |     0.451697 |       0.494993 |   0.722531 |
| k-d_tree_sklearn     |     0.453715 |       1.24593  |   1.11966  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.450585 |       0.707966 |   0.504027 |
| Bori_Aron_solution-1 |     0.446759 |       1.42816  |   0.576101 |
| k-d_tree_polars      |     0.453816 |       0.917762 |   0.915976 |
| barab-szabi-1        |     0.451696 |       0.919084 |   0.936224 |
| k-d_tree_pandas      |     0.450999 |       0.806319 |   1.15933  |
| k-d_tree_sklearn     |     0.458161 |       2.09733  |   1.19816  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452564 |        4.79668 |   0.72947  |
| Bori_Aron_solution-1 |     0.452575 |       10.8455  |   0.803191 |
| k-d_tree_sklearn     |     0.453155 |       16.3626  |   1.29601  |
| barab-szabi-1        |     0.455189 |        5.52885 |   6.39775  |
| k-d_tree_polars      |     0.449876 |        5.53545 |   6.48653  |
| k-d_tree_pandas      |     0.453701 |        4.49711 |   6.77556  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.788282 |        68.9593 |    2.64803 |
| k-d_tree_sklearn     |     0.457385 |       232.269  |    3.75014 |
| Bori_Aron_solution-1 |     0.458997 |       150.15   |   16.0997  |