# 2026-02-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.66786  |       1e-06    |   0.427821 |
| barab-szabi-2        |     0.517047 |       0.448742 |   0.430465 |
| k-d_tree_polars      |     0.533196 |       0.411552 |   0.439674 |
| barab-szabi-1        |     0.521667 |       0.409114 |   0.440013 |
| Bori_Aron_solution-1 |     0.543779 |       0.547203 |   0.576076 |
| k-d_tree_pandas      |     8.53946  |       0.414613 |   0.609582 |
| k-d_tree_sklearn     |     3.17252  |       1.1327   |   1.08908  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531982 |       0.440033 |   0.430135 |
| barab-szabi-1        |     0.518287 |       0.40711  |   0.451402 |
| k-d_tree_polars      |     0.540776 |       0.422185 |   0.451637 |
| Bori_Aron_solution-1 |     0.523837 |       0.567326 |   0.542986 |
| k-d_tree_pandas      |     0.558156 |       0.405805 |   0.574486 |
| k-d_tree_sklearn     |     0.528464 |       0.967927 |   1.09041  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532143 |       0.448397 |   0.452025 |
| k-d_tree_polars      |     0.517949 |       0.439236 |   0.463958 |
| barab-szabi-1        |     0.530071 |       0.43226  |   0.465813 |
| Bori_Aron_solution-1 |     0.525204 |       0.592527 |   0.54348  |
| k-d_tree_pandas      |     0.540006 |       0.404764 |   0.589638 |
| k-d_tree_sklearn     |     0.52834  |       1.02764  |   1.12419  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52272  |       0.506056 |   0.474903 |
| k-d_tree_polars      |     0.522065 |       0.556025 |   0.555554 |
| barab-szabi-1        |     0.519385 |       0.55012  |   0.565259 |
| Bori_Aron_solution-1 |     0.511471 |       0.78264  |   0.56832  |
| k-d_tree_pandas      |     0.51515  |       0.495063 |   0.732204 |
| k-d_tree_sklearn     |     0.532595 |       1.25428  |   1.1242   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52279  |       0.730651 |   0.507857 |
| Bori_Aron_solution-1 |     0.516415 |       1.46322  |   0.594993 |
| k-d_tree_polars      |     0.529825 |       0.92927  |   0.903975 |
| barab-szabi-1        |     0.521436 |       0.922977 |   0.961161 |
| k-d_tree_pandas      |     0.520027 |       0.806863 |   1.18971  |
| k-d_tree_sklearn     |     0.525343 |       2.1279   |   1.21672  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548868 |        5.44467 |   0.793838 |
| Bori_Aron_solution-1 |     0.523032 |       11.1728  |   0.849246 |
| k-d_tree_sklearn     |     0.557169 |       16.7494  |   1.32704  |
| barab-szabi-1        |     0.529081 |        5.5241  |   6.59009  |
| k-d_tree_polars      |     0.521721 |        5.47103 |   6.65639  |
| k-d_tree_pandas      |     0.532037 |        4.41977 |   7.28551  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52413  |        73.1468 |    2.85533 |
| k-d_tree_sklearn     |     0.534981 |       244.584  |    4.18793 |
| Bori_Aron_solution-1 |     0.671672 |       146.392  |   17.854   |