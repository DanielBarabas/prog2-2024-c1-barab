# 2024-03-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.712461 |       0.380095 |   0.359786 |
| k-d_tree_polars      |     0.754014 |       0.432217 |   0.377782 |
| barab-szabi-1        |     0.752949 |       0.420578 |   0.383911 |
| solution-1           |     8.69998  |       1e-06    |   0.385559 |
| Bori_Aron_solution-1 |     0.698848 |       0.505436 |   0.499118 |
| k-d_tree_pandas      |     9.16668  |       0.413439 |   0.539186 |
| k-d_tree_sklearn     |     3.40653  |       0.942214 |   0.708376 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744301 |       0.382202 |   0.378814 |
| barab-szabi-1        |     0.75705  |       0.423893 |   0.385568 |
| k-d_tree_polars      |     0.77636  |       0.464274 |   0.391992 |
| k-d_tree_pandas      |     0.758502 |       0.408137 |   0.545709 |
| Bori_Aron_solution-1 |     0.749006 |       0.543021 |   0.55143  |
| k-d_tree_sklearn     |     0.765515 |       0.911019 |   0.716927 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.755322 |       0.401162 |   0.393347 |
| k-d_tree_polars      |     0.757648 |       0.464209 |   0.411166 |
| barab-szabi-1        |     0.762117 |       0.448082 |   0.420555 |
| Bori_Aron_solution-1 |     0.775664 |       0.573942 |   0.572645 |
| k-d_tree_pandas      |     0.762058 |       0.43709  |   0.585994 |
| k-d_tree_sklearn     |     0.758379 |       0.945208 |   0.740341 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.757886 |       0.46228  |   0.423791 |
| k-d_tree_polars      |     0.766945 |       0.567063 |   0.516763 |
| barab-szabi-1        |     0.758537 |       0.562399 |   0.538198 |
| Bori_Aron_solution-1 |     0.735855 |       0.792195 |   0.581113 |
| k-d_tree_pandas      |     0.778526 |       0.512919 |   0.7353   |
| k-d_tree_sklearn     |     0.79798  |       1.17837  |   0.806668 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.754393 |       0.723842 |   0.484481 |
| Bori_Aron_solution-1 |     0.744365 |       1.44398  |   0.561281 |
| k-d_tree_polars      |     0.771712 |       0.88646  |   0.876663 |
| k-d_tree_sklearn     |     0.758318 |       2.06987  |   0.893046 |
| barab-szabi-1        |     0.763642 |       0.880373 |   0.92862  |
| k-d_tree_pandas      |     0.765295 |       0.793563 |   1.16657  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.778866 |        5.65331 |   0.799001 |
| Bori_Aron_solution-1 |     0.746178 |       11.2603  |   0.82983  |
| k-d_tree_sklearn     |     0.765205 |       17.7728  |   1.1147   |
| barab-szabi-1        |     0.771451 |        5.03178 |   7.03683  |
| k-d_tree_polars      |     0.768874 |        5.01312 |   7.0755   |
| k-d_tree_pandas      |     0.748781 |        4.05816 |   7.32601  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.759292 |        78.2158 |    3.77544 |
| k-d_tree_sklearn     |     0.984341 |       233.218  |    4.92056 |
| Bori_Aron_solution-1 |     0.916166 |       149.43   |   18.7163  |