# 2024-10-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.54705  |       1e-06    |   0.349224 |
| barab-szabi-2        |     0.618255 |       0.384525 |   0.377885 |
| barab-szabi-1        |     0.609118 |       0.397902 |   0.382283 |
| k-d_tree_polars      |     0.619807 |       0.40292  |   0.382662 |
| Bori_Aron_solution-1 |     0.603802 |       0.519011 |   0.51508  |
| k-d_tree_pandas      |     0.61479  |       0.374487 |   0.517733 |
| k-d_tree_sklearn     |    10.1486   |       1.09618  |   0.9406   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612956 |       0.382773 |   0.38116  |
| k-d_tree_polars      |     0.617459 |       0.401951 |   0.384693 |
| barab-szabi-1        |     0.649826 |       0.403203 |   0.388077 |
| Bori_Aron_solution-1 |     0.602345 |       0.52336  |   0.516812 |
| k-d_tree_pandas      |     0.611955 |       0.383303 |   0.52873  |
| k-d_tree_sklearn     |     0.637696 |       0.886365 |   0.948254 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616564 |       0.398799 |   0.391635 |
| barab-szabi-1        |     0.611444 |       0.425492 |   0.419121 |
| k-d_tree_polars      |     0.609617 |       0.426666 |   0.419601 |
| Bori_Aron_solution-1 |     0.60618  |       0.561561 |   0.516268 |
| k-d_tree_pandas      |     0.613541 |       0.40188  |   0.602731 |
| k-d_tree_sklearn     |     0.611181 |       0.92097  |   0.967854 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61287  |       0.464446 |   0.421396 |
| k-d_tree_polars      |     0.613228 |       0.535907 |   0.524755 |
| barab-szabi-1        |     0.608541 |       0.535968 |   0.528583 |
| Bori_Aron_solution-1 |     0.601607 |       0.744494 |   0.5292   |
| k-d_tree_pandas      |     0.613013 |       0.477393 |   0.705467 |
| k-d_tree_sklearn     |     0.620248 |       1.15482  |   1.05048  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607166 |       0.710057 |   0.452753 |
| Bori_Aron_solution-1 |     0.601079 |       1.3697   |   0.558854 |
| k-d_tree_polars      |     0.613297 |       0.849193 |   0.866881 |
| barab-szabi-1        |     0.609377 |       0.849827 |   0.898217 |
| k-d_tree_sklearn     |     0.607612 |       1.97264  |   1.11564  |
| k-d_tree_pandas      |     0.60833  |       0.744065 |   1.13065  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610052 |        5.14536 |   0.707308 |
| Bori_Aron_solution-1 |     0.610478 |       10.6285  |   0.802063 |
| k-d_tree_sklearn     |     0.613282 |       15.6054  |   1.22583  |
| k-d_tree_polars      |     0.619234 |        4.84994 |   6.45654  |
| barab-szabi-1        |     0.605691 |        4.83946 |   6.4763   |
| k-d_tree_pandas      |     0.603155 |        3.90455 |   6.85496  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627525 |        71.8604 |    2.85407 |
| k-d_tree_sklearn     |     0.614284 |       225.075  |    4.12506 |
| Bori_Aron_solution-1 |     0.629554 |       145.757  |   17.9663  |