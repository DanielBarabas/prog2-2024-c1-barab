# 2025-11-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.522916 |       0.393995 |   0.417544 |
| barab-szabi-2        |     0.509634 |       0.58805  |   0.421023 |
| k-d_tree_polars      |     0.51901  |       0.399765 |   0.421081 |
| solution-1           |     8.15414  |       1e-06    |   0.500631 |
| Bori_Aron_solution-1 |     0.514887 |       0.5344   |   0.530256 |
| k-d_tree_pandas      |     8.43611  |       0.407895 |   0.728819 |
| k-d_tree_sklearn     |     3.05412  |       1.13604  |   1.05091  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.517813 |       0.421662 |   0.424651 |
| barab-szabi-1        |     0.518594 |       0.40201  |   0.426579 |
| k-d_tree_polars      |     0.51458  |       0.406763 |   0.429384 |
| Bori_Aron_solution-1 |     0.510368 |       0.542401 |   0.534322 |
| k-d_tree_pandas      |     0.516765 |       0.38134  |   0.545718 |
| k-d_tree_sklearn     |     0.520239 |       0.948793 |   1.03743  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522629 |       0.431875 |   0.435024 |
| k-d_tree_polars      |     0.522026 |       0.43213  |   0.45291  |
| barab-szabi-1        |     0.518097 |       0.430126 |   0.455893 |
| Bori_Aron_solution-1 |     0.513941 |       0.585656 |   0.538959 |
| k-d_tree_pandas      |     0.517756 |       0.405014 |   0.589015 |
| k-d_tree_sklearn     |     0.523571 |       0.998397 |   1.06909  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521071 |       0.494296 |   0.501622 |
| Bori_Aron_solution-1 |     0.515379 |       0.766975 |   0.549548 |
| k-d_tree_polars      |     0.52259  |       0.549113 |   0.552621 |
| barab-szabi-1        |     0.521827 |       0.551791 |   0.560853 |
| k-d_tree_pandas      |     0.524574 |       0.495113 |   0.730402 |
| k-d_tree_sklearn     |     0.519636 |       1.23428  |   1.11121  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522012 |       0.734885 |   0.497999 |
| Bori_Aron_solution-1 |     0.516199 |       1.43022  |   0.577674 |
| k-d_tree_polars      |     0.519477 |       0.919377 |   0.895696 |
| barab-szabi-1        |     0.52427  |       0.918653 |   0.937869 |
| k-d_tree_pandas      |     0.517568 |       0.806264 |   1.16114  |
| k-d_tree_sklearn     |     0.521249 |       2.08825  |   1.19331  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519365 |        5.14911 |   0.744788 |
| Bori_Aron_solution-1 |     0.51147  |       11.1294  |   0.835546 |
| k-d_tree_sklearn     |     0.52722  |       16.485   |   1.29112  |
| barab-szabi-1        |     0.520312 |        5.44861 |   6.50431  |
| k-d_tree_polars      |     0.523189 |        5.37979 |   6.53393  |
| k-d_tree_pandas      |     0.518593 |        4.41157 |   6.90089  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527373 |        72.5719 |    2.7542  |
| k-d_tree_sklearn     |     0.530641 |       235.723  |    4.08121 |
| Bori_Aron_solution-1 |     0.707374 |       154.235  |   17.573   |