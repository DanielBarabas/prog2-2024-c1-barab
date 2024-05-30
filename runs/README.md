# 2024-05-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.96324  |       0.40021  |   0.340049 |
| k-d_tree_polars      |     0.787574 |       0.397443 |   0.341672 |
| barab-szabi-1        |     0.791289 |       0.395898 |   0.341938 |
| Bori_Aron_solution-1 |     4.6727   |       0.407367 |   0.4036   |
| k-d_tree_pandas      |     0.783384 |       0.38071  |   0.474254 |
| k-d_tree_sklearn     |     3.49058  |       1.17258  |   0.668651 |
| solution-1           |     8.24554  |       1e-06    |   0.671666 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.783712 |       0.342735 |   0.343026 |
| barab-szabi-1        |     0.801847 |       0.412039 |   0.348933 |
| k-d_tree_polars      |     0.793704 |       0.423636 |   0.368405 |
| Bori_Aron_solution-1 |     0.779385 |       0.48147  |   0.467519 |
| k-d_tree_pandas      |     0.786492 |       0.39232  |   0.486647 |
| k-d_tree_sklearn     |     0.7996   |       0.873722 |   0.776957 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.803446 |       0.358267 |   0.351078 |
| k-d_tree_polars      |     0.786631 |       0.429278 |   0.371335 |
| barab-szabi-1        |     0.785818 |       0.428713 |   0.379508 |
| Bori_Aron_solution-1 |     0.783109 |       0.517599 |   0.474634 |
| k-d_tree_pandas      |     0.792801 |       0.412452 |   0.524761 |
| k-d_tree_sklearn     |     0.80607  |       0.895255 |   0.70332  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.785856 |       0.423669 |   0.390811 |
| k-d_tree_polars      |     0.788704 |       0.539938 |   0.476436 |
| barab-szabi-1        |     0.790637 |       0.546309 |   0.486781 |
| Bori_Aron_solution-1 |     0.782605 |       0.697613 |   0.487743 |
| k-d_tree_pandas      |     0.800081 |       0.49373  |   0.668709 |
| k-d_tree_sklearn     |     0.798481 |       1.12216  |   0.76532  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.792994 |       0.681434 |   0.424606 |
| Bori_Aron_solution-1 |     0.78591  |       1.34815  |   0.517559 |
| k-d_tree_polars      |     0.790498 |       0.866801 |   0.826511 |
| k-d_tree_sklearn     |     0.800741 |       1.9441   |   0.86801  |
| barab-szabi-1        |     0.78442  |       0.867189 |   0.874281 |
| k-d_tree_pandas      |     0.807662 |       0.766138 |   1.10556  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.793059 |        5.45863 |   0.769728 |
| Bori_Aron_solution-1 |     0.779544 |       10.6955  |   0.773602 |
| k-d_tree_sklearn     |     0.788772 |       15.8858  |   1.04085  |
| k-d_tree_polars      |     0.810977 |        4.97223 |   6.47208  |
| barab-szabi-1        |     0.789329 |        4.98143 |   6.48872  |
| k-d_tree_pandas      |     0.787406 |        4.01714 |   6.93145  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.98722  |        75.4237 |    3.99841 |
| k-d_tree_sklearn     |     0.931577 |       240.067  |    4.66099 |
| Bori_Aron_solution-1 |     0.780659 |       151.255  |   18.7243  |