# 2024-09-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608854 |       0.387849 |   0.378936 |
| k-d_tree_polars      |     4.13032  |       0.452542 |   0.391292 |
| solution-1           |     7.6094   |       1e-06    |   0.403867 |
| Bori_Aron_solution-1 |     4.38851  |       0.543738 |   0.449031 |
| barab-szabi-1        |     0.609228 |       0.391467 |   0.45058  |
| k-d_tree_pandas      |     0.591443 |       0.375499 |   0.522484 |
| k-d_tree_sklearn     |     3.03651  |       0.932367 |   0.692744 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.614129 |       0.399974 |   0.388433 |
| barab-szabi-1        |     0.606369 |       0.397629 |   0.392041 |
| barab-szabi-2        |     0.604633 |       0.390913 |   0.393933 |
| Bori_Aron_solution-1 |     0.599302 |       0.534369 |   0.525098 |
| k-d_tree_pandas      |     0.605372 |       0.374707 |   0.53126  |
| k-d_tree_sklearn     |     0.623157 |       0.876322 |   0.691542 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607223 |       0.401654 |   0.393046 |
| k-d_tree_polars      |     0.606452 |       0.42366  |   0.416758 |
| barab-szabi-1        |     0.608958 |       0.442817 |   0.422288 |
| Bori_Aron_solution-1 |     0.615849 |       0.563172 |   0.522839 |
| k-d_tree_pandas      |     0.606686 |       0.390779 |   0.574895 |
| k-d_tree_sklearn     |     0.621432 |       0.91337  |   0.719181 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603701 |       0.470981 |   0.42172  |
| k-d_tree_polars      |     0.602965 |       0.54278  |   0.514371 |
| barab-szabi-1        |     0.599838 |       0.534058 |   0.529287 |
| Bori_Aron_solution-1 |     0.598145 |       0.74907  |   0.54593  |
| k-d_tree_pandas      |     0.606987 |       0.472878 |   0.6985   |
| k-d_tree_sklearn     |     0.602194 |       1.14259  |   0.778549 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60421  |       0.709155 |   0.461869 |
| Bori_Aron_solution-1 |     0.593689 |       1.37246  |   0.557933 |
| k-d_tree_sklearn     |     0.606986 |       1.95363  |   0.855189 |
| k-d_tree_polars      |     0.603312 |       0.847214 |   0.860169 |
| barab-szabi-1        |     0.612907 |       0.848876 |   0.896717 |
| k-d_tree_pandas      |     0.605455 |       0.744818 |   1.1276   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610677 |        5.25607 |   0.72045  |
| Bori_Aron_solution-1 |     0.595026 |       10.7532  |   0.811644 |
| k-d_tree_sklearn     |     0.615129 |       15.8128  |   0.972697 |
| k-d_tree_polars      |     0.609253 |        4.80159 |   6.56331  |
| barab-szabi-1        |     0.609098 |        4.82992 |   6.5923   |
| k-d_tree_pandas      |     0.610224 |        3.84396 |   6.93424  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734643 |        70.0683 |    3.75496 |
| k-d_tree_sklearn     |     0.924313 |       220.303  |    3.99665 |
| Bori_Aron_solution-1 |     0.621336 |       146.61   |   18.6393  |