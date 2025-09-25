# 2025-09-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534748 |       0.480279 |   0.427543 |
| barab-szabi-1        |     0.545343 |       0.409371 |   0.429947 |
| k-d_tree_polars      |     0.543695 |       0.422946 |   0.430174 |
| solution-1           |     7.83857  |       1e-06    |   0.5026   |
| Bori_Aron_solution-1 |     0.53571  |       0.54711  |   0.55404  |
| k-d_tree_pandas      |     8.47969  |       0.409591 |   0.697025 |
| k-d_tree_sklearn     |     3.17178  |       1.11515  |   1.05434  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540778 |       0.423337 |   0.426463 |
| barab-szabi-1        |     0.545785 |       0.406924 |   0.432987 |
| k-d_tree_polars      |     0.545483 |       0.42034  |   0.449906 |
| Bori_Aron_solution-1 |     0.534409 |       0.554885 |   0.549995 |
| k-d_tree_pandas      |     0.538637 |       0.39349  |   0.556803 |
| k-d_tree_sklearn     |     0.568974 |       0.965741 |   1.06095  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540668 |       0.506547 |   0.449146 |
| k-d_tree_polars      |     0.552597 |       0.436419 |   0.455812 |
| barab-szabi-1        |     0.544972 |       0.433823 |   0.459036 |
| Bori_Aron_solution-1 |     0.532636 |       0.591366 |   0.550396 |
| k-d_tree_pandas      |     0.540093 |       0.408935 |   0.601975 |
| k-d_tree_sklearn     |     0.544019 |       1.00954  |   1.08394  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539698 |       0.50835  |   0.467777 |
| k-d_tree_polars      |     0.543922 |       0.550151 |   0.555744 |
| barab-szabi-1        |     0.539428 |       0.546934 |   0.560756 |
| Bori_Aron_solution-1 |     0.532193 |       0.771522 |   0.563174 |
| k-d_tree_pandas      |     0.537161 |       0.492768 |   0.750466 |
| k-d_tree_sklearn     |     0.546597 |       1.25271  |   1.13501  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539257 |       0.744655 |   0.499772 |
| Bori_Aron_solution-1 |     0.537544 |       1.40468  |   0.579866 |
| k-d_tree_polars      |     0.541744 |       0.888089 |   0.909599 |
| barab-szabi-1        |     0.535153 |       0.889    |   0.957572 |
| k-d_tree_pandas      |     0.539874 |       0.759854 |   1.16774  |
| k-d_tree_sklearn     |     0.542771 |       2.08262  |   1.20745  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541774 |        5.2854  |   0.731584 |
| Bori_Aron_solution-1 |     0.535373 |       10.7255  |   0.838649 |
| k-d_tree_sklearn     |     0.544871 |       16.8224  |   1.35181  |
| k-d_tree_polars      |     0.542183 |        5.03957 |   6.61345  |
| barab-szabi-1        |     0.563763 |        4.92262 |   6.63432  |
| k-d_tree_pandas      |     0.542551 |        3.96561 |   7.03867  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541653 |        72.6621 |    2.60302 |
| k-d_tree_sklearn     |     0.554824 |       231.331  |    4.07709 |
| Bori_Aron_solution-1 |     0.592014 |       140.878  |   18.1413  |