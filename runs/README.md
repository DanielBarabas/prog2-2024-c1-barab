# 2024-03-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.690846 |       0.37534  |   0.351093 |
| solution-1           |     8.11232  |       1e-06    |   0.361118 |
| k-d_tree_polars      |     0.722814 |       0.40479  |   0.361937 |
| barab-szabi-1        |     0.720319 |       0.398775 |   0.362398 |
| Bori_Aron_solution-1 |     0.680365 |       0.498469 |   0.498416 |
| k-d_tree_pandas      |     9.90387  |       0.400152 |   0.534076 |
| k-d_tree_sklearn     |     3.21777  |       0.888855 |   0.670901 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.740104 |       0.375323 |   0.367534 |
| barab-szabi-1        |     0.723193 |       0.404742 |   0.369983 |
| k-d_tree_polars      |     0.72587  |       0.41306  |   0.370645 |
| Bori_Aron_solution-1 |     0.713361 |       0.522689 |   0.512224 |
| k-d_tree_pandas      |     0.722257 |       0.388517 |   0.518312 |
| k-d_tree_sklearn     |     0.737086 |       0.853709 |   0.677248 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.726457 |       0.388495 |   0.376258 |
| k-d_tree_polars      |     0.724482 |       0.42977  |   0.392285 |
| barab-szabi-1        |     0.731606 |       0.429941 |   0.393742 |
| Bori_Aron_solution-1 |     0.714617 |       0.551127 |   0.508059 |
| k-d_tree_pandas      |     0.721068 |       0.404811 |   0.555783 |
| k-d_tree_sklearn     |     0.73688  |       0.964415 |   0.714955 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.709234 |       0.439953 |   0.411726 |
| k-d_tree_polars      |     0.716228 |       0.533446 |   0.493989 |
| barab-szabi-1        |     0.720989 |       0.544064 |   0.503504 |
| Bori_Aron_solution-1 |     0.722188 |       0.724986 |   0.512201 |
| k-d_tree_pandas      |     0.7246   |       0.481422 |   0.681906 |
| k-d_tree_sklearn     |     0.723459 |       1.13542  |   0.749841 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.718808 |       0.709949 |   0.448236 |
| Bori_Aron_solution-1 |     0.708429 |       1.36384  |   0.534401 |
| k-d_tree_polars      |     0.71231  |       0.85508  |   0.841913 |
| k-d_tree_sklearn     |     0.719998 |       1.92602  |   0.854248 |
| barab-szabi-1        |     0.725029 |       0.858617 |   0.876309 |
| k-d_tree_pandas      |     0.718262 |       0.754719 |   1.11807  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.715491 |        5.2386  |   0.749146 |
| Bori_Aron_solution-1 |     0.699867 |       10.6202  |   0.786086 |
| k-d_tree_sklearn     |     0.722219 |       16.3759  |   1.07044  |
| barab-szabi-1        |     0.719512 |        4.91672 |   6.45068  |
| k-d_tree_polars      |     0.74442  |        4.95257 |   6.52233  |
| k-d_tree_pandas      |     0.71898  |        3.98112 |   6.68503  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.733598 |        70.5348 |    3.74436 |
| k-d_tree_sklearn     |     0.873998 |       225.177  |    4.7977  |
| Bori_Aron_solution-1 |     0.774464 |       146.414  |   13.5389  |