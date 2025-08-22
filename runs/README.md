# 2025-08-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.602303 |       0.406954 |   0.428453 |
| barab-szabi-2        |     0.543597 |       0.422789 |   0.429296 |
| barab-szabi-1        |     0.933484 |       0.459919 |   0.463088 |
| Bori_Aron_solution-1 |     0.535933 |       0.542607 |   0.550094 |
| solution-1           |     8.13193  |       1e-06    |   0.571547 |
| k-d_tree_pandas      |     8.35627  |       0.449197 |   0.77882  |
| k-d_tree_sklearn     |     3.03359  |       1.16597  |   1.05905  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.547738 |       0.414619 |   0.430159 |
| k-d_tree_polars      |     0.544386 |       0.415498 |   0.431164 |
| barab-szabi-2        |     0.542674 |       0.428859 |   0.431871 |
| Bori_Aron_solution-1 |     0.534427 |       0.551606 |   0.54279  |
| k-d_tree_pandas      |     0.544834 |       0.388196 |   0.564624 |
| k-d_tree_sklearn     |     0.546834 |       0.982254 |   1.06779  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542247 |       0.434113 |   0.442568 |
| barab-szabi-1        |     0.542651 |       0.440444 |   0.45661  |
| k-d_tree_polars      |     0.559618 |       0.436079 |   0.457354 |
| Bori_Aron_solution-1 |     0.541072 |       0.589332 |   0.563078 |
| k-d_tree_pandas      |     0.547011 |       0.411102 |   0.600466 |
| k-d_tree_sklearn     |     0.551039 |       1.02068  |   1.1363   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547205 |       0.506495 |   0.467546 |
| k-d_tree_polars      |     0.543704 |       0.556873 |   0.562372 |
| barab-szabi-1        |     0.545853 |       0.55019  |   0.564516 |
| Bori_Aron_solution-1 |     0.545916 |       0.767214 |   0.567827 |
| k-d_tree_pandas      |     0.556046 |       0.490375 |   0.738933 |
| k-d_tree_sklearn     |     0.557137 |       1.25962  |   1.13749  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558149 |       0.740538 |   0.50017  |
| Bori_Aron_solution-1 |     0.542974 |       1.39206  |   0.585366 |
| k-d_tree_polars      |     0.547037 |       0.88867  |   0.891876 |
| barab-szabi-1        |     0.546584 |       0.888559 |   0.958235 |
| k-d_tree_pandas      |     0.545638 |       0.76288  |   1.17485  |
| k-d_tree_sklearn     |     0.544613 |       2.06875  |   1.22054  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545129 |        5.28205 |   0.743344 |
| Bori_Aron_solution-1 |     0.550155 |       10.5643  |   0.84639  |
| k-d_tree_sklearn     |     0.549868 |       16.1022  |   1.30942  |
| barab-szabi-1        |     0.547836 |        5.06055 |   6.46752  |
| k-d_tree_polars      |     0.544637 |        5.02353 |   6.55019  |
| k-d_tree_pandas      |     0.543527 |        3.92709 |   6.92973  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538871 |         75.7   |    2.77215 |
| k-d_tree_sklearn     |     0.548037 |        241.455 |    4.09782 |
| Bori_Aron_solution-1 |     0.621611 |        144.568 |   18.1381  |