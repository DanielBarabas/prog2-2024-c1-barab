# 2026-09-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.267723 |       0.284433 |   0.291675 |
| k-d_tree_polars      |     0.333863 |       0.26634  |   0.325558 |
| k-d_tree_pandas      |     0.754564 |       0.237166 |   0.340922 |
| Bori_Aron_solution-1 |     0.754084 |       0.330949 |   0.385613 |
| solution-1           |     5.6412   |       1e-06    |   0.449463 |
| barab-szabi-1        |     7.20338  |       0.393097 |   0.622624 |
| k-d_tree_sklearn     |     2.32219  |       1.13227  |   0.675792 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.273897 |       0.277286 |   0.282091 |
| k-d_tree_polars      |     0.270331 |       0.272749 |   0.290326 |
| barab-szabi-2        |     0.270029 |       0.282391 |   0.296807 |
| k-d_tree_pandas      |     0.270221 |       0.239211 |   0.337632 |
| Bori_Aron_solution-1 |     0.268842 |       0.339332 |   0.337729 |
| k-d_tree_sklearn     |     0.27192  |       0.632293 |   0.658131 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.270297 |       0.28802  |   0.305196 |
| barab-szabi-1        |     0.270432 |       0.292364 |   0.30918  |
| barab-szabi-2        |     0.270767 |       0.289701 |   0.333088 |
| Bori_Aron_solution-1 |     0.268572 |       0.367512 |   0.335417 |
| k-d_tree_pandas      |     0.286135 |       0.261338 |   0.360353 |
| k-d_tree_sklearn     |     0.273161 |       0.649087 |   0.676646 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.269056 |       0.31761  |   0.313003 |
| k-d_tree_polars      |     0.304479 |       0.345946 |   0.343288 |
| Bori_Aron_solution-1 |     0.271643 |       0.47022  |   0.34985  |
| barab-szabi-1        |     0.27207  |       0.35256  |   0.350557 |
| k-d_tree_pandas      |     0.271654 |       0.299645 |   0.424985 |
| k-d_tree_sklearn     |     0.272429 |       0.792167 |   0.702141 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.271313 |       0.47852  |   0.338897 |
| Bori_Aron_solution-1 |     0.266963 |       0.837788 |   0.362431 |
| k-d_tree_polars      |     0.273755 |       0.53255  |   0.563165 |
| barab-szabi-1        |     0.268552 |       0.52715  |   0.587451 |
| k-d_tree_sklearn     |     0.27439  |       1.22658  |   0.714761 |
| k-d_tree_pandas      |     0.282792 |       0.449775 |   0.75069  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.272216 |        3.34265 |   0.524198 |
| Bori_Aron_solution-1 |     0.277098 |        6.50677 |   0.528599 |
| k-d_tree_sklearn     |     0.275681 |       10.5005  |   0.792874 |
| k-d_tree_polars      |     0.269058 |        3.4005  |   4.42232  |
| barab-szabi-1        |     0.271183 |        3.44883 |   4.5778   |
| k-d_tree_pandas      |     0.271825 |        2.18581 |   4.76457  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.393554 |       151.182  |    1.96573 |
| barab-szabi-2        |     0.449432 |        55.9228 |    2.20106 |
| Bori_Aron_solution-1 |     0.26688  |       126.746  |   14.9907  |