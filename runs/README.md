# 2024-10-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.637596 |       0.398117 |   0.383574 |
| solution-1           |     7.78298  |       1e-06    |   0.400554 |
| barab-szabi-1        |     0.630491 |       0.404231 |   0.407567 |
| k-d_tree_polars      |     0.631581 |       0.398609 |   0.412878 |
| Bori_Aron_solution-1 |     0.617867 |       0.541464 |   0.527713 |
| k-d_tree_pandas      |     0.627586 |       0.391308 |   0.539769 |
| k-d_tree_sklearn     |    10.6301   |       1.09582  |   0.995372 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629285 |       0.392939 |   0.393876 |
| k-d_tree_polars      |     0.628932 |       0.428942 |   0.395169 |
| barab-szabi-1        |     0.630419 |       0.452493 |   0.406826 |
| k-d_tree_pandas      |     0.657339 |       0.39555  |   0.557597 |
| Bori_Aron_solution-1 |     0.649116 |       0.561979 |   0.584395 |
| k-d_tree_sklearn     |     0.64024  |       0.930503 |   0.988403 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.638495 |       0.457709 |   0.424699 |
| barab-szabi-1        |     0.646997 |       0.4313   |   0.428545 |
| barab-szabi-2        |     0.629895 |       0.404877 |   0.442309 |
| Bori_Aron_solution-1 |     0.627516 |       0.584167 |   0.551785 |
| k-d_tree_pandas      |     0.636977 |       0.419076 |   0.592011 |
| k-d_tree_sklearn     |     0.625864 |       0.965397 |   1.00471  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633784 |       0.469781 |   0.437837 |
| k-d_tree_polars      |     0.640734 |       0.548855 |   0.529631 |
| barab-szabi-1        |     0.635575 |       0.559601 |   0.540363 |
| Bori_Aron_solution-1 |     0.621357 |       0.766371 |   0.541072 |
| k-d_tree_pandas      |     0.629842 |       0.509089 |   0.711937 |
| k-d_tree_sklearn     |     0.628776 |       1.18602  |   1.06462  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.664971 |       0.72217  |   0.475163 |
| Bori_Aron_solution-1 |     0.621736 |       1.40719  |   0.568817 |
| k-d_tree_polars      |     0.617859 |       0.861    |   0.89369  |
| barab-szabi-1        |     0.635715 |       0.864875 |   0.937724 |
| k-d_tree_sklearn     |     0.633483 |       2.01974  |   1.13369  |
| k-d_tree_pandas      |     0.623153 |       0.76036  |   1.16425  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62513  |        5.45206 |   0.739354 |
| Bori_Aron_solution-1 |     0.624122 |       10.8034  |   0.824268 |
| k-d_tree_sklearn     |     0.633313 |       16.4918  |   1.27854  |
| barab-szabi-1        |     0.630084 |        4.87854 |   6.56491  |
| k-d_tree_polars      |     0.621929 |        4.83824 |   6.60403  |
| k-d_tree_pandas      |     0.643939 |        3.93696 |   6.96317  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.648623 |        71.2213 |    2.91548 |
| k-d_tree_sklearn     |     0.623555 |       228.805  |    4.33835 |
| Bori_Aron_solution-1 |     0.637775 |       149.226  |   18.4438  |