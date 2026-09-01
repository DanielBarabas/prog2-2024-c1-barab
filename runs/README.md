# 2026-09-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.54836  |       0.504279 |   0.452997 |
| barab-szabi-1        |     0.454905 |       0.41132  |   0.453889 |
| k-d_tree_polars      |     0.466579 |       0.409257 |   0.456682 |
| solution-1           |     7.54945  |       1e-06    |   0.470571 |
| Bori_Aron_solution-1 |     4.37151  |       0.670358 |   0.479918 |
| k-d_tree_pandas      |     0.457609 |       0.383991 |   0.548317 |
| k-d_tree_sklearn     |     3.00601  |       1.30054  |   1.09481  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478973 |       0.462169 |   0.451127 |
| k-d_tree_polars      |     0.477296 |       0.42829  |   0.452327 |
| barab-szabi-1        |     0.468283 |       0.420286 |   0.453935 |
| k-d_tree_pandas      |     0.469897 |       0.405591 |   0.556191 |
| Bori_Aron_solution-1 |     0.466518 |       0.560287 |   0.556257 |
| k-d_tree_sklearn     |     0.476672 |       1.03209  |   1.09543  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470778 |       0.459106 |   0.464019 |
| k-d_tree_polars      |     0.47096  |       0.448344 |   0.477629 |
| barab-szabi-1        |     0.477027 |       0.451053 |   0.479433 |
| Bori_Aron_solution-1 |     0.468456 |       0.597122 |   0.552637 |
| k-d_tree_pandas      |     0.484084 |       0.418599 |   0.599517 |
| k-d_tree_sklearn     |     0.480694 |       1.09228  |   1.1049   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478804 |       0.519365 |   0.491649 |
| Bori_Aron_solution-1 |     0.472566 |       0.77986  |   0.569758 |
| k-d_tree_polars      |     0.469822 |       0.569201 |   0.588954 |
| barab-szabi-1        |     0.47408  |       0.588264 |   0.612833 |
| k-d_tree_pandas      |     0.47019  |       0.512187 |   0.75774  |
| k-d_tree_sklearn     |     0.474595 |       1.29188  |   1.20989  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479613 |       0.738952 |   0.527537 |
| Bori_Aron_solution-1 |     0.48707  |       1.44584  |   0.611239 |
| k-d_tree_polars      |     0.48699  |       0.92279  |   0.91917  |
| barab-szabi-1        |     0.479646 |       0.94153  |   0.962762 |
| k-d_tree_pandas      |     0.488385 |       0.807645 |   1.18528  |
| k-d_tree_sklearn     |     0.476609 |       2.16587  |   1.23071  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46821  |        5.33736 |   0.772042 |
| Bori_Aron_solution-1 |     0.467256 |       11.0934  |   0.806969 |
| k-d_tree_sklearn     |     0.470783 |       17.246   |   1.30286  |
| k-d_tree_polars      |     0.483164 |        5.36776 |   6.7327   |
| barab-szabi-1        |     0.474017 |        5.38186 |   6.79743  |
| k-d_tree_pandas      |     0.478908 |        4.32462 |   7.17603  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634626 |        76.0242 |    2.99334 |
| k-d_tree_sklearn     |     0.625472 |       244.386  |    3.85491 |
| Bori_Aron_solution-1 |     0.47429  |       157.141  |   15.7774  |