# 2025-03-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.600669 |       0.40356  |   0.415486 |
| barab-szabi-2        |     0.578093 |       0.415832 |   0.418477 |
| solution-1           |     7.44584  |       1e-06    |   0.421611 |
| barab-szabi-1        |     0.571302 |       0.414829 |   0.487383 |
| Bori_Aron_solution-1 |     0.56994  |       0.542476 |   0.54485  |
| k-d_tree_pandas      |     7.83377  |       0.40871  |   0.597717 |
| k-d_tree_sklearn     |     2.93882  |       1.52299  |   1.02893  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60007  |       0.408741 |   0.403005 |
| k-d_tree_polars      |     0.593672 |       0.425401 |   0.414552 |
| barab-szabi-1        |     0.596649 |       0.414101 |   0.419813 |
| Bori_Aron_solution-1 |     0.602143 |       0.553507 |   0.539095 |
| k-d_tree_pandas      |     0.587457 |       0.385288 |   0.552371 |
| k-d_tree_sklearn     |     0.591359 |       0.956759 |   1.04579  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.59387  |       0.424101 |   0.421282 |
| barab-szabi-1        |     0.595489 |       0.440491 |   0.445169 |
| k-d_tree_polars      |     0.587718 |       0.436794 |   0.482436 |
| Bori_Aron_solution-1 |     0.586822 |       0.592273 |   0.558874 |
| k-d_tree_pandas      |     0.591679 |       0.409223 |   0.598422 |
| k-d_tree_sklearn     |     0.590882 |       0.999659 |   1.06543  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604214 |       0.484535 |   0.452669 |
| k-d_tree_polars      |     0.609959 |       0.551198 |   0.543624 |
| barab-szabi-1        |     0.608402 |       0.548931 |   0.559644 |
| Bori_Aron_solution-1 |     0.58587  |       0.758075 |   0.560356 |
| k-d_tree_pandas      |     0.58448  |       0.480593 |   0.737858 |
| k-d_tree_sklearn     |     0.591237 |       1.2269   |   1.12795  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590763 |       0.736327 |   0.482859 |
| Bori_Aron_solution-1 |     0.583487 |       1.3949   |   0.585629 |
| k-d_tree_polars      |     0.592907 |       0.877014 |   0.88922  |
| barab-szabi-1        |     0.595737 |       0.862678 |   0.927148 |
| k-d_tree_pandas      |     0.592199 |       0.7474   |   1.17501  |
| k-d_tree_sklearn     |     0.589913 |       2.05827  |   1.21792  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587997 |        5.52842 |   0.78054  |
| Bori_Aron_solution-1 |     0.587978 |       10.7452  |   0.887175 |
| k-d_tree_sklearn     |     0.592086 |       16.6412  |   1.35021  |
| k-d_tree_polars      |     0.592429 |        4.95173 |   6.76076  |
| barab-szabi-1        |     0.586349 |        4.94128 |   6.77014  |
| k-d_tree_pandas      |     0.592465 |        3.83598 |   7.20204  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.712465 |        77.3982 |    3.39939 |
| k-d_tree_sklearn     |     0.6469   |       239.155  |    4.30658 |
| Bori_Aron_solution-1 |     0.588988 |       160.002  |   13.6755  |