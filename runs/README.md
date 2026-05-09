# 2026-05-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.613139 |       0.394986 |   0.420788 |
| barab-szabi-2        |     0.456653 |       0.424555 |   0.421175 |
| barab-szabi-1        |     0.457596 |       0.412184 |   0.425125 |
| solution-1           |     7.83242  |       1e-06    |   0.438598 |
| Bori_Aron_solution-1 |     0.936544 |       0.539136 |   0.541669 |
| k-d_tree_pandas      |     0.452732 |       0.38841  |   0.648797 |
| k-d_tree_sklearn     |    11.318    |       1.21334  |   1.03992  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.453635 |       0.419684 |   0.420542 |
| barab-szabi-1        |     0.465535 |       0.465588 |   0.424933 |
| k-d_tree_polars      |     0.451796 |       0.407138 |   0.425721 |
| k-d_tree_pandas      |     0.457377 |       0.385645 |   0.540805 |
| Bori_Aron_solution-1 |     0.448432 |       0.547684 |   0.545712 |
| k-d_tree_sklearn     |     0.462092 |       0.972959 |   1.06652  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452147 |       0.44622  |   0.435841 |
| k-d_tree_polars      |     0.454273 |       0.431698 |   0.446871 |
| barab-szabi-1        |     0.476943 |       0.436688 |   0.449594 |
| Bori_Aron_solution-1 |     0.445707 |       0.580965 |   0.545042 |
| k-d_tree_pandas      |     0.458772 |       0.404619 |   0.584215 |
| k-d_tree_sklearn     |     0.455026 |       0.996838 |   1.05474  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.449253 |       0.497905 |   0.460983 |
| Bori_Aron_solution-1 |     0.449228 |       0.771663 |   0.543806 |
| k-d_tree_polars      |     0.451137 |       0.551751 |   0.552387 |
| barab-szabi-1        |     0.451204 |       0.54903  |   0.564803 |
| k-d_tree_pandas      |     0.453104 |       0.489249 |   0.712866 |
| k-d_tree_sklearn     |     0.456881 |       1.23322  |   1.09194  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.45196  |       0.736771 |   0.49835  |
| Bori_Aron_solution-1 |     0.442662 |       1.45343  |   0.568154 |
| k-d_tree_polars      |     0.469135 |       0.903625 |   0.934513 |
| barab-szabi-1        |     0.455543 |       0.900541 |   0.973618 |
| k-d_tree_sklearn     |     0.457433 |       2.11487  |   1.12951  |
| k-d_tree_pandas      |     0.454482 |       0.778623 |   1.15503  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.451465 |        5.26421 |   0.694797 |
| Bori_Aron_solution-1 |     0.453109 |       11.1141  |   0.786865 |
| k-d_tree_sklearn     |     0.459332 |       16.4814  |   1.21687  |
| k-d_tree_polars      |     0.45471  |        5.25821 |   7.14925  |
| barab-szabi-1        |     0.448748 |        5.30329 |   7.25616  |
| k-d_tree_pandas      |     0.453346 |        4.21759 |   7.50418  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.651236 |        76.5398 |    2.40913 |
| k-d_tree_sklearn     |     0.461807 |       258.821  |    3.24824 |
| Bori_Aron_solution-1 |     0.457101 |       152.635  |   22.7853  |