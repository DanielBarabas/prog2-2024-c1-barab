# 2026-03-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.963708 |       0.447062 |   0.446219 |
| k-d_tree_polars      |     0.965139 |       0.419455 |   0.461554 |
| solution-1           |     9.10895  |       1e-06    |   0.509246 |
| Bori_Aron_solution-1 |     0.964844 |       0.571454 |   0.571457 |
| k-d_tree_pandas      |     0.964467 |       0.406958 |   0.587581 |
| barab-szabi-1        |     9.98038  |       0.573007 |   0.88798  |
| k-d_tree_sklearn     |     3.81293  |       1.73589  |   1.22349  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.969531 |       0.460007 |   0.447135 |
| barab-szabi-1        |     0.996836 |       0.445163 |   0.453959 |
| k-d_tree_polars      |     0.994507 |       0.435503 |   0.464888 |
| Bori_Aron_solution-1 |     0.965662 |       0.626127 |   0.599113 |
| k-d_tree_pandas      |     0.988471 |       0.454186 |   0.609939 |
| k-d_tree_sklearn     |     0.52353  |       1.05644  |   1.16492  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.50541  |       0.469275 |   0.494131 |
| barab-szabi-1        |     0.528883 |       0.481286 |   0.504799 |
| k-d_tree_polars      |     0.522633 |       0.498276 |   0.513271 |
| Bori_Aron_solution-1 |     0.559647 |       0.668103 |   0.608579 |
| k-d_tree_pandas      |     0.517083 |       0.434208 |   0.638025 |
| k-d_tree_sklearn     |     0.526999 |       1.09406  |   1.19373  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529915 |       0.522225 |   0.504772 |
| k-d_tree_polars      |     0.529981 |       0.58058  |   0.576021 |
| barab-szabi-1        |     0.51517  |       0.586231 |   0.612495 |
| Bori_Aron_solution-1 |     0.50048  |       0.813234 |   0.617884 |
| k-d_tree_pandas      |     0.507707 |       0.514486 |   0.758671 |
| k-d_tree_sklearn     |     0.517971 |       1.322    |   1.21068  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.515548 |       0.784674 |   0.557652 |
| Bori_Aron_solution-1 |     0.512304 |       1.52891  |   0.619351 |
| k-d_tree_polars      |     0.525996 |       0.95532  |   0.979228 |
| barab-szabi-1        |     0.525234 |       0.95293  |   1.01798  |
| k-d_tree_pandas      |     0.538747 |       0.860597 |   1.28169  |
| k-d_tree_sklearn     |     0.527734 |       2.38261  |   1.3643   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531839 |        5.64678 |   0.805241 |
| Bori_Aron_solution-1 |     0.547317 |       11.6605  |   0.859416 |
| k-d_tree_sklearn     |     0.522801 |       17.822   |   1.34319  |
| k-d_tree_polars      |     0.515679 |        5.50823 |   6.94241  |
| barab-szabi-1        |     0.534613 |        5.72923 |   7.20127  |
| k-d_tree_pandas      |     0.50796  |        4.46074 |   7.42123  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.513532 |        75.2679 |    2.66059 |
| k-d_tree_sklearn     |     0.789369 |       252.4    |    4.09571 |
| Bori_Aron_solution-1 |     0.512877 |       152.81   |   14.7971  |