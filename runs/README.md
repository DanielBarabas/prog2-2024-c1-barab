# 2024-11-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.54044  |       1e-06    |   0.378198 |
| k-d_tree_polars      |     0.619439 |       0.395298 |   0.386211 |
| barab-szabi-1        |     0.620201 |       0.397654 |   0.38639  |
| barab-szabi-2        |     0.627837 |       0.386141 |   0.392531 |
| Bori_Aron_solution-1 |     0.610914 |       0.554618 |   0.513281 |
| k-d_tree_pandas      |     0.613917 |       0.383304 |   0.526342 |
| k-d_tree_sklearn     |    10.3229   |       1.01748  |   0.957653 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631977 |       0.388007 |   0.387717 |
| k-d_tree_polars      |     0.61522  |       0.405598 |   0.392664 |
| barab-szabi-1        |     0.622093 |       0.403921 |   0.395862 |
| Bori_Aron_solution-1 |     0.60469  |       0.523699 |   0.517874 |
| k-d_tree_pandas      |     0.609812 |       0.3841   |   0.525949 |
| k-d_tree_sklearn     |     0.633188 |       0.886469 |   0.953114 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613549 |       0.400097 |   0.399527 |
| k-d_tree_polars      |     0.615963 |       0.428328 |   0.420326 |
| barab-szabi-1        |     0.615755 |       0.431463 |   0.422374 |
| Bori_Aron_solution-1 |     0.614862 |       0.562842 |   0.521787 |
| k-d_tree_pandas      |     0.613537 |       0.400063 |   0.572156 |
| k-d_tree_sklearn     |     0.621981 |       0.939912 |   0.992193 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627587 |       0.46401  |   0.425315 |
| k-d_tree_polars      |     0.612189 |       0.534142 |   0.520902 |
| barab-szabi-1        |     0.615984 |       0.539208 |   0.526678 |
| Bori_Aron_solution-1 |     0.608076 |       0.744297 |   0.546517 |
| k-d_tree_pandas      |     0.633105 |       0.483911 |   0.705938 |
| k-d_tree_sklearn     |     0.615065 |       1.1649   |   1.04303  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614197 |       0.715492 |   0.495298 |
| Bori_Aron_solution-1 |     0.625875 |       1.38919  |   0.559578 |
| k-d_tree_polars      |     0.617132 |       0.850142 |   0.871739 |
| barab-szabi-1        |     0.611717 |       0.86534  |   0.908755 |
| k-d_tree_sklearn     |     0.617203 |       1.99973  |   1.13008  |
| k-d_tree_pandas      |     0.613639 |       0.756726 |   1.16539  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622483 |        5.3761  |   0.722912 |
| Bori_Aron_solution-1 |     0.61758  |       10.7206  |   0.811742 |
| k-d_tree_sklearn     |     0.62273  |       16.1748  |   1.23326  |
| k-d_tree_polars      |     0.60836  |        4.8773  |   6.56143  |
| barab-szabi-1        |     0.619199 |        4.89281 |   6.60356  |
| k-d_tree_pandas      |     0.615861 |        3.88284 |   6.97038  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633982 |        71.6762 |    2.88072 |
| k-d_tree_sklearn     |     0.618364 |       224.799  |    4.16111 |
| Bori_Aron_solution-1 |     0.637514 |       147.97   |   17.3677  |