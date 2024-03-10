# 2024-03-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73279  |       0.361985 |   0.363168 |
| barab-szabi-1        |     0.73788  |       0.39962  |   0.363685 |
| Bori_Aron_solution-1 |     0.724327 |       0.506088 |   0.506004 |
| k-d_tree_pandas      |     0.735859 |       0.38432  |   0.50961  |
| solution-1           |     8.17384  |       1e-06    |   0.562254 |
| k-d_tree_polars      |     8.57898  |       0.454694 |   0.571142 |
| k-d_tree_sklearn     |     3.41351  |       0.92756  |   0.668514 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.734883 |       0.407913 |   0.368626 |
| barab-szabi-1        |     0.733875 |       0.413759 |   0.368995 |
| barab-szabi-2        |     0.736544 |       0.369908 |   0.404987 |
| Bori_Aron_solution-1 |     0.739939 |       0.511876 |   0.507293 |
| k-d_tree_pandas      |     0.733497 |       0.400875 |   0.51345  |
| k-d_tree_sklearn     |     0.734508 |       0.860649 |   0.682793 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.739841 |       0.431768 |   0.379368 |
| k-d_tree_polars      |     0.733237 |       0.433566 |   0.392287 |
| barab-szabi-1        |     0.731498 |       0.431795 |   0.402675 |
| Bori_Aron_solution-1 |     0.724562 |       0.552272 |   0.502074 |
| k-d_tree_pandas      |     0.74201  |       0.404447 |   0.55541  |
| k-d_tree_sklearn     |     0.742919 |       0.90978  |   0.700382 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.736807 |       0.453145 |   0.402278 |
| k-d_tree_polars      |     0.731645 |       0.542686 |   0.492337 |
| barab-szabi-1        |     0.734755 |       0.547039 |   0.504976 |
| Bori_Aron_solution-1 |     0.727143 |       0.735883 |   0.515366 |
| k-d_tree_pandas      |     0.731471 |       0.485759 |   0.686308 |
| k-d_tree_sklearn     |     0.748975 |       1.12173  |   0.764451 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.74173  |       0.698147 |   0.438854 |
| Bori_Aron_solution-1 |     0.723785 |       1.41141  |   0.546963 |
| k-d_tree_polars      |     0.734161 |       0.876939 |   0.857129 |
| k-d_tree_sklearn     |     0.736585 |       1.97578  |   0.873398 |
| barab-szabi-1        |     0.726486 |       0.856301 |   0.883215 |
| k-d_tree_pandas      |     0.734437 |       0.7618   |   1.13658  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.750929 |        5.09675 |   0.734935 |
| Bori_Aron_solution-1 |     0.722002 |       10.569   |   0.80038  |
| k-d_tree_sklearn     |     0.748664 |       15.5482  |   1.05762  |
| barab-szabi-1        |     0.737932 |        4.94232 |   6.4278   |
| k-d_tree_polars      |     0.734578 |        4.92572 |   6.43703  |
| k-d_tree_pandas      |     0.73868  |        3.90682 |   6.72305  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.852604 |        70.6995 |    3.76359 |
| k-d_tree_sklearn     |     0.743211 |       228.735  |    5.1789  |
| Bori_Aron_solution-1 |     0.84879  |       140.55   |   18.3273  |