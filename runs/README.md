# 2026-03-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482211 |       0.434464 |   0.436331 |
| k-d_tree_polars      |     0.489433 |       0.409316 |   0.441684 |
| solution-1           |     8.56141  |       1e-06    |   0.469543 |
| barab-szabi-1        |     9.40082  |       0.446081 |   0.500692 |
| Bori_Aron_solution-1 |     0.483433 |       0.557557 |   0.549815 |
| k-d_tree_pandas      |     0.490097 |       0.391646 |   0.562351 |
| k-d_tree_sklearn     |     3.20913  |       1.10986  |   1.08721  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.496891 |       0.418405 |   0.445414 |
| barab-szabi-2        |     0.495101 |       0.443461 |   0.446893 |
| k-d_tree_polars      |     0.499348 |       0.429678 |   0.454988 |
| Bori_Aron_solution-1 |     0.493274 |       0.569455 |   0.559126 |
| k-d_tree_pandas      |     0.502648 |       0.41292  |   0.576039 |
| k-d_tree_sklearn     |     0.517633 |       0.99302  |   1.12191  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499371 |       0.476311 |   0.46685  |
| barab-szabi-1        |     0.503473 |       0.444467 |   0.468866 |
| k-d_tree_polars      |     0.497725 |       0.442349 |   0.474304 |
| Bori_Aron_solution-1 |     0.499001 |       0.602005 |   0.558815 |
| k-d_tree_pandas      |     0.496742 |       0.423563 |   0.613563 |
| k-d_tree_sklearn     |     0.509881 |       1.04568  |   1.10719  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.501667 |       0.51997  |   0.48269  |
| Bori_Aron_solution-1 |     0.492106 |       0.809044 |   0.572277 |
| k-d_tree_polars      |     0.499724 |       0.576943 |   0.572413 |
| barab-szabi-1        |     0.4991   |       0.571283 |   0.580373 |
| k-d_tree_pandas      |     0.496442 |       0.508624 |   0.747    |
| k-d_tree_sklearn     |     0.504786 |       1.28313  |   1.16362  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497488 |       0.739862 |   0.518383 |
| Bori_Aron_solution-1 |     0.490959 |       1.50735  |   0.605849 |
| k-d_tree_polars      |     0.501451 |       0.939425 |   0.925456 |
| barab-szabi-1        |     0.497086 |       0.932292 |   0.974035 |
| k-d_tree_pandas      |     0.497902 |       0.839918 |   1.21142  |
| k-d_tree_sklearn     |     0.506994 |       2.17506  |   1.245    |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499949 |        5.42451 |   0.747454 |
| Bori_Aron_solution-1 |     0.502303 |       11.442   |   0.865422 |
| k-d_tree_sklearn     |     0.50115  |       17.6654  |   1.33868  |
| k-d_tree_polars      |     0.53229  |        5.47344 |   6.71043  |
| barab-szabi-1        |     0.502392 |        5.52495 |   6.86064  |
| k-d_tree_pandas      |     0.500709 |        4.49476 |   7.25134  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.505825 |        74.3135 |    2.69469 |
| k-d_tree_sklearn     |     0.834205 |       246.995  |    4.08423 |
| Bori_Aron_solution-1 |     0.53298  |       151.211  |   19.5201  |