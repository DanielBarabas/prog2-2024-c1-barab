# 2026-08-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.30828  |       0.514121 |   0.443194 |
| barab-szabi-1        |     0.461511 |       0.404935 |   0.458701 |
| Bori_Aron_solution-1 |     4.56691  |       0.702295 |   0.483649 |
| k-d_tree_polars      |     0.456504 |       0.411632 |   0.488279 |
| solution-1           |     8.09743  |       1e-06    |   0.493534 |
| k-d_tree_pandas      |     0.455221 |       0.383048 |   0.545914 |
| k-d_tree_sklearn     |     3.05857  |       1.20993  |   1.07059  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467751 |       0.440031 |   0.448975 |
| barab-szabi-1        |     0.47239  |       0.42221  |   0.458885 |
| k-d_tree_polars      |     0.472029 |       0.414872 |   0.460048 |
| Bori_Aron_solution-1 |     0.463842 |       0.554424 |   0.552152 |
| k-d_tree_pandas      |     0.4684   |       0.39448  |   0.558377 |
| k-d_tree_sklearn     |     0.472768 |       1.00147  |   1.07606  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466712 |       0.455148 |   0.456799 |
| barab-szabi-1        |     0.46627  |       0.449617 |   0.478385 |
| k-d_tree_polars      |     0.471382 |       0.451756 |   0.480332 |
| Bori_Aron_solution-1 |     0.460923 |       0.588404 |   0.549288 |
| k-d_tree_pandas      |     0.466545 |       0.409304 |   0.592517 |
| k-d_tree_sklearn     |     0.47726  |       1.04616  |   1.0865   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469453 |       0.534029 |   0.483281 |
| Bori_Aron_solution-1 |     0.471376 |       0.773612 |   0.559292 |
| k-d_tree_polars      |     0.466668 |       0.567565 |   0.571142 |
| barab-szabi-1        |     0.464922 |       0.577509 |   0.583993 |
| k-d_tree_pandas      |     0.467372 |       0.497112 |   0.73105  |
| k-d_tree_sklearn     |     0.471588 |       1.27682  |   1.14962  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469575 |       0.731019 |   0.515836 |
| Bori_Aron_solution-1 |     0.460672 |       1.42173  |   0.579731 |
| k-d_tree_polars      |     0.473403 |       0.923283 |   0.907779 |
| barab-szabi-1        |     0.465132 |       0.922653 |   0.966318 |
| k-d_tree_sklearn     |     0.474168 |       2.08524  |   1.2196   |
| k-d_tree_pandas      |     0.470126 |       0.801925 |   1.23346  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467032 |        5.22329 |   0.786927 |
| Bori_Aron_solution-1 |     0.464036 |       10.8256  |   0.813982 |
| k-d_tree_sklearn     |     0.477044 |       16.5386  |   1.29477  |
| k-d_tree_polars      |     0.470842 |        5.23533 |   6.59854  |
| barab-szabi-1        |     0.508425 |        5.27896 |   6.60917  |
| k-d_tree_pandas      |     0.489557 |        4.33465 |   6.94576  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.747657 |        71.9621 |    2.9284  |
| k-d_tree_sklearn     |     0.583952 |       240.96   |    3.97946 |
| Bori_Aron_solution-1 |     0.461622 |       149.844  |   23.0609  |