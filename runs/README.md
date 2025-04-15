# 2025-04-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.1993   |       1e-06    |   0.360875 |
| barab-szabi-2        |     0.551051 |       0.415147 |   0.409611 |
| k-d_tree_polars      |     0.566819 |       0.405185 |   0.416652 |
| barab-szabi-1        |     0.554152 |       0.404145 |   0.423326 |
| Bori_Aron_solution-1 |     0.552456 |       0.553954 |   0.555154 |
| k-d_tree_pandas      |     7.4001   |       0.402021 |   0.582857 |
| k-d_tree_sklearn     |     2.88359  |       0.986885 |   1.02486  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575579 |       0.426717 |   0.409956 |
| barab-szabi-1        |     0.573364 |       0.412172 |   0.416185 |
| k-d_tree_polars      |     0.567212 |       0.411785 |   0.418313 |
| Bori_Aron_solution-1 |     0.570638 |       0.551599 |   0.546188 |
| k-d_tree_pandas      |     0.570448 |       0.390485 |   0.611733 |
| k-d_tree_sklearn     |     0.572541 |       0.983514 |   1.02902  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573859 |       0.426656 |   0.41443  |
| barab-szabi-1        |     0.567004 |       0.438741 |   0.448025 |
| k-d_tree_polars      |     0.570987 |       0.434396 |   0.460957 |
| Bori_Aron_solution-1 |     0.561113 |       0.590385 |   0.54905  |
| k-d_tree_pandas      |     0.570841 |       0.405757 |   0.606125 |
| k-d_tree_sklearn     |     0.57213  |       1.02587  |   1.07648  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559757 |       0.485394 |   0.451683 |
| k-d_tree_polars      |     0.567387 |       0.540658 |   0.537122 |
| barab-szabi-1        |     0.587489 |       0.541742 |   0.550278 |
| Bori_Aron_solution-1 |     0.565095 |       0.765779 |   0.564259 |
| k-d_tree_pandas      |     0.564958 |       0.482189 |   0.731972 |
| k-d_tree_sklearn     |     0.574929 |       1.22311  |   1.13929  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568825 |       0.727241 |   0.48523  |
| Bori_Aron_solution-1 |     0.558564 |       1.39134  |   0.598939 |
| k-d_tree_polars      |     0.565896 |       0.867241 |   0.894875 |
| barab-szabi-1        |     0.568427 |       0.863988 |   0.932599 |
| k-d_tree_pandas      |     0.57026  |       0.740232 |   1.17853  |
| k-d_tree_sklearn     |     0.57031  |       2.05879  |   1.20466  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56082  |        5.37284 |   0.730417 |
| Bori_Aron_solution-1 |     0.564369 |       10.631   |   0.882032 |
| k-d_tree_sklearn     |     0.577833 |       16.5272  |   1.34255  |
| k-d_tree_polars      |     0.566679 |        4.92791 |   6.62712  |
| barab-szabi-1        |     0.567279 |        4.93121 |   6.64298  |
| k-d_tree_pandas      |     0.56605  |        3.82961 |   7.05687  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.792121 |         72.753 |    3.26314 |
| k-d_tree_sklearn     |     0.64099  |        230.878 |    4.23179 |
| Bori_Aron_solution-1 |     0.56178  |        147.144 |   16.232   |