# 2026-09-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.478553 |       0.426907 |   0.470615 |
| barab-szabi-2        |     0.492141 |       0.475706 |   0.473366 |
| solution-1           |     7.90332  |       1e-06    |   0.49205  |
| Bori_Aron_solution-1 |     0.47573  |       0.567858 |   0.562395 |
| k-d_tree_pandas      |     0.481846 |       0.399759 |   0.572503 |
| barab-szabi-1        |     9.52295  |       0.496058 |   0.664718 |
| k-d_tree_sklearn     |     3.18834  |       1.22957  |   1.12615  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488667 |       0.462399 |   0.459778 |
| k-d_tree_polars      |     0.511096 |       0.457183 |   0.477166 |
| barab-szabi-1        |     0.498517 |       0.44257  |   0.480691 |
| k-d_tree_pandas      |     0.500952 |       0.414704 |   0.601099 |
| Bori_Aron_solution-1 |     0.499611 |       0.586368 |   0.634163 |
| k-d_tree_sklearn     |     0.49636  |       1.0661   |   1.09631  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.497306 |       0.476499 |   0.496671 |
| barab-szabi-2        |     0.490929 |       0.50091  |   0.496853 |
| k-d_tree_polars      |     0.485155 |       0.476882 |   0.504226 |
| Bori_Aron_solution-1 |     0.492324 |       0.612239 |   0.565387 |
| k-d_tree_pandas      |     0.49408  |       0.428132 |   0.625266 |
| k-d_tree_sklearn     |     0.496973 |       1.09177  |   1.17133  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.506358 |       0.541042 |   0.516326 |
| Bori_Aron_solution-1 |     0.482477 |       0.804092 |   0.583476 |
| k-d_tree_polars      |     0.508978 |       0.577395 |   0.588791 |
| barab-szabi-1        |     0.495945 |       0.630353 |   0.595632 |
| k-d_tree_pandas      |     0.491001 |       0.525077 |   0.745488 |
| k-d_tree_sklearn     |     0.494963 |       1.34292  |   1.23518  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480615 |       0.76514  |   0.533185 |
| Bori_Aron_solution-1 |     0.492261 |       1.48208  |   0.619324 |
| k-d_tree_polars      |     0.494331 |       0.946057 |   0.954116 |
| barab-szabi-1        |     0.512957 |       0.951622 |   1.03636  |
| k-d_tree_pandas      |     0.509841 |       0.825112 |   1.22428  |
| k-d_tree_sklearn     |     0.496256 |       2.17161  |   1.26619  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479012 |        5.45634 |   0.770189 |
| Bori_Aron_solution-1 |     0.469558 |       11.2697  |   0.826704 |
| k-d_tree_sklearn     |     0.495991 |       17.3388  |   1.34709  |
| barab-szabi-1        |     0.479872 |        5.46937 |   6.99987  |
| k-d_tree_polars      |     0.484548 |        5.39053 |   7.13724  |
| k-d_tree_pandas      |     0.488663 |        4.35085 |   7.35497  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.592832 |        73.3624 |    2.87141 |
| k-d_tree_sklearn     |     0.718088 |       242.582  |    4.08423 |
| Bori_Aron_solution-1 |     0.481725 |       154.852  |   25.5996  |