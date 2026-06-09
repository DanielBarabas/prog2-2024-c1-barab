# 2026-06-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     9.17644  |       0.425478 |   0.34205  |
| barab-szabi-1        |     0.355671 |       0.31644  |   0.346381 |
| solution-1           |     6.27639  |       1e-06    |   0.348991 |
| k-d_tree_polars      |     0.357987 |       0.319699 |   0.350376 |
| Bori_Aron_solution-1 |     0.355333 |       0.428804 |   0.427318 |
| k-d_tree_pandas      |     0.361147 |       0.30336  |   0.434368 |
| k-d_tree_sklearn     |     2.31919  |       0.883005 |   0.853747 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.367982 |       0.348357 |   0.344121 |
| k-d_tree_polars      |     0.363749 |       0.330299 |   0.353831 |
| barab-szabi-1        |     0.362811 |       0.330585 |   0.362731 |
| Bori_Aron_solution-1 |     0.359217 |       0.435219 |   0.432045 |
| k-d_tree_pandas      |     0.364732 |       0.325683 |   0.439316 |
| k-d_tree_sklearn     |     0.365914 |       0.776188 |   0.85236  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364879 |       0.449135 |   0.361801 |
| k-d_tree_polars      |     0.370275 |       0.347741 |   0.368539 |
| barab-szabi-1        |     0.363809 |       0.347195 |   0.371972 |
| Bori_Aron_solution-1 |     0.361024 |       0.475236 |   0.448246 |
| k-d_tree_pandas      |     0.363247 |       0.327329 |   0.466369 |
| k-d_tree_sklearn     |     0.365968 |       0.819406 |   0.856611 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.363619 |       0.411069 |   0.379654 |
| Bori_Aron_solution-1 |     0.360358 |       0.626658 |   0.444021 |
| k-d_tree_polars      |     0.364669 |       0.441327 |   0.448991 |
| barab-szabi-1        |     0.362304 |       0.441723 |   0.455621 |
| k-d_tree_pandas      |     0.364624 |       0.397243 |   0.570464 |
| k-d_tree_sklearn     |     0.36558  |       1.00111  |   0.885047 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.36463  |       0.610958 |   0.417542 |
| Bori_Aron_solution-1 |     0.363192 |       1.18334  |   0.466554 |
| k-d_tree_polars      |     0.361964 |       0.771055 |   0.757401 |
| barab-szabi-1        |     0.36107  |       0.726741 |   0.785294 |
| k-d_tree_sklearn     |     0.366246 |       1.76398  |   0.923578 |
| k-d_tree_pandas      |     0.36182  |       0.62407  |   0.931495 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364341 |        4.34299 |   0.628198 |
| Bori_Aron_solution-1 |     0.35729  |        8.94843 |   0.645557 |
| k-d_tree_sklearn     |     0.364583 |       14.2999  |   0.998738 |
| k-d_tree_polars      |     0.365219 |        4.60669 |   5.80227  |
| barab-szabi-1        |     0.366226 |        4.85562 |   5.83851  |
| k-d_tree_pandas      |     0.364795 |        3.24703 |   6.07277  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.359361 |        69.3948 |    2.34472 |
| k-d_tree_sklearn     |     1.03632  |       220.643  |    3.03004 |
| Bori_Aron_solution-1 |     0.36332  |       144.54   |   23.3517  |