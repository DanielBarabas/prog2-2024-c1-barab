# 2025-02-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.592053 |       0.426278 |   0.41604  |
| barab-szabi-2        |     8.22615  |       0.773823 |   0.417707 |
| barab-szabi-1        |     0.630968 |       0.424043 |   0.431833 |
| solution-1           |     7.82402  |       1e-06    |   0.510882 |
| Bori_Aron_solution-1 |     0.596595 |       0.556464 |   0.587273 |
| k-d_tree_pandas      |     0.63089  |       0.422945 |   0.59733  |
| k-d_tree_sklearn     |     3.18274  |       1.14115  |   1.06524  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616559 |       0.414086 |   0.416895 |
| k-d_tree_polars      |     0.640767 |       0.424878 |   0.421726 |
| barab-szabi-1        |     0.606457 |       0.429053 |   0.42635  |
| k-d_tree_pandas      |     0.616765 |       0.408143 |   0.569766 |
| Bori_Aron_solution-1 |     0.604383 |       0.563913 |   0.58669  |
| k-d_tree_sklearn     |     0.611543 |       0.989454 |   1.09781  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611552 |       0.434485 |   0.428925 |
| barab-szabi-1        |     0.61285  |       0.449827 |   0.450784 |
| k-d_tree_polars      |     0.613755 |       0.443283 |   0.457698 |
| Bori_Aron_solution-1 |     0.630559 |       0.619681 |   0.567996 |
| k-d_tree_pandas      |     0.601167 |       0.424284 |   0.619565 |
| k-d_tree_sklearn     |     0.620725 |       1.0511   |   1.18386  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612079 |       0.505669 |   0.457954 |
| k-d_tree_polars      |     0.601508 |       0.548866 |   0.545507 |
| Bori_Aron_solution-1 |     0.595557 |       0.763038 |   0.562129 |
| barab-szabi-1        |     0.604907 |       0.557403 |   0.566941 |
| k-d_tree_pandas      |     0.602184 |       0.50903  |   0.737813 |
| k-d_tree_sklearn     |     0.619189 |       1.24328  |   1.14679  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600629 |       0.744313 |   0.531764 |
| Bori_Aron_solution-1 |     0.606353 |       1.43726  |   0.615184 |
| k-d_tree_polars      |     0.603321 |       0.891191 |   0.929257 |
| barab-szabi-1        |     0.611698 |       0.882769 |   0.95608  |
| k-d_tree_pandas      |     0.611375 |       0.756685 |   1.21319  |
| k-d_tree_sklearn     |     0.61992  |       2.1832   |   1.25023  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600492 |        5.50838 |   0.757395 |
| Bori_Aron_solution-1 |     0.601588 |       11.1496  |   0.897609 |
| k-d_tree_sklearn     |     0.606808 |       17.0525  |   1.35534  |
| k-d_tree_polars      |     0.603879 |        4.92057 |   6.71775  |
| barab-szabi-1        |     0.604453 |        4.89845 |   6.87624  |
| k-d_tree_pandas      |     0.609185 |        3.87014 |   7.27058  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602447 |        80.0331 |    3.11302 |
| k-d_tree_sklearn     |     0.635012 |       240.207  |    4.44673 |
| Bori_Aron_solution-1 |     0.709929 |       152.4    |   19.1547  |