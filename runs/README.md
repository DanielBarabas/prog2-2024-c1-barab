# 2026-01-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.93391  |       1e-06    |   0.435574 |
| barab-szabi-2        |     0.565219 |       0.479233 |   0.461671 |
| barab-szabi-1        |     0.578294 |       0.446517 |   0.470215 |
| k-d_tree_polars      |     0.576545 |       0.443772 |   0.47685  |
| Bori_Aron_solution-1 |     0.565898 |       0.693906 |   0.593884 |
| k-d_tree_pandas      |     8.70476  |       0.461597 |   0.670419 |
| k-d_tree_sklearn     |     3.22341  |       1.13412  |   1.15763  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.569072 |       0.458289 |   0.467093 |
| barab-szabi-2        |     0.555245 |       0.469844 |   0.470186 |
| barab-szabi-1        |     0.570755 |       0.445422 |   0.470538 |
| k-d_tree_pandas      |     0.574112 |       0.424184 |   0.603477 |
| Bori_Aron_solution-1 |     0.559914 |       0.609123 |   0.606322 |
| k-d_tree_sklearn     |     0.570862 |       1.07574  |   1.1729   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.568987 |       0.46333  |   0.495337 |
| k-d_tree_polars      |     0.572485 |       0.487544 |   0.503519 |
| barab-szabi-2        |     0.564294 |       0.472482 |   0.52326  |
| Bori_Aron_solution-1 |     0.554522 |       0.645534 |   0.598497 |
| k-d_tree_pandas      |     0.565374 |       0.444326 |   0.646623 |
| k-d_tree_sklearn     |     0.570727 |       1.13026  |   1.21495  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574928 |       0.536371 |   0.50284  |
| k-d_tree_polars      |     0.58106  |       0.591074 |   0.597372 |
| barab-szabi-1        |     0.57224  |       0.589467 |   0.611179 |
| Bori_Aron_solution-1 |     0.559006 |       0.833795 |   0.622776 |
| k-d_tree_pandas      |     0.564596 |       0.537226 |   0.804866 |
| k-d_tree_sklearn     |     0.564494 |       1.35518  |   1.23941  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575557 |       0.819475 |   0.650141 |
| Bori_Aron_solution-1 |     0.562752 |       1.56931  |   0.65231  |
| k-d_tree_polars      |     0.575714 |       0.974093 |   0.995845 |
| barab-szabi-1        |     0.572648 |       0.985049 |   1.05556  |
| k-d_tree_pandas      |     0.564447 |       0.873729 |   1.29327  |
| k-d_tree_sklearn     |     0.582052 |       2.34536  |   1.3071   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58004  |        5.65071 |   0.819702 |
| Bori_Aron_solution-1 |     0.566269 |       11.6112  |   0.893461 |
| k-d_tree_sklearn     |     0.573858 |       18.2677  |   1.42693  |
| barab-szabi-1        |     0.5788   |        5.49178 |   7.08905  |
| k-d_tree_polars      |     0.564646 |        5.4657  |   7.12907  |
| k-d_tree_pandas      |     0.581095 |        4.52871 |   7.62023  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581493 |        84.3475 |    2.85524 |
| k-d_tree_sklearn     |     0.585505 |       251.618  |    4.5262  |
| Bori_Aron_solution-1 |     0.721116 |       156.566  |   17.9785  |