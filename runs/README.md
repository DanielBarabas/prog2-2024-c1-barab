# 2026-07-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.21185  |       1e-06    |   0.426176 |
| barab-szabi-2        |     0.46512  |       0.440125 |   0.435581 |
| k-d_tree_polars      |     0.474393 |       0.41316  |   0.452904 |
| k-d_tree_pandas      |     0.472215 |       0.382266 |   0.548229 |
| Bori_Aron_solution-1 |     0.453233 |       0.543265 |   0.548253 |
| barab-szabi-1        |     8.50793  |       0.478251 |   0.615153 |
| k-d_tree_sklearn     |     3.00885  |       1.1275   |   1.05912  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469484 |       0.443191 |   0.447574 |
| barab-szabi-1        |     0.472262 |       0.423768 |   0.454831 |
| k-d_tree_polars      |     0.472667 |       0.423469 |   0.454857 |
| Bori_Aron_solution-1 |     0.460807 |       0.546796 |   0.544795 |
| k-d_tree_pandas      |     0.468333 |       0.385953 |   0.555345 |
| k-d_tree_sklearn     |     0.473332 |       1.02457  |   1.06583  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465824 |       0.451149 |   0.46066  |
| k-d_tree_polars      |     0.469805 |       0.449222 |   0.478228 |
| barab-szabi-1        |     0.470552 |       0.449824 |   0.482915 |
| Bori_Aron_solution-1 |     0.460107 |       0.592879 |   0.558256 |
| k-d_tree_pandas      |     0.467479 |       0.407364 |   0.600552 |
| k-d_tree_sklearn     |     0.47346  |       1.06667  |   1.08154  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468735 |       0.509313 |   0.47829  |
| Bori_Aron_solution-1 |     0.474065 |       0.769308 |   0.557335 |
| barab-szabi-1        |     0.471397 |       0.563824 |   0.577868 |
| k-d_tree_polars      |     0.477297 |       0.567376 |   0.579544 |
| k-d_tree_pandas      |     0.474317 |       0.50347  |   0.734817 |
| k-d_tree_sklearn     |     0.469905 |       1.2719   |   1.15364  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476762 |       0.725405 |   0.506319 |
| Bori_Aron_solution-1 |     0.462131 |       1.42378  |   0.579261 |
| k-d_tree_polars      |     0.469307 |       0.916752 |   0.918356 |
| barab-szabi-1        |     0.477509 |       0.938853 |   0.97268  |
| k-d_tree_pandas      |     0.469694 |       0.794483 |   1.16391  |
| k-d_tree_sklearn     |     0.47186  |       2.10708  |   1.22748  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470823 |        5.18034 |   0.740901 |
| Bori_Aron_solution-1 |     0.461284 |       11.0127  |   0.813674 |
| k-d_tree_sklearn     |     0.475367 |       16.8982  |   1.29174  |
| barab-szabi-1        |     0.468393 |        5.27171 |   6.78256  |
| k-d_tree_polars      |     0.47495  |        5.36605 |   6.79985  |
| k-d_tree_pandas      |     0.465656 |        4.29831 |   7.2175   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465102 |        69.9104 |    2.75728 |
| k-d_tree_sklearn     |     0.686771 |       233.368  |    4.16043 |
| Bori_Aron_solution-1 |     0.464359 |       153.216  |   16.3882  |