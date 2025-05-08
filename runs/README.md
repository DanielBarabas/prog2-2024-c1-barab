# 2025-05-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.65583  |       1e-06    |   0.359234 |
| barab-szabi-2        |     0.53768  |       0.408182 |   0.411273 |
| barab-szabi-1        |     0.509284 |       0.407939 |   0.416104 |
| k-d_tree_polars      |     4.04621  |       0.411693 |   0.420023 |
| Bori_Aron_solution-1 |     4.70586  |       0.608897 |   0.492562 |
| k-d_tree_pandas      |     0.508957 |       0.384513 |   0.557745 |
| k-d_tree_sklearn     |     3.05227  |       1.01592  |   1.03036  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523953 |       0.414082 |   0.421314 |
| k-d_tree_polars      |     0.525689 |       0.408493 |   0.42172  |
| barab-szabi-1        |     0.543193 |       0.424989 |   0.422782 |
| Bori_Aron_solution-1 |     0.512428 |       0.605108 |   0.555019 |
| k-d_tree_pandas      |     0.519711 |       0.393544 |   0.569336 |
| k-d_tree_sklearn     |     0.537568 |       0.986112 |   1.04736  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529358 |       0.424408 |   0.431952 |
| k-d_tree_polars      |     0.526164 |       0.442997 |   0.446234 |
| barab-szabi-1        |     0.524619 |       0.438455 |   0.448688 |
| Bori_Aron_solution-1 |     0.522733 |       0.592775 |   0.562637 |
| k-d_tree_pandas      |     0.52182  |       0.414975 |   0.599605 |
| k-d_tree_sklearn     |     0.53456  |       1.01411  |   1.07836  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531687 |       0.486754 |   0.458034 |
| k-d_tree_polars      |     0.523705 |       0.549919 |   0.55863  |
| Bori_Aron_solution-1 |     0.531021 |       0.771991 |   0.561374 |
| barab-szabi-1        |     0.52699  |       0.545748 |   0.563046 |
| k-d_tree_pandas      |     0.523533 |       0.498015 |   0.737955 |
| k-d_tree_sklearn     |     0.530611 |       1.23661  |   1.13289  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522662 |       0.729733 |   0.495172 |
| Bori_Aron_solution-1 |     0.516898 |       1.41074  |   0.636581 |
| k-d_tree_polars      |     0.525434 |       0.884426 |   0.887597 |
| barab-szabi-1        |     0.520995 |       0.877191 |   0.932313 |
| k-d_tree_pandas      |     0.520554 |       0.768392 |   1.1973   |
| k-d_tree_sklearn     |     0.530849 |       2.13675  |   1.23475  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525276 |        5.34601 |   0.748153 |
| Bori_Aron_solution-1 |     0.521542 |       10.7289  |   0.886705 |
| k-d_tree_sklearn     |     0.529251 |       16.4209  |   1.33158  |
| barab-szabi-1        |     0.521529 |        5.04716 |   6.62368  |
| k-d_tree_polars      |     0.524775 |        5.07366 |   6.67931  |
| k-d_tree_pandas      |     0.532957 |        3.94245 |   6.97366  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604171 |        74.5366 |    2.77015 |
| k-d_tree_sklearn     |     0.768258 |       237.877  |    4.39379 |
| Bori_Aron_solution-1 |     0.519252 |       155.896  |   15.3479  |