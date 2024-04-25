# 2024-04-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |    12.0958   |       1e-06    |   0.372514 |
| barab-szabi-2        |     0.732911 |       0.360394 |   0.372574 |
| k-d_tree_polars      |     0.725351 |       0.439836 |   0.372904 |
| barab-szabi-1        |     9.65693  |       0.446597 |   0.373702 |
| Bori_Aron_solution-1 |     0.721589 |       0.505614 |   0.50558  |
| k-d_tree_pandas      |     0.729115 |       0.404022 |   0.506028 |
| k-d_tree_sklearn     |     3.46003  |       0.927484 |   0.693657 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.759554 |       0.354047 |   0.357758 |
| barab-szabi-1        |     0.754273 |       0.429746 |   0.358144 |
| k-d_tree_polars      |     0.760983 |       0.425923 |   0.359321 |
| Bori_Aron_solution-1 |     0.744305 |       0.508167 |   0.509396 |
| k-d_tree_pandas      |     0.750195 |       0.415278 |   0.512928 |
| k-d_tree_sklearn     |     0.775444 |       0.897522 |   0.706406 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.753605 |       0.369071 |   0.364948 |
| barab-szabi-1        |     0.758989 |       0.454622 |   0.389605 |
| k-d_tree_polars      |     0.754398 |       0.451696 |   0.38979  |
| Bori_Aron_solution-1 |     0.746102 |       0.54329  |   0.512097 |
| k-d_tree_pandas      |     0.766504 |       0.423828 |   0.548367 |
| k-d_tree_sklearn     |     0.760849 |       0.923312 |   0.724337 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.756471 |       0.439267 |   0.400721 |
| k-d_tree_polars      |     0.769835 |       0.557631 |   0.488499 |
| barab-szabi-1        |     0.758085 |       0.560622 |   0.493587 |
| Bori_Aron_solution-1 |     0.746416 |       0.713438 |   0.51634  |
| k-d_tree_pandas      |     0.752192 |       0.504122 |   0.688607 |
| k-d_tree_sklearn     |     0.765905 |       1.15948  |   0.796878 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.762787 |       0.693085 |   0.434153 |
| Bori_Aron_solution-1 |     0.746163 |       1.38755  |   0.543766 |
| k-d_tree_polars      |     0.758412 |       0.879056 |   0.849432 |
| k-d_tree_sklearn     |     0.775485 |       2.01157  |   0.880144 |
| barab-szabi-1        |     0.75468  |       0.874399 |   0.896002 |
| k-d_tree_pandas      |     0.75723  |       0.776361 |   1.11457  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.745998 |        5.47926 |   0.77327  |
| Bori_Aron_solution-1 |     0.743248 |       10.9369  |   0.792426 |
| k-d_tree_sklearn     |     0.758499 |       16.8373  |   1.09387  |
| k-d_tree_polars      |     0.751026 |        4.9179  |   6.7656   |
| barab-szabi-1        |     0.76304  |        4.88795 |   6.82159  |
| k-d_tree_pandas      |     0.749358 |        3.91874 |   7.15982  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.937364 |        74.6672 |    3.77375 |
| k-d_tree_sklearn     |     0.814085 |       235.384  |    4.81134 |
| Bori_Aron_solution-1 |     0.75     |       146.914  |   17.0406  |