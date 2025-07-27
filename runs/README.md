# 2025-07-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.537187 |       0.412176 |   0.421779 |
| barab-szabi-2        |     8.26528  |       0.59775  |   0.423626 |
| solution-1           |     7.66854  |       1e-06    |   0.428486 |
| k-d_tree_polars      |     0.561307 |       0.40782  |   0.429259 |
| Bori_Aron_solution-1 |     0.539904 |       0.544655 |   0.543558 |
| k-d_tree_pandas      |     0.557349 |       0.385749 |   0.553217 |
| k-d_tree_sklearn     |     3.16393  |       1.08278  |   1.05807  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550839 |       0.424788 |   0.425059 |
| k-d_tree_polars      |     0.569438 |       0.413621 |   0.42862  |
| barab-szabi-1        |     0.557508 |       0.410698 |   0.429261 |
| Bori_Aron_solution-1 |     0.553349 |       0.558624 |   0.548881 |
| k-d_tree_pandas      |     0.559681 |       0.390713 |   0.556986 |
| k-d_tree_sklearn     |     0.56328  |       0.981586 |   1.08779  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553315 |       0.433044 |   0.438845 |
| barab-szabi-1        |     0.563245 |       0.445549 |   0.452341 |
| k-d_tree_polars      |     0.554535 |       0.44698  |   0.461388 |
| Bori_Aron_solution-1 |     0.548379 |       0.587777 |   0.546957 |
| k-d_tree_pandas      |     0.557202 |       0.410053 |   0.598522 |
| k-d_tree_sklearn     |     0.558647 |       1.01934  |   1.0705   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556383 |       0.497956 |   0.46701  |
| k-d_tree_polars      |     0.556859 |       0.549477 |   0.550135 |
| Bori_Aron_solution-1 |     0.548805 |       0.775717 |   0.557723 |
| barab-szabi-1        |     0.557137 |       0.548748 |   0.563403 |
| k-d_tree_pandas      |     0.553107 |       0.489893 |   0.741902 |
| k-d_tree_sklearn     |     0.557406 |       1.23743  |   1.13247  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554031 |       0.73919  |   0.495086 |
| Bori_Aron_solution-1 |     0.550363 |       1.40956  |   0.585375 |
| k-d_tree_polars      |     0.553803 |       0.889882 |   0.907359 |
| barab-szabi-1        |     0.554173 |       0.888344 |   0.956095 |
| k-d_tree_pandas      |     0.555856 |       0.76298  |   1.18838  |
| k-d_tree_sklearn     |     0.567872 |       2.08089  |   1.20878  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555988 |        5.37477 |   0.728238 |
| Bori_Aron_solution-1 |     0.555516 |       10.7131  |   0.843585 |
| k-d_tree_sklearn     |     0.558413 |       16.5565  |   1.31261  |
| k-d_tree_polars      |     0.556693 |        5.07008 |   6.7206   |
| barab-szabi-1        |     0.555348 |        5.03871 |   6.72207  |
| k-d_tree_pandas      |     0.562557 |        3.86707 |   7.20822  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559416 |        71.3285 |    2.65998 |
| k-d_tree_sklearn     |     0.771339 |       230.476  |    3.94188 |
| Bori_Aron_solution-1 |     0.552891 |       140.813  |   17.9825  |