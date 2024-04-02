# 2024-04-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.703206 |       0.37893  |   0.357502 |
| solution-1           |     8.23572  |       1e-06    |   0.360035 |
| barab-szabi-1        |     0.737436 |       0.394043 |   0.363188 |
| k-d_tree_polars      |     0.741274 |       0.39736  |   0.369503 |
| Bori_Aron_solution-1 |     0.697083 |       0.494302 |   0.496878 |
| k-d_tree_pandas      |    19.3267   |       0.394948 |   0.531878 |
| k-d_tree_sklearn     |     4.0164   |       0.882473 |   0.668097 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731907 |       0.366098 |   0.361089 |
| k-d_tree_polars      |     0.730722 |       0.405927 |   0.367705 |
| barab-szabi-1        |     0.736976 |       0.401484 |   0.372964 |
| Bori_Aron_solution-1 |     0.719474 |       0.508356 |   0.498123 |
| k-d_tree_pandas      |     0.738019 |       0.383659 |   0.513958 |
| k-d_tree_sklearn     |     0.741982 |       0.842817 |   0.730927 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.736599 |       0.425411 |   0.395315 |
| barab-szabi-1        |     0.737572 |       0.429304 |   0.40094  |
| barab-szabi-2        |     0.729742 |       0.383364 |   0.479242 |
| k-d_tree_pandas      |     0.738063 |       0.400498 |   0.546637 |
| Bori_Aron_solution-1 |     0.738129 |       0.549909 |   0.651325 |
| k-d_tree_sklearn     |     0.738155 |       0.886145 |   0.701507 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734081 |       0.448723 |   0.413296 |
| k-d_tree_polars      |     0.747362 |       0.540748 |   0.499861 |
| barab-szabi-1        |     0.735791 |       0.538438 |   0.514584 |
| Bori_Aron_solution-1 |     0.734605 |       0.726058 |   0.517165 |
| k-d_tree_pandas      |     0.734642 |       0.479697 |   0.681186 |
| k-d_tree_sklearn     |     0.748277 |       1.15374  |   0.781666 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731528 |       0.687425 |   0.446011 |
| Bori_Aron_solution-1 |     0.725833 |       1.35336  |   0.534625 |
| k-d_tree_polars      |     0.736209 |       0.850791 |   0.850641 |
| k-d_tree_sklearn     |     0.734874 |       1.90536  |   0.8609   |
| barab-szabi-1        |     0.744069 |       0.859099 |   0.876722 |
| k-d_tree_pandas      |     0.760478 |       0.739103 |   1.1096   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735926 |        5.3239  |   0.746979 |
| Bori_Aron_solution-1 |     0.721035 |       10.6038  |   0.793614 |
| k-d_tree_sklearn     |     0.743176 |       15.8465  |   1.06031  |
| barab-szabi-1        |     0.733235 |        4.81318 |   6.61663  |
| k-d_tree_polars      |     0.743206 |        4.83705 |   6.62489  |
| k-d_tree_pandas      |     0.738011 |        3.86404 |   6.87711  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.733128 |        71.7281 |    3.96126 |
| k-d_tree_sklearn     |     0.946208 |       226.373  |    4.90144 |
| Bori_Aron_solution-1 |     0.883915 |       147.411  |   14.2191  |