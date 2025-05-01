# 2025-05-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.55302  |       1e-06    |   0.369303 |
| barab-szabi-1        |     0.523482 |       0.408892 |   0.423387 |
| barab-szabi-2        |     0.520334 |       0.431921 |   0.425745 |
| k-d_tree_polars      |     7.77099  |       0.433417 |   0.465895 |
| k-d_tree_pandas      |     0.532241 |       0.401412 |   0.563095 |
| Bori_Aron_solution-1 |     0.525496 |       0.568045 |   0.573448 |
| k-d_tree_sklearn     |     2.9696   |       1.01748  |   1.03989  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536893 |       0.420993 |   0.425301 |
| barab-szabi-1        |     0.603065 |       0.42112  |   0.42723  |
| k-d_tree_polars      |     0.530926 |       0.414887 |   0.431432 |
| Bori_Aron_solution-1 |     0.53093  |       0.580056 |   0.571537 |
| k-d_tree_pandas      |     0.535572 |       0.415699 |   0.57249  |
| k-d_tree_sklearn     |     0.539192 |       0.979421 |   1.07079  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534357 |       0.433496 |   0.430431 |
| k-d_tree_polars      |     0.528115 |       0.441085 |   0.449813 |
| barab-szabi-1        |     0.534201 |       0.440408 |   0.453972 |
| Bori_Aron_solution-1 |     0.524179 |       0.59428  |   0.559606 |
| k-d_tree_pandas      |     0.541062 |       0.420569 |   0.612397 |
| k-d_tree_sklearn     |     0.531976 |       1.04369  |   1.10771  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528206 |       0.498881 |   0.461807 |
| k-d_tree_polars      |     0.536237 |       0.557722 |   0.560101 |
| barab-szabi-1        |     0.538767 |       0.563025 |   0.561334 |
| Bori_Aron_solution-1 |     0.52965  |       0.777282 |   0.5834   |
| k-d_tree_pandas      |     0.54367  |       0.495367 |   0.743725 |
| k-d_tree_sklearn     |     0.529133 |       1.28425  |   1.18802  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537279 |       0.748131 |   0.496191 |
| Bori_Aron_solution-1 |     0.526621 |       1.4389   |   0.620199 |
| k-d_tree_polars      |     0.535735 |       0.893245 |   0.934818 |
| barab-szabi-1        |     0.540029 |       0.904338 |   0.965621 |
| k-d_tree_pandas      |     0.534327 |       0.772381 |   1.20406  |
| k-d_tree_sklearn     |     0.535623 |       2.10183  |   1.22209  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528604 |        5.54919 |   0.774948 |
| Bori_Aron_solution-1 |     0.542319 |       10.8472  |   0.886117 |
| k-d_tree_sklearn     |     0.533499 |       16.9017  |   1.33241  |
| barab-szabi-1        |     0.548221 |        5.05152 |   6.81678  |
| k-d_tree_polars      |     0.533726 |        5.06125 |   6.938    |
| k-d_tree_pandas      |     0.543629 |        3.99302 |   7.16263  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529938 |        78.3169 |    2.65557 |
| k-d_tree_sklearn     |     0.816298 |       230.922  |    4.25482 |
| Bori_Aron_solution-1 |     0.529314 |       144.096  |   18.256   |