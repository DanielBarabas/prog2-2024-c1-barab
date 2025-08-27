# 2025-08-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.578315 |       0.440837 |   0.455446 |
| solution-1           |     7.6468   |       1e-06    |   0.465134 |
| barab-szabi-2        |     0.584833 |       0.470978 |   0.492236 |
| barab-szabi-1        |     0.577481 |       0.443605 |   0.502378 |
| Bori_Aron_solution-1 |     0.565747 |       0.593133 |   0.589497 |
| k-d_tree_pandas      |     7.93644  |       0.443459 |   0.707835 |
| k-d_tree_sklearn     |     3.09431  |       1.19021  |   1.16399  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.574907 |       0.459281 |   0.455085 |
| barab-szabi-2        |     0.572147 |       0.452686 |   0.457132 |
| barab-szabi-1        |     0.575584 |       0.442518 |   0.461468 |
| Bori_Aron_solution-1 |     0.566244 |       0.599221 |   0.588017 |
| k-d_tree_pandas      |     0.582584 |       0.417223 |   0.602918 |
| k-d_tree_sklearn     |     0.584889 |       1.06769  |   1.15435  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593729 |       0.483034 |   0.478091 |
| k-d_tree_polars      |     0.581937 |       0.477123 |   0.478275 |
| barab-szabi-1        |     0.584995 |       0.484083 |   0.508571 |
| Bori_Aron_solution-1 |     0.563125 |       0.641876 |   0.608736 |
| k-d_tree_pandas      |     0.574097 |       0.435561 |   0.653681 |
| k-d_tree_sklearn     |     0.591337 |       1.11115  |   1.17744  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576618 |       0.544442 |   0.49403  |
| barab-szabi-1        |     0.581744 |       0.580086 |   0.603124 |
| Bori_Aron_solution-1 |     0.59165  |       0.821635 |   0.607837 |
| k-d_tree_polars      |     0.61444  |       0.624234 |   0.635936 |
| k-d_tree_pandas      |     0.587215 |       0.522424 |   0.780484 |
| k-d_tree_sklearn     |     0.586339 |       1.40349  |   1.32694  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.567516 |       1.51512  |   0.611997 |
| barab-szabi-2        |     0.599346 |       0.848967 |   0.740031 |
| k-d_tree_polars      |     0.572155 |       0.931211 |   0.95018  |
| barab-szabi-1        |     0.573613 |       0.932759 |   1.02215  |
| k-d_tree_pandas      |     0.599329 |       0.786775 |   1.24769  |
| k-d_tree_sklearn     |     0.590492 |       2.31636  |   1.37591  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549308 |        5.57191 |   0.754678 |
| Bori_Aron_solution-1 |     0.571471 |       11.2004  |   0.895246 |
| k-d_tree_sklearn     |     0.551066 |       17.8672  |   1.38976  |
| barab-szabi-1        |     0.545637 |        5.06736 |   6.89737  |
| k-d_tree_pandas      |     0.579323 |        3.95406 |   7.32012  |
| k-d_tree_polars      |     0.565805 |        5.18685 |   7.51135  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587154 |        78.3777 |    2.85607 |
| k-d_tree_sklearn     |     0.571944 |       246.87   |    4.2335  |
| Bori_Aron_solution-1 |     0.60949  |       152.189  |   17.5914  |