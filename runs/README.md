# 2026-06-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.428788 |       0.378768 |   0.413086 |
| barab-szabi-2        |     0.7732   |       0.423424 |   0.430882 |
| Bori_Aron_solution-1 |     0.413043 |       0.510753 |   0.508031 |
| k-d_tree_pandas      |     0.424415 |       0.366075 |   0.52194  |
| solution-1           |     7.92558  |       1e-06    |   0.549373 |
| barab-szabi-1        |     9.5133   |       0.431081 |   0.642885 |
| k-d_tree_sklearn     |     2.86515  |       1.01824  |   0.980228 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.427382 |       0.39522  |   0.424822 |
| barab-szabi-1        |     0.431856 |       0.38732  |   0.425795 |
| barab-szabi-2        |     0.429308 |       0.41694  |   0.429923 |
| Bori_Aron_solution-1 |     0.425609 |       0.520191 |   0.513915 |
| k-d_tree_pandas      |     0.428009 |       0.364613 |   0.519487 |
| k-d_tree_sklearn     |     0.451423 |       0.90865  |   0.990307 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.43637  |       0.432274 |   0.438612 |
| k-d_tree_polars      |     0.43757  |       0.428575 |   0.448353 |
| barab-szabi-1        |     0.435715 |       0.418042 |   0.453604 |
| Bori_Aron_solution-1 |     0.42951  |       0.560141 |   0.529217 |
| k-d_tree_pandas      |     0.451075 |       0.388163 |   0.562756 |
| k-d_tree_sklearn     |     0.439037 |       0.961508 |   1.03179  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.448042 |       0.484213 |   0.451711 |
| Bori_Aron_solution-1 |     0.422095 |       0.720821 |   0.52719  |
| k-d_tree_polars      |     0.430009 |       0.529646 |   0.529978 |
| barab-szabi-1        |     0.431881 |       0.536258 |   0.545619 |
| k-d_tree_pandas      |     0.426052 |       0.462754 |   0.677415 |
| k-d_tree_sklearn     |     0.434088 |       1.15914  |   1.0509   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.427987 |       0.709206 |   0.497139 |
| Bori_Aron_solution-1 |     0.427174 |       1.3288   |   0.565621 |
| k-d_tree_polars      |     0.434859 |       0.856087 |   0.833612 |
| barab-szabi-1        |     0.426511 |       0.843546 |   0.869268 |
| k-d_tree_pandas      |     0.430382 |       0.733518 |   1.06189  |
| k-d_tree_sklearn     |     0.434903 |       1.9105   |   1.10352  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.432768 |        4.88151 |   0.699056 |
| Bori_Aron_solution-1 |     0.421319 |        9.90392 |   0.860983 |
| k-d_tree_sklearn     |     0.434863 |       14.914   |   1.26368  |
| k-d_tree_polars      |     0.436814 |        4.88902 |   6.1557   |
| barab-szabi-1        |     0.427161 |        4.86298 |   6.1698   |
| k-d_tree_pandas      |     0.432719 |        3.84666 |   6.47543  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.428648 |        65.5246 |    2.55297 |
| k-d_tree_sklearn     |     0.675527 |       174.825  |    4.0264  |
| Bori_Aron_solution-1 |     0.427704 |       136.183  |   15.6047  |