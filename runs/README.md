# 2026-06-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.35632  |       1e-06    |   0.336644 |
| barab-szabi-2        |     7.40517  |       0.830195 |   0.346334 |
| barab-szabi-1        |     0.361722 |       0.32289  |   0.382442 |
| k-d_tree_polars      |     0.369863 |       0.33682  |   0.413904 |
| Bori_Aron_solution-1 |     0.369081 |       0.449657 |   0.447841 |
| k-d_tree_pandas      |     0.37158  |       0.315646 |   0.459273 |
| k-d_tree_sklearn     |     2.45093  |       1.15764  |   0.865938 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.378078 |       0.359548 |   0.356678 |
| barab-szabi-1        |     0.369054 |       0.34401  |   0.362423 |
| k-d_tree_polars      |     0.376364 |       0.39932  |   0.395813 |
| k-d_tree_pandas      |     0.373142 |       0.312149 |   0.434041 |
| Bori_Aron_solution-1 |     0.363664 |       0.449718 |   0.450022 |
| k-d_tree_sklearn     |     0.374593 |       0.79708  |   0.872177 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.36318  |       0.358628 |   0.363658 |
| barab-szabi-1        |     0.367934 |       0.350164 |   0.373753 |
| k-d_tree_polars      |     0.363761 |       0.351402 |   0.379051 |
| Bori_Aron_solution-1 |     0.361438 |       0.48681  |   0.465564 |
| k-d_tree_pandas      |     0.360338 |       0.320767 |   0.467616 |
| k-d_tree_sklearn     |     0.37191  |       0.838449 |   0.871691 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.36305  |       0.415284 |   0.387445 |
| k-d_tree_polars      |     0.383286 |       0.445737 |   0.44717  |
| Bori_Aron_solution-1 |     0.36388  |       0.623988 |   0.458562 |
| barab-szabi-1        |     0.374303 |       0.445736 |   0.467453 |
| k-d_tree_pandas      |     0.365428 |       0.40992  |   0.581291 |
| k-d_tree_sklearn     |     0.37326  |       0.994467 |   0.900309 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.371348 |       0.60939  |   0.418016 |
| Bori_Aron_solution-1 |     0.360299 |       1.1933   |   0.467388 |
| k-d_tree_polars      |     0.370783 |       0.718217 |   0.765955 |
| barab-szabi-1        |     0.367288 |       0.716855 |   0.785387 |
| k-d_tree_pandas      |     0.378395 |       0.626632 |   0.959809 |
| k-d_tree_sklearn     |     0.371312 |       1.76135  |   0.983495 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364056 |        4.62663 |   0.624713 |
| Bori_Aron_solution-1 |     0.360032 |        9.29187 |   0.657982 |
| k-d_tree_sklearn     |     0.361641 |       15.3587  |   0.992059 |
| barab-szabi-1        |     0.367392 |        4.84487 |   6.08451  |
| k-d_tree_polars      |     0.366075 |        4.78827 |   6.09519  |
| k-d_tree_pandas      |     0.359662 |        3.26099 |   6.41519  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364224 |        69.4995 |    2.4029  |
| k-d_tree_sklearn     |     1.04152  |       219.121  |    3.03589 |
| Bori_Aron_solution-1 |     0.450496 |       136.956  |   23.2613  |