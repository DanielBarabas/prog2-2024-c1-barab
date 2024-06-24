# 2024-06-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.51084  |       1e-06    |   0.396732 |
| barab-szabi-2        |     0.808725 |       0.418181 |   0.404016 |
| barab-szabi-1        |     0.847442 |       0.428764 |   0.409074 |
| k-d_tree_polars      |     0.808759 |       0.43687  |   0.415165 |
| Bori_Aron_solution-1 |     0.797655 |       0.55383  |   0.562686 |
| k-d_tree_pandas      |     8.91216  |       0.42932  |   0.6152   |
| k-d_tree_sklearn     |     3.63284  |       1.08871  |   0.790723 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.844361 |       0.438074 |   0.417504 |
| barab-szabi-1        |     0.850888 |       0.444288 |   0.423545 |
| barab-szabi-2        |     0.83715  |       0.409449 |   0.425661 |
| k-d_tree_pandas      |     0.865546 |       0.419481 |   0.587527 |
| Bori_Aron_solution-1 |     0.846048 |       0.585917 |   0.605511 |
| k-d_tree_sklearn     |     0.856865 |       1.00446  |   0.789558 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.843448 |       0.431808 |   0.425963 |
| barab-szabi-1        |     0.836486 |       0.467605 |   0.452782 |
| k-d_tree_polars      |     0.848801 |       0.456769 |   0.48589  |
| Bori_Aron_solution-1 |     0.850571 |       0.614149 |   0.558491 |
| k-d_tree_pandas      |     0.844547 |       0.426408 |   0.627718 |
| k-d_tree_sklearn     |     0.856726 |       1.02848  |   0.821306 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.847017 |       0.493069 |   0.454026 |
| k-d_tree_polars      |     0.838211 |       0.550941 |   0.532914 |
| barab-szabi-1        |     0.84832  |       0.563601 |   0.557983 |
| Bori_Aron_solution-1 |     0.801692 |       0.78724  |   0.560305 |
| k-d_tree_pandas      |     0.881206 |       0.510225 |   0.745531 |
| k-d_tree_sklearn     |     0.863247 |       1.27294  |   0.892491 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.80913  |       0.719884 |   0.473208 |
| Bori_Aron_solution-1 |     0.79451  |       1.43506  |   0.562122 |
| k-d_tree_polars      |     0.813056 |       0.861588 |   0.896477 |
| barab-szabi-1        |     0.803599 |       0.865566 |   0.913418 |
| k-d_tree_sklearn     |     0.80878  |       2.06071  |   0.929602 |
| k-d_tree_pandas      |     0.816107 |       0.765914 |   1.15021  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.805127 |        5.50989 |   0.782356 |
| Bori_Aron_solution-1 |     0.793917 |       11.0385  |   0.851552 |
| k-d_tree_sklearn     |     0.804996 |       16.6433  |   1.0929   |
| k-d_tree_polars      |     0.80146  |        4.97    |   6.77919  |
| barab-szabi-1        |     0.798705 |        4.98152 |   6.79135  |
| k-d_tree_pandas      |     0.812778 |        3.98342 |   7.06032  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.09332  |        74.7882 |    4.03344 |
| k-d_tree_sklearn     |     0.916079 |       239.779  |    4.537   |
| Bori_Aron_solution-1 |     0.800972 |       151.594  |   18.2062  |