# 2026-05-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473782 |       0.438497 |   0.442883 |
| solution-1           |     8.53565  |       1e-06    |   0.453223 |
| barab-szabi-1        |     0.4839   |       0.417483 |   0.456715 |
| k-d_tree_polars      |     0.475935 |       0.444105 |   0.471445 |
| Bori_Aron_solution-1 |     0.620837 |       0.554792 |   0.560128 |
| k-d_tree_pandas      |     0.483795 |       0.399088 |   0.563979 |
| k-d_tree_sklearn     |    11.3063   |       1.50641  |   1.11309  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.493066 |       0.434289 |   0.446814 |
| barab-szabi-2        |     0.496191 |       0.45888  |   0.451793 |
| barab-szabi-1        |     0.490849 |       0.429576 |   0.453945 |
| k-d_tree_pandas      |     0.479509 |       0.401536 |   0.579221 |
| Bori_Aron_solution-1 |     0.472163 |       0.600715 |   0.586997 |
| k-d_tree_sklearn     |     0.487244 |       1.01146  |   1.11923  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482564 |       0.468802 |   0.466654 |
| k-d_tree_polars      |     0.490665 |       0.47973  |   0.488285 |
| barab-szabi-1        |     0.477875 |       0.463293 |   0.498141 |
| Bori_Aron_solution-1 |     0.470197 |       0.646925 |   0.589054 |
| k-d_tree_pandas      |     0.483978 |       0.428289 |   0.631426 |
| k-d_tree_sklearn     |     0.480765 |       1.08262  |   1.16632  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48801  |       0.540856 |   0.520347 |
| k-d_tree_polars      |     0.483286 |       0.581048 |   0.580203 |
| Bori_Aron_solution-1 |     0.469821 |       0.805884 |   0.584452 |
| barab-szabi-1        |     0.482967 |       0.579393 |   0.600556 |
| k-d_tree_pandas      |     0.485618 |       0.523498 |   0.782765 |
| k-d_tree_sklearn     |     0.48742  |       1.32994  |   1.20767  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477986 |       0.750142 |   0.541965 |
| Bori_Aron_solution-1 |     0.474444 |       1.48594  |   0.611287 |
| k-d_tree_polars      |     0.475461 |       0.944961 |   0.943122 |
| barab-szabi-1        |     0.478957 |       0.948685 |   0.976979 |
| k-d_tree_pandas      |     0.477777 |       0.83249  |   1.20869  |
| k-d_tree_sklearn     |     0.486814 |       2.22913  |   1.2858   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480897 |        5.41017 |   0.790379 |
| Bori_Aron_solution-1 |     0.487971 |       11.3446  |   0.827966 |
| k-d_tree_sklearn     |     0.489475 |       17.8692  |   1.37983  |
| k-d_tree_polars      |     0.473842 |        5.54671 |   6.97299  |
| barab-szabi-1        |     0.503047 |        5.58572 |   7.05673  |
| k-d_tree_pandas      |     0.5014   |        4.55891 |   7.4655   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.760255 |        72.1458 |    2.63314 |
| k-d_tree_sklearn     |     0.500579 |       242.461  |    3.77108 |
| Bori_Aron_solution-1 |     0.460659 |       155.536  |   22.5958  |