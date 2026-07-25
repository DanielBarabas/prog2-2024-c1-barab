# 2026-07-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.57675  |       1e-06    |   0.24905  |
| barab-szabi-2        |     0.314491 |       0.310296 |   0.309888 |
| barab-szabi-1        |     0.314191 |       0.293384 |   0.313554 |
| k-d_tree_pandas      |     0.322031 |       0.273899 |   0.381041 |
| Bori_Aron_solution-1 |     0.357509 |       0.395178 |   0.384801 |
| k-d_tree_polars      |     9.96301  |       0.504035 |   0.50277  |
| k-d_tree_sklearn     |     2.91599  |       1.18523  |   0.744781 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.312954 |       0.294239 |   0.314536 |
| barab-szabi-2        |     0.313298 |       0.304103 |   0.316755 |
| k-d_tree_polars      |     0.31314  |       0.287693 |   0.322907 |
| Bori_Aron_solution-1 |     0.311364 |       0.382133 |   0.385473 |
| k-d_tree_pandas      |     0.310786 |       0.280736 |   0.388258 |
| k-d_tree_sklearn     |     0.32416  |       0.706399 |   0.741719 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.316645 |       0.324924 |   0.326699 |
| k-d_tree_polars      |     0.312919 |       0.334556 |   0.334155 |
| barab-szabi-1        |     0.313652 |       0.32369  |   0.33421  |
| Bori_Aron_solution-1 |     0.316754 |       0.418263 |   0.393562 |
| k-d_tree_pandas      |     0.315417 |       0.29077  |   0.414882 |
| k-d_tree_sklearn     |     0.320949 |       0.722793 |   0.753026 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.314789 |       0.36261  |   0.352893 |
| k-d_tree_polars      |     0.317737 |       0.409046 |   0.388281 |
| barab-szabi-1        |     0.31651  |       0.409105 |   0.401784 |
| Bori_Aron_solution-1 |     0.305358 |       0.537473 |   0.439147 |
| k-d_tree_pandas      |     0.313631 |       0.349676 |   0.5059   |
| k-d_tree_sklearn     |     0.31544  |       0.892216 |   0.77709  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.314224 |       0.551203 |   0.387421 |
| Bori_Aron_solution-1 |     0.31004  |       0.99619  |   0.430473 |
| k-d_tree_polars      |     0.314837 |       0.8173   |   0.642497 |
| barab-szabi-1        |     0.312758 |       0.635329 |   0.67167  |
| k-d_tree_pandas      |     0.318798 |       0.526104 |   0.793888 |
| k-d_tree_sklearn     |     0.321285 |       1.46337  |   0.809556 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.309934 |        3.65172 |   0.609188 |
| Bori_Aron_solution-1 |     0.348648 |        7.58976 |   0.729819 |
| k-d_tree_sklearn     |     0.323475 |       11.8443  |   0.95838  |
| barab-szabi-1        |     0.313128 |        4.46637 |   4.78154  |
| k-d_tree_pandas      |     0.314513 |        2.68912 |   5.01397  |
| k-d_tree_polars      |     0.317627 |        4.3149  |   5.13054  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.79996  |        59.8243 |    3.32117 |
| k-d_tree_sklearn     |     1.23273  |       168.157  |    5.78875 |
| Bori_Aron_solution-1 |     0.310449 |       154.315  |   71.1119  |