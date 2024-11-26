# 2024-11-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.624629 |       0.409965 |   0.393074 |
| barab-szabi-1        |     0.628322 |       0.405472 |   0.394161 |
| barab-szabi-2        |     0.632794 |       0.406895 |   0.398726 |
| Bori_Aron_solution-1 |     0.622886 |       0.534231 |   0.537285 |
| k-d_tree_pandas      |     0.644379 |       0.402512 |   0.543176 |
| solution-1           |     7.72739  |       1e-06    |   0.731681 |
| k-d_tree_sklearn     |    10.5305   |       1.57897  |   0.979326 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630987 |       0.413201 |   0.403365 |
| k-d_tree_polars      |     0.632642 |       0.427105 |   0.405697 |
| barab-szabi-1        |     0.648332 |       0.424695 |   0.413658 |
| Bori_Aron_solution-1 |     0.632638 |       0.545579 |   0.537828 |
| k-d_tree_pandas      |     0.645653 |       0.396702 |   0.560393 |
| k-d_tree_sklearn     |     0.647552 |       0.943866 |   1.02144  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62923  |       0.409308 |   0.402464 |
| barab-szabi-1        |     0.649167 |       0.452903 |   0.435362 |
| k-d_tree_polars      |     0.626532 |       0.434216 |   0.44397  |
| Bori_Aron_solution-1 |     0.622762 |       0.577603 |   0.554515 |
| k-d_tree_pandas      |     0.641592 |       0.428018 |   0.612847 |
| k-d_tree_sklearn     |     0.644201 |       0.983371 |   1.01799  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.637614 |       0.480155 |   0.446487 |
| k-d_tree_polars      |     0.666142 |       0.589711 |   0.541329 |
| barab-szabi-1        |     0.641737 |       0.577731 |   0.559643 |
| Bori_Aron_solution-1 |     0.652472 |       0.768748 |   0.574099 |
| k-d_tree_pandas      |     0.655794 |       0.509313 |   0.75551  |
| k-d_tree_sklearn     |     0.666232 |       1.19416  |   1.12551  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623394 |       0.736327 |   0.472363 |
| Bori_Aron_solution-1 |     0.635639 |       1.40692  |   0.572846 |
| k-d_tree_polars      |     0.638511 |       0.87635  |   0.890359 |
| barab-szabi-1        |     0.609821 |       0.891462 |   0.941972 |
| k-d_tree_pandas      |     0.624429 |       0.754881 |   1.17163  |
| k-d_tree_sklearn     |     0.650058 |       2.09402  |   1.18875  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612077 |        5.73804 |   0.762193 |
| Bori_Aron_solution-1 |     0.607242 |       11.119   |   0.83626  |
| k-d_tree_sklearn     |     0.627004 |       17.0498  |   1.25659  |
| barab-szabi-1        |     0.619081 |        4.95356 |   6.77673  |
| k-d_tree_polars      |     0.614152 |        4.87741 |   6.83024  |
| k-d_tree_pandas      |     0.615685 |        3.9229  |   7.31785  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623498 |        76.1433 |    3.27063 |
| k-d_tree_sklearn     |     0.620657 |       235.134  |    4.2949  |
| Bori_Aron_solution-1 |     0.622311 |       149.884  |   17.0942  |