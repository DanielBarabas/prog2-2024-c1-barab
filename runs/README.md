# 2025-06-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.539572 |       0.407637 |   0.420846 |
| barab-szabi-2        |     0.538772 |       0.418576 |   0.423696 |
| barab-szabi-1        |     0.544601 |       0.416114 |   0.448804 |
| solution-1           |     7.22618  |       1e-06    |   0.5177   |
| Bori_Aron_solution-1 |     0.533191 |       0.55128  |   0.55437  |
| k-d_tree_pandas      |     8.98068  |       0.434506 |   0.633391 |
| k-d_tree_sklearn     |     2.93941  |       1.11882  |   1.10893  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.559716 |       0.411237 |   0.426162 |
| barab-szabi-2        |     0.561622 |       0.422124 |   0.434865 |
| k-d_tree_polars      |     0.571218 |       0.420717 |   0.439048 |
| Bori_Aron_solution-1 |     0.545284 |       0.552765 |   0.548558 |
| k-d_tree_pandas      |     0.552469 |       0.38942  |   0.564722 |
| k-d_tree_sklearn     |     0.567798 |       0.991459 |   1.07825  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557819 |       0.43014  |   0.434335 |
| k-d_tree_polars      |     0.552038 |       0.435105 |   0.458558 |
| barab-szabi-1        |     0.576242 |       0.439561 |   0.470671 |
| Bori_Aron_solution-1 |     0.554363 |       0.591618 |   0.55934  |
| k-d_tree_pandas      |     0.57102  |       0.416539 |   0.612232 |
| k-d_tree_sklearn     |     0.556349 |       1.04141  |   1.08864  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548931 |       0.503749 |   0.466484 |
| k-d_tree_polars      |     0.557441 |       0.552375 |   0.558365 |
| Bori_Aron_solution-1 |     0.545242 |       0.777228 |   0.560111 |
| barab-szabi-1        |     0.551778 |       0.549278 |   0.561813 |
| k-d_tree_pandas      |     0.557024 |       0.484701 |   0.73647  |
| k-d_tree_sklearn     |     0.557645 |       1.25382  |   1.14076  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554168 |       0.742546 |   0.500692 |
| Bori_Aron_solution-1 |     0.545204 |       1.40116  |   0.590282 |
| k-d_tree_polars      |     0.553382 |       0.903424 |   0.902961 |
| barab-szabi-1        |     0.554444 |       0.883022 |   0.948747 |
| k-d_tree_pandas      |     0.549967 |       0.763457 |   1.1839   |
| k-d_tree_sklearn     |     0.554487 |       2.07643  |   1.22596  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551929 |        5.3555  |   0.764933 |
| Bori_Aron_solution-1 |     0.547949 |       10.8516  |   0.866218 |
| k-d_tree_sklearn     |     0.558122 |       16.3142  |   1.31815  |
| k-d_tree_polars      |     0.551764 |        4.95508 |   6.60297  |
| barab-szabi-1        |     0.556886 |        4.99597 |   6.61346  |
| k-d_tree_pandas      |     0.55407  |        3.88666 |   6.99171  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.750756 |        75.7835 |    2.95563 |
| k-d_tree_sklearn     |     0.608836 |       239.933  |    4.05099 |
| Bori_Aron_solution-1 |     0.546539 |       143.14   |   17.7537  |