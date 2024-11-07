# 2024-11-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.86252  |       1e-06    |   0.400297 |
| k-d_tree_polars      |     0.628467 |       0.406161 |   0.402866 |
| barab-szabi-2        |     0.636471 |       0.419875 |   0.414429 |
| barab-szabi-1        |     0.659069 |       0.43742  |   0.421948 |
| Bori_Aron_solution-1 |     0.648243 |       0.543411 |   0.570281 |
| k-d_tree_pandas      |     0.663924 |       0.435184 |   0.571876 |
| k-d_tree_sklearn     |    11.1759   |       1.08026  |   0.998871 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.654108 |       0.414631 |   0.396469 |
| k-d_tree_polars      |     0.642007 |       0.422355 |   0.428652 |
| barab-szabi-1        |     0.636542 |       0.454823 |   0.430958 |
| k-d_tree_pandas      |     0.643744 |       0.408535 |   0.571076 |
| Bori_Aron_solution-1 |     0.627884 |       0.562836 |   0.572287 |
| k-d_tree_sklearn     |     0.65491  |       0.999908 |   1.09643  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.651039 |       0.427413 |   0.42449  |
| barab-szabi-1        |     0.650552 |       0.439238 |   0.429778 |
| k-d_tree_polars      |     0.637449 |       0.451143 |   0.446043 |
| Bori_Aron_solution-1 |     0.616851 |       0.571932 |   0.541965 |
| k-d_tree_pandas      |     0.619893 |       0.423548 |   0.618638 |
| k-d_tree_sklearn     |     0.644317 |       0.988586 |   1.0575   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631939 |       0.482379 |   0.45702  |
| k-d_tree_polars      |     0.621425 |       0.557357 |   0.522052 |
| barab-szabi-1        |     0.637166 |       0.551372 |   0.539615 |
| Bori_Aron_solution-1 |     0.640236 |       0.776485 |   0.577243 |
| k-d_tree_pandas      |     0.636975 |       0.504506 |   0.720073 |
| k-d_tree_sklearn     |     0.628757 |       1.20749  |   1.06487  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.643785 |       0.779608 |   0.503183 |
| Bori_Aron_solution-1 |     0.622162 |       1.43551  |   0.588547 |
| k-d_tree_polars      |     0.643    |       0.883009 |   0.884845 |
| barab-szabi-1        |     0.640888 |       0.875018 |   0.916146 |
| k-d_tree_pandas      |     0.635944 |       0.769755 |   1.19043  |
| k-d_tree_sklearn     |     0.630391 |       2.08771  |   1.20863  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.656121 |        5.57202 |   0.737151 |
| Bori_Aron_solution-1 |     0.61881  |       10.9276  |   0.814165 |
| k-d_tree_sklearn     |     0.635578 |       17.0372  |   1.27294  |
| barab-szabi-1        |     0.624065 |        4.87496 |   6.75959  |
| k-d_tree_polars      |     0.636928 |        4.87835 |   7.07783  |
| k-d_tree_pandas      |     0.621799 |        3.88967 |   7.18591  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.660277 |        77.6937 |    3.14892 |
| k-d_tree_sklearn     |     0.626371 |       233.617  |    4.30597 |
| Bori_Aron_solution-1 |     0.646364 |       152.87   |   18.8484  |