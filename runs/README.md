# 2026-08-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.02941  |       1e-06    |   0.428271 |
| barab-szabi-2        |     4.50762  |       0.475918 |   0.452882 |
| k-d_tree_polars      |     0.476485 |       0.442179 |   0.454268 |
| barab-szabi-1        |     0.479507 |       0.4494   |   0.462044 |
| Bori_Aron_solution-1 |     4.88423  |       0.68959  |   0.514861 |
| k-d_tree_pandas      |     0.482764 |       0.40405  |   0.596824 |
| k-d_tree_sklearn     |     3.07428  |       1.26692  |   1.14252  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484122 |       0.453287 |   0.456427 |
| barab-szabi-1        |     0.488435 |       0.443234 |   0.463961 |
| k-d_tree_polars      |     0.483617 |       0.4588   |   0.464753 |
| Bori_Aron_solution-1 |     0.479176 |       0.59618  |   0.562344 |
| k-d_tree_pandas      |     0.49141  |       0.407116 |   0.588498 |
| k-d_tree_sklearn     |     0.490863 |       1.06545  |   1.12709  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486718 |       0.467988 |   0.46429  |
| k-d_tree_polars      |     0.487729 |       0.47361  |   0.481506 |
| barab-szabi-1        |     0.494654 |       0.478044 |   0.483233 |
| Bori_Aron_solution-1 |     0.478647 |       0.625232 |   0.577421 |
| k-d_tree_pandas      |     0.501557 |       0.425417 |   0.609319 |
| k-d_tree_sklearn     |     0.488888 |       1.13116  |   1.14317  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491497 |       0.530481 |   0.493261 |
| k-d_tree_polars      |     0.494061 |       0.595316 |   0.585607 |
| barab-szabi-1        |     0.49453  |       0.590498 |   0.596183 |
| Bori_Aron_solution-1 |     0.489367 |       0.812743 |   0.62292  |
| k-d_tree_pandas      |     0.49035  |       0.51368  |   0.745538 |
| k-d_tree_sklearn     |     0.496655 |       1.3495   |   1.19059  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485401 |       0.797713 |   0.582662 |
| Bori_Aron_solution-1 |     0.488147 |       1.5152   |   0.607034 |
| k-d_tree_polars      |     0.490247 |       0.925734 |   0.998106 |
| barab-szabi-1        |     0.48767  |       0.935943 |   1.02873  |
| k-d_tree_pandas      |     0.488368 |       0.780148 |   1.21363  |
| k-d_tree_sklearn     |     0.506875 |       2.30259  |   1.24663  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.493251 |        5.99579 |   0.78452  |
| Bori_Aron_solution-1 |     0.490661 |       11.7841  |   0.840521 |
| k-d_tree_sklearn     |     0.491809 |       18.5781  |   1.36687  |
| barab-szabi-1        |     0.50491  |        5.10462 |   7.80817  |
| k-d_tree_polars      |     0.487707 |        5.09964 |   7.8926   |
| k-d_tree_pandas      |     0.496135 |        4.09075 |   8.27034  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.771742 |        87.5706 |    2.92104 |
| k-d_tree_sklearn     |     0.60943  |       270.62   |    3.28847 |
| Bori_Aron_solution-1 |     0.497167 |       162.832  |   23.205   |