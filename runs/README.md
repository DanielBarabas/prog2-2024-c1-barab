# 2024-05-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.67909  |       0.357904 |   0.344738 |
| k-d_tree_polars      |     0.786084 |       0.399694 |   0.345839 |
| barab-szabi-1        |     0.785519 |       0.39748  |   0.347782 |
| solution-1           |     7.96895  |       1.4e-05  |   0.36542  |
| Bori_Aron_solution-1 |     4.77004  |       0.416984 |   0.407598 |
| k-d_tree_pandas      |     0.792453 |       0.383405 |   0.484399 |
| k-d_tree_sklearn     |     3.24622  |       0.912113 |   0.657301 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.790599 |       0.355576 |   0.346268 |
| k-d_tree_polars      |     0.78979  |       0.409549 |   0.351891 |
| barab-szabi-1        |     0.780635 |       0.412238 |   0.370065 |
| Bori_Aron_solution-1 |     0.776598 |       0.481426 |   0.469501 |
| k-d_tree_pandas      |     0.779169 |       0.390186 |   0.504584 |
| k-d_tree_sklearn     |     0.811496 |       0.841248 |   0.668342 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.788493 |       0.379548 |   0.362233 |
| k-d_tree_polars      |     0.778976 |       0.431445 |   0.376244 |
| barab-szabi-1        |     0.783229 |       0.44282  |   0.379714 |
| Bori_Aron_solution-1 |     0.784868 |       0.521817 |   0.478544 |
| k-d_tree_pandas      |     0.788307 |       0.403337 |   0.532738 |
| k-d_tree_sklearn     |     0.784784 |       0.887639 |   0.693115 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.795384 |       0.433222 |   0.390407 |
| k-d_tree_polars      |     0.779954 |       0.541246 |   0.479842 |
| barab-szabi-1        |     0.789122 |       0.544418 |   0.49003  |
| Bori_Aron_solution-1 |     0.777966 |       0.700739 |   0.490332 |
| k-d_tree_pandas      |     0.779317 |       0.489523 |   0.662688 |
| k-d_tree_sklearn     |     0.793705 |       1.11194  |   0.756251 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.773128 |       0.691895 |   0.434217 |
| Bori_Aron_solution-1 |     0.780768 |       1.35195  |   0.520122 |
| k-d_tree_polars      |     0.778463 |       0.870538 |   0.828132 |
| k-d_tree_sklearn     |     0.795631 |       1.94307  |   0.862629 |
| barab-szabi-1        |     0.784584 |       0.90175  |   0.874721 |
| k-d_tree_pandas      |     0.781694 |       0.76525  |   1.09284  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.78324  |        5.29081 |   0.740807 |
| Bori_Aron_solution-1 |     0.775824 |       10.8011  |   0.780091 |
| k-d_tree_sklearn     |     0.819427 |       15.7429  |   1.06139  |
| k-d_tree_polars      |     0.785022 |        4.99963 |   6.53808  |
| barab-szabi-1        |     0.783827 |        5.01619 |   6.62871  |
| k-d_tree_pandas      |     0.780121 |        4.02598 |   6.85558  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.14221  |        75.5849 |    3.61288 |
| k-d_tree_sklearn     |     0.946574 |       236.63   |    4.858   |
| Bori_Aron_solution-1 |     0.771187 |       156.402  |   17.9988  |