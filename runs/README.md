# 2026-03-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.30721  |       1e-06    |   0.408599 |
| barab-szabi-2        |     0.501011 |       0.458287 |   0.456956 |
| k-d_tree_polars      |     0.505969 |       0.434182 |   0.472765 |
| barab-szabi-1        |     9.05705  |       0.448284 |   0.526951 |
| Bori_Aron_solution-1 |     0.498926 |       0.58842  |   0.582253 |
| k-d_tree_pandas      |     0.509783 |       0.412559 |   0.589981 |
| k-d_tree_sklearn     |     3.30472  |       1.16109  |   1.1414   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.523109 |       0.440672 |   0.463588 |
| barab-szabi-2        |     0.516834 |       0.455594 |   0.467967 |
| k-d_tree_polars      |     0.515554 |       0.436675 |   0.472615 |
| Bori_Aron_solution-1 |     0.52555  |       0.591284 |   0.5739   |
| k-d_tree_pandas      |     0.524853 |       0.412762 |   0.5871   |
| k-d_tree_sklearn     |     0.51732  |       1.07264  |   1.16224  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519068 |       0.482342 |   0.482237 |
| barab-szabi-1        |     0.520553 |       0.462437 |   0.491697 |
| k-d_tree_polars      |     0.523449 |       0.465675 |   0.497053 |
| Bori_Aron_solution-1 |     0.507206 |       0.636415 |   0.588823 |
| k-d_tree_pandas      |     0.520766 |       0.456158 |   0.645178 |
| k-d_tree_sklearn     |     0.52529  |       1.125    |   1.18001  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51432  |       0.530305 |   0.502189 |
| k-d_tree_polars      |     0.516494 |       0.590396 |   0.585801 |
| Bori_Aron_solution-1 |     0.514796 |       0.819667 |   0.591822 |
| barab-szabi-1        |     0.522713 |       0.59971  |   0.597918 |
| k-d_tree_pandas      |     0.516949 |       0.527432 |   0.774628 |
| k-d_tree_sklearn     |     0.529666 |       1.34556  |   1.2186   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.507385 |       1.5491   |   0.608527 |
| barab-szabi-2        |     0.511014 |       0.777056 |   0.614493 |
| k-d_tree_polars      |     0.509762 |       0.951884 |   0.961848 |
| barab-szabi-1        |     0.516603 |       0.979414 |   0.995738 |
| k-d_tree_pandas      |     0.520885 |       0.857222 |   1.2425   |
| k-d_tree_sklearn     |     0.516817 |       2.28018  |   1.3177   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51614  |        5.28537 |   0.763558 |
| Bori_Aron_solution-1 |     0.518274 |       11.4586  |   0.84514  |
| k-d_tree_sklearn     |     0.546825 |       18.0017  |   1.43654  |
| barab-szabi-1        |     0.514392 |        5.80451 |   6.78997  |
| k-d_tree_polars      |     0.522658 |        5.60086 |   6.94006  |
| k-d_tree_pandas      |     0.526975 |        4.63537 |   7.41711  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53056  |        71.4065 |    2.60051 |
| k-d_tree_sklearn     |     0.915649 |       244.784  |    3.85669 |
| Bori_Aron_solution-1 |     0.49861  |       149.333  |   22.0516  |