# 2025-01-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611727 |       0.453876 |   0.424557 |
| barab-szabi-1        |     0.627986 |       0.437053 |   0.433352 |
| k-d_tree_polars      |     0.631262 |       0.440927 |   0.437714 |
| solution-1           |     7.87856  |       1e-06    |   0.475033 |
| Bori_Aron_solution-1 |     0.643083 |       0.568416 |   0.562941 |
| k-d_tree_pandas      |     8.31473  |       0.434129 |   0.607994 |
| k-d_tree_sklearn     |     3.25657  |       1.11342  |   1.08826  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.598539 |       0.416925 |   0.413336 |
| barab-szabi-2        |     0.614732 |       0.427174 |   0.420398 |
| barab-szabi-1        |     0.609151 |       0.430532 |   0.424208 |
| k-d_tree_pandas      |     0.60912  |       0.42059  |   0.58718  |
| Bori_Aron_solution-1 |     0.626072 |       0.613741 |   0.589882 |
| k-d_tree_sklearn     |     0.652442 |       0.963995 |   1.03256  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.628436 |       0.455333 |   0.453775 |
| barab-szabi-1        |     0.635527 |       0.493575 |   0.471161 |
| k-d_tree_polars      |     0.630316 |       0.473562 |   0.475578 |
| Bori_Aron_solution-1 |     0.616951 |       0.624826 |   0.592316 |
| k-d_tree_pandas      |     0.622766 |       0.437449 |   0.628346 |
| k-d_tree_sklearn     |     0.640519 |       1.08133  |   1.1459   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.6371   |       0.498614 |   0.472148 |
| k-d_tree_polars      |     0.624603 |       0.603775 |   0.584296 |
| barab-szabi-1        |     0.620626 |       0.568126 |   0.584626 |
| Bori_Aron_solution-1 |     0.61578  |       0.813758 |   0.60671  |
| k-d_tree_pandas      |     0.631299 |       0.518383 |   0.77065  |
| k-d_tree_sklearn     |     0.631249 |       1.31919  |   1.21817  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.57821  |       1.37133  |   0.58109  |
| barab-szabi-2        |     0.615323 |       0.763494 |   0.625167 |
| k-d_tree_polars      |     0.584357 |       0.852032 |   0.872558 |
| barab-szabi-1        |     0.630299 |       0.883218 |   0.974439 |
| k-d_tree_pandas      |     0.626144 |       0.766403 |   1.24154  |
| k-d_tree_sklearn     |     0.61599  |       2.22879  |   1.29265  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604546 |        5.37136 |   0.738762 |
| Bori_Aron_solution-1 |     0.570529 |       10.6913  |   0.881613 |
| k-d_tree_sklearn     |     0.592223 |       16.622   |   1.29914  |
| k-d_tree_polars      |     0.591805 |        4.81444 |   6.63447  |
| barab-szabi-1        |     0.581253 |        4.79574 |   6.77163  |
| k-d_tree_pandas      |     0.581225 |        3.85752 |   7.05819  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610065 |        71.5795 |    2.95682 |
| k-d_tree_sklearn     |     0.588796 |       222.588  |    4.47857 |
| Bori_Aron_solution-1 |     0.686092 |       148.048  |   17.4724  |