# 2026-01-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529331 |       0.510232 |   0.428608 |
| k-d_tree_polars      |     0.529954 |       0.404999 |   0.431798 |
| barab-szabi-1        |     0.545118 |       0.409405 |   0.434484 |
| Bori_Aron_solution-1 |     0.520298 |       0.543372 |   0.548112 |
| solution-1           |     7.32073  |       1e-06    |   0.584179 |
| k-d_tree_pandas      |     8.06684  |       0.444428 |   0.772268 |
| k-d_tree_sklearn     |     2.9472   |       1.12641  |   1.169    |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528132 |       0.433259 |   0.431269 |
| barab-szabi-1        |     0.539067 |       0.411699 |   0.437457 |
| k-d_tree_polars      |     0.532347 |       0.407085 |   0.444268 |
| Bori_Aron_solution-1 |     0.523289 |       0.551496 |   0.546443 |
| k-d_tree_pandas      |     0.529986 |       0.390087 |   0.561858 |
| k-d_tree_sklearn     |     0.532542 |       0.96992  |   1.06744  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532297 |       0.44773  |   0.452242 |
| barab-szabi-1        |     0.53482  |       0.440672 |   0.461959 |
| k-d_tree_polars      |     0.527355 |       0.439643 |   0.466004 |
| Bori_Aron_solution-1 |     0.522415 |       0.590895 |   0.547229 |
| k-d_tree_pandas      |     0.530225 |       0.411491 |   0.598427 |
| k-d_tree_sklearn     |     0.533325 |       1.02028  |   1.09325  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532335 |       0.514064 |   0.516699 |
| k-d_tree_polars      |     0.526378 |       0.56635  |   0.55909  |
| Bori_Aron_solution-1 |     0.525334 |       0.780184 |   0.567324 |
| barab-szabi-1        |     0.525223 |       0.554876 |   0.570677 |
| k-d_tree_pandas      |     0.527616 |       0.508667 |   0.740439 |
| k-d_tree_sklearn     |     0.530521 |       1.25518  |   1.1423   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529394 |       0.746673 |   0.502645 |
| Bori_Aron_solution-1 |     0.521738 |       1.45729  |   0.585505 |
| k-d_tree_polars      |     0.529567 |       0.893529 |   0.910814 |
| barab-szabi-1        |     0.528523 |       0.924333 |   0.961856 |
| k-d_tree_pandas      |     0.530414 |       0.813481 |   1.18127  |
| k-d_tree_sklearn     |     0.538723 |       2.11466  |   1.22035  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529794 |        5.21349 |   0.753476 |
| Bori_Aron_solution-1 |     0.520947 |       11.207   |   0.839926 |
| k-d_tree_sklearn     |     0.53083  |       16.8242  |   1.29702  |
| barab-szabi-1        |     0.526903 |        5.41153 |   6.62886  |
| k-d_tree_polars      |     0.529205 |        5.39499 |   6.66661  |
| k-d_tree_pandas      |     0.535012 |        4.37947 |   7.05606  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525516 |        77.6778 |    2.8044  |
| k-d_tree_sklearn     |     0.537029 |       238.776  |    4.09696 |
| Bori_Aron_solution-1 |     0.651628 |       148.482  |   18.3046  |