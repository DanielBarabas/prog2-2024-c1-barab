# 2025-02-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.69787  |       1e-06    |   0.396988 |
| barab-szabi-2        |     4.12213  |       0.441894 |   0.407877 |
| barab-szabi-1        |     0.591172 |       0.404213 |   0.408303 |
| k-d_tree_polars      |     0.592994 |       0.40595  |   0.414166 |
| Bori_Aron_solution-1 |     5.06463  |       0.588491 |   0.497614 |
| k-d_tree_pandas      |     0.595351 |       0.38291  |   0.542185 |
| k-d_tree_sklearn     |     3.08957  |       0.978292 |   1.02368  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.58632  |       0.407136 |   0.407939 |
| barab-szabi-1        |     0.608375 |       0.406577 |   0.410133 |
| barab-szabi-2        |     0.588065 |       0.40975  |   0.472071 |
| Bori_Aron_solution-1 |     0.584392 |       0.552973 |   0.540668 |
| k-d_tree_pandas      |     0.58303  |       0.394017 |   0.555722 |
| k-d_tree_sklearn     |     0.595098 |       0.958617 |   1.02058  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588292 |       0.415488 |   0.418154 |
| k-d_tree_polars      |     0.586316 |       0.438241 |   0.437022 |
| barab-szabi-1        |     0.588547 |       0.43306  |   0.442147 |
| Bori_Aron_solution-1 |     0.582253 |       0.58437  |   0.542787 |
| k-d_tree_pandas      |     0.586963 |       0.406219 |   0.620458 |
| k-d_tree_sklearn     |     0.613111 |       1.02592  |   1.05137  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605765 |       0.483681 |   0.451765 |
| k-d_tree_polars      |     0.584253 |       0.533877 |   0.527698 |
| barab-szabi-1        |     0.589054 |       0.537666 |   0.533439 |
| Bori_Aron_solution-1 |     0.588329 |       0.752213 |   0.554732 |
| k-d_tree_pandas      |     0.587597 |       0.473679 |   0.724819 |
| k-d_tree_sklearn     |     0.595166 |       1.21164  |   1.10955  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.595289 |       0.734744 |   0.479967 |
| Bori_Aron_solution-1 |     0.585223 |       1.39231  |   0.582702 |
| k-d_tree_polars      |     0.587042 |       0.861429 |   0.890158 |
| barab-szabi-1        |     0.593075 |       0.863674 |   0.9234   |
| k-d_tree_pandas      |     0.583877 |       0.743021 |   1.1763   |
| k-d_tree_sklearn     |     0.588431 |       2.04757  |   1.20155  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593797 |        5.33495 |   0.735235 |
| Bori_Aron_solution-1 |     0.580867 |       10.5724  |   0.866691 |
| k-d_tree_sklearn     |     0.595517 |       16.272   |   1.30007  |
| barab-szabi-1        |     0.595697 |        4.86897 |   6.59133  |
| k-d_tree_polars      |     0.588202 |        4.90116 |   6.71422  |
| k-d_tree_pandas      |     0.584666 |        3.74354 |   7.03914  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.784508 |         70.742 |    3.0505  |
| k-d_tree_sklearn     |     0.730257 |        225.926 |    4.36162 |
| Bori_Aron_solution-1 |     0.58412  |        155.543 |   14.79    |