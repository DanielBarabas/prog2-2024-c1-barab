# 2025-09-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.62939  |       1e-06    |   0.372522 |
| k-d_tree_polars      |     0.553099 |       0.412804 |   0.435335 |
| barab-szabi-1        |     0.563581 |       0.415936 |   0.437076 |
| barab-szabi-2        |     0.527246 |       0.431956 |   0.439462 |
| Bori_Aron_solution-1 |     0.537716 |       0.54871  |   0.557205 |
| k-d_tree_pandas      |     7.78343  |       0.474005 |   0.671924 |
| k-d_tree_sklearn     |     3.01318  |       1.04372  |   1.09028  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.57142  |       0.409879 |   0.434808 |
| barab-szabi-1        |     0.541139 |       0.416794 |   0.438776 |
| barab-szabi-2        |     0.563335 |       0.461411 |   0.452985 |
| k-d_tree_pandas      |     0.554772 |       0.400243 |   0.563324 |
| Bori_Aron_solution-1 |     0.548035 |       0.55489  |   0.568939 |
| k-d_tree_sklearn     |     0.548872 |       0.973141 |   1.07581  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555218 |       0.440612 |   0.443165 |
| k-d_tree_polars      |     0.543633 |       0.438741 |   0.467884 |
| barab-szabi-1        |     0.545624 |       0.50186  |   0.473161 |
| Bori_Aron_solution-1 |     0.547631 |       0.601305 |   0.552371 |
| k-d_tree_pandas      |     0.545034 |       0.40917  |   0.601531 |
| k-d_tree_sklearn     |     0.552563 |       1.03359  |   1.0953   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543713 |       0.498215 |   0.470548 |
| k-d_tree_polars      |     0.535771 |       0.5504   |   0.559043 |
| barab-szabi-1        |     0.550252 |       0.553538 |   0.560823 |
| Bori_Aron_solution-1 |     0.548328 |       0.774971 |   0.592425 |
| k-d_tree_pandas      |     0.557044 |       0.487489 |   0.740692 |
| k-d_tree_sklearn     |     0.550826 |       1.26125  |   1.162    |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53945  |       0.765848 |   0.499191 |
| Bori_Aron_solution-1 |     0.534793 |       1.40138  |   0.591819 |
| k-d_tree_polars      |     0.535966 |       0.887827 |   0.912619 |
| barab-szabi-1        |     0.541427 |       0.887112 |   0.965877 |
| k-d_tree_pandas      |     0.542818 |       0.766369 |   1.18032  |
| k-d_tree_sklearn     |     0.546056 |       2.09925  |   1.2129   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536811 |        5.07264 |   0.731996 |
| Bori_Aron_solution-1 |     0.536811 |       10.4873  |   0.846188 |
| k-d_tree_sklearn     |     0.549544 |       16.4193  |   1.31954  |
| k-d_tree_polars      |     0.541497 |        5.08383 |   6.47492  |
| barab-szabi-1        |     0.544525 |        5.06141 |   6.5095   |
| k-d_tree_pandas      |     0.544799 |        3.96532 |   6.79632  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537584 |        71.6078 |    2.68293 |
| k-d_tree_sklearn     |     0.554435 |       231.142  |    4.14548 |
| Bori_Aron_solution-1 |     0.59782  |       144.074  |   16.7844  |