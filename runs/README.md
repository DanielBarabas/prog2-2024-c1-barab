# 2025-08-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.54529  |       0.411316 |   0.425421 |
| k-d_tree_polars      |     0.567403 |       0.408146 |   0.425469 |
| barab-szabi-2        |     8.25255  |       0.592412 |   0.425659 |
| solution-1           |     8.03928  |       1e-06    |   0.429067 |
| Bori_Aron_solution-1 |     0.546762 |       0.550248 |   0.55515  |
| k-d_tree_pandas      |     0.562857 |       0.398155 |   0.58314  |
| k-d_tree_sklearn     |     3.07656  |       1.07593  |   1.06516  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587844 |       0.427319 |   0.428325 |
| barab-szabi-1        |     0.557239 |       0.42849  |   0.431855 |
| k-d_tree_polars      |     0.569424 |       0.422776 |   0.435891 |
| Bori_Aron_solution-1 |     0.554992 |       0.562862 |   0.548173 |
| k-d_tree_pandas      |     0.561811 |       0.405612 |   0.567095 |
| k-d_tree_sklearn     |     0.557905 |       1.0315   |   1.07586  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566139 |       0.443739 |   0.440906 |
| k-d_tree_polars      |     0.570917 |       0.439054 |   0.461176 |
| barab-szabi-1        |     0.562998 |       0.442627 |   0.463037 |
| Bori_Aron_solution-1 |     0.560047 |       0.596255 |   0.56807  |
| k-d_tree_pandas      |     0.566061 |       0.415149 |   0.62123  |
| k-d_tree_sklearn     |     0.591923 |       1.02241  |   1.13313  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564141 |       0.509478 |   0.473067 |
| k-d_tree_polars      |     0.573205 |       0.555227 |   0.56022  |
| Bori_Aron_solution-1 |     0.579319 |       0.802078 |   0.588564 |
| barab-szabi-1        |     0.572364 |       0.612001 |   0.591226 |
| k-d_tree_pandas      |     0.564361 |       0.493904 |   0.746396 |
| k-d_tree_sklearn     |     0.581258 |       1.29408  |   1.16174  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562439 |       0.753752 |   0.522687 |
| Bori_Aron_solution-1 |     0.55756  |       1.4346   |   0.608242 |
| k-d_tree_polars      |     0.564737 |       0.894029 |   0.927978 |
| barab-szabi-1        |     0.573944 |       0.895696 |   0.969626 |
| k-d_tree_pandas      |     0.565519 |       0.770476 |   1.18449  |
| k-d_tree_sklearn     |     0.570344 |       2.11961  |   1.23897  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555873 |        5.30709 |   0.790895 |
| Bori_Aron_solution-1 |     0.559062 |       10.7423  |   0.849844 |
| k-d_tree_sklearn     |     0.562615 |       16.4616  |   1.33581  |
| k-d_tree_polars      |     0.566369 |        5.10623 |   6.6625   |
| barab-szabi-1        |     0.56627  |        5.07452 |   6.77122  |
| k-d_tree_pandas      |     0.56143  |        3.912   |   7.00983  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560944 |        79.6902 |    2.73228 |
| k-d_tree_sklearn     |     0.767762 |       235.231  |    3.95466 |
| Bori_Aron_solution-1 |     0.566002 |       151.987  |   17.9457  |