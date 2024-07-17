# 2024-07-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551056 |       0.390957 |   0.377579 |
| barab-szabi-1        |     0.55015  |       0.395118 |   0.386354 |
| k-d_tree_polars      |     0.563339 |       0.393144 |   0.38754  |
| k-d_tree_pandas      |     0.54992  |       0.374567 |   0.519909 |
| Bori_Aron_solution-1 |     0.549446 |       0.525824 |   0.522225 |
| solution-1           |     7.88979  |       1e-06    |   0.566152 |
| k-d_tree_sklearn     |    12.0502   |       1.21736  |   0.707762 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558785 |       0.387652 |   0.381713 |
| barab-szabi-1        |     0.551914 |       0.400165 |   0.390343 |
| k-d_tree_polars      |     0.553715 |       0.401689 |   0.43944  |
| Bori_Aron_solution-1 |     0.55973  |       0.526612 |   0.511118 |
| k-d_tree_pandas      |     0.548637 |       0.380622 |   0.527222 |
| k-d_tree_sklearn     |     0.562049 |       0.88939  |   0.697295 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550365 |       0.397637 |   0.392403 |
| barab-szabi-1        |     0.549886 |       0.423745 |   0.419728 |
| k-d_tree_polars      |     0.568655 |       0.43694  |   0.419915 |
| Bori_Aron_solution-1 |     0.54634  |       0.566603 |   0.521649 |
| k-d_tree_pandas      |     0.557965 |       0.397745 |   0.57137  |
| k-d_tree_sklearn     |     0.55543  |       0.934561 |   0.725591 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560921 |       0.467639 |   0.429607 |
| k-d_tree_polars      |     0.550313 |       0.532775 |   0.517417 |
| barab-szabi-1        |     0.562883 |       0.537735 |   0.522799 |
| Bori_Aron_solution-1 |     0.545707 |       0.74057  |   0.529809 |
| k-d_tree_pandas      |     0.555639 |       0.477479 |   0.713965 |
| k-d_tree_sklearn     |     0.563751 |       1.20018  |   0.785654 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55919  |       0.716711 |   0.461073 |
| Bori_Aron_solution-1 |     0.540988 |       1.40296  |   0.575914 |
| k-d_tree_polars      |     0.546841 |       0.843656 |   0.854403 |
| k-d_tree_sklearn     |     0.562684 |       1.95487  |   0.865464 |
| barab-szabi-1        |     0.546458 |       0.844661 |   0.904375 |
| k-d_tree_pandas      |     0.547627 |       0.736413 |   1.1417   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551728 |        5.31409 |   0.729361 |
| Bori_Aron_solution-1 |     0.541088 |       10.7897  |   0.846804 |
| k-d_tree_sklearn     |     0.556162 |       15.9237  |   0.997342 |
| k-d_tree_polars      |     0.557699 |        4.87853 |   6.50797  |
| barab-szabi-1        |     0.553398 |        4.8621  |   6.58694  |
| k-d_tree_pandas      |     0.553288 |        3.8672  |   6.89316  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.787879 |        72.0015 |    3.01734 |
| k-d_tree_sklearn     |     0.556538 |       229.591  |    3.91251 |
| Bori_Aron_solution-1 |     0.56025  |       146.673  |   18.0294  |