# 2025-02-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.41043  |       2e-06    |   0.407105 |
| barab-szabi-2        |     0.585577 |       0.41947  |   0.419242 |
| barab-szabi-1        |     0.590871 |       0.424582 |   0.423021 |
| k-d_tree_polars      |     0.586874 |       0.418501 |   0.436369 |
| Bori_Aron_solution-1 |     0.58407  |       0.558024 |   0.565282 |
| k-d_tree_pandas      |     7.78266  |       0.422096 |   0.606259 |
| k-d_tree_sklearn     |     2.99158  |       1.02155  |   1.05593  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.595276 |       0.422172 |   0.412788 |
| k-d_tree_polars      |     0.593357 |       0.415036 |   0.423981 |
| barab-szabi-1        |     0.602642 |       0.436982 |   0.425197 |
| Bori_Aron_solution-1 |     0.592968 |       0.561755 |   0.556341 |
| k-d_tree_pandas      |     0.606733 |       0.406491 |   0.577027 |
| k-d_tree_sklearn     |     0.603714 |       1.00412  |   1.07544  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607282 |       0.444633 |   0.445601 |
| k-d_tree_polars      |     0.59921  |       0.439315 |   0.447098 |
| barab-szabi-1        |     0.614876 |       0.452984 |   0.452698 |
| Bori_Aron_solution-1 |     0.595036 |       0.598582 |   0.560448 |
| k-d_tree_pandas      |     0.603292 |       0.415176 |   0.611522 |
| k-d_tree_sklearn     |     0.670129 |       1.10657  |   1.11706  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603582 |       0.498146 |   0.453092 |
| k-d_tree_polars      |     0.604336 |       0.547848 |   0.540988 |
| barab-szabi-1        |     0.664762 |       0.570629 |   0.571143 |
| Bori_Aron_solution-1 |     0.644989 |       0.839041 |   0.628411 |
| k-d_tree_pandas      |     0.625442 |       0.532035 |   0.828083 |
| k-d_tree_sklearn     |     0.60193  |       1.25865  |   1.14515  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.666842 |       0.763041 |   0.5021   |
| Bori_Aron_solution-1 |     0.596013 |       1.45533  |   0.600187 |
| barab-szabi-1        |     0.609768 |       0.89962  |   0.982435 |
| k-d_tree_polars      |     0.63102  |       0.966022 |   1.02532  |
| k-d_tree_pandas      |     0.604823 |       0.748724 |   1.19473  |
| k-d_tree_sklearn     |     0.616375 |       2.13088  |   1.25153  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618237 |        5.53316 |   0.781248 |
| Bori_Aron_solution-1 |     0.597315 |       10.9231  |   0.890884 |
| k-d_tree_sklearn     |     0.609257 |       16.9126  |   1.45931  |
| barab-szabi-1        |     0.606659 |        5.16207 |   6.91354  |
| k-d_tree_pandas      |     0.605005 |        3.83477 |   7.13717  |
| k-d_tree_polars      |     0.613937 |        4.96301 |   7.31321  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.747024 |        79.5734 |    3.76576 |
| k-d_tree_sklearn     |     0.656874 |       246.649  |    4.33908 |
| Bori_Aron_solution-1 |     0.629137 |       156.866  |   16.0836  |