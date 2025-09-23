# 2025-09-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     9.28478  |       0.825633 |   0.433154 |
| k-d_tree_polars      |     0.537872 |       0.410708 |   0.43683  |
| barab-szabi-1        |     0.534497 |       0.415276 |   0.447079 |
| solution-1           |     7.88086  |       1e-06    |   0.508878 |
| k-d_tree_pandas      |     0.54037  |       0.389917 |   0.559471 |
| Bori_Aron_solution-1 |     0.528073 |       0.553323 |   0.563988 |
| k-d_tree_sklearn     |     3.01224  |       1.22798  |   1.09038  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.55107  |       0.418562 |   0.435247 |
| barab-szabi-2        |     0.552445 |       0.433952 |   0.438901 |
| barab-szabi-1        |     0.553144 |       0.421379 |   0.43964  |
| Bori_Aron_solution-1 |     0.543989 |       0.565721 |   0.562061 |
| k-d_tree_pandas      |     0.551698 |       0.400172 |   0.578788 |
| k-d_tree_sklearn     |     0.561915 |       0.991083 |   1.08598  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553621 |       0.449911 |   0.462957 |
| barab-szabi-1        |     0.558803 |       0.449995 |   0.46754  |
| k-d_tree_polars      |     0.563434 |       0.449955 |   0.514049 |
| Bori_Aron_solution-1 |     0.555058 |       0.603214 |   0.566263 |
| k-d_tree_pandas      |     0.566969 |       0.416787 |   0.619777 |
| k-d_tree_sklearn     |     0.567471 |       1.0476   |   1.11211  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564526 |       0.513483 |   0.483005 |
| k-d_tree_polars      |     0.570112 |       0.557757 |   0.561696 |
| Bori_Aron_solution-1 |     0.55024  |       0.786647 |   0.589851 |
| barab-szabi-1        |     0.556963 |       0.566397 |   0.598396 |
| k-d_tree_pandas      |     0.559715 |       0.517983 |   0.757806 |
| k-d_tree_sklearn     |     0.571351 |       1.28589  |   1.18343  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558303 |       0.78275  |   0.569251 |
| Bori_Aron_solution-1 |     0.570345 |       1.45695  |   0.620162 |
| k-d_tree_polars      |     0.574036 |       0.918555 |   0.975506 |
| barab-szabi-1        |     0.558331 |       0.919774 |   0.983292 |
| k-d_tree_pandas      |     0.567609 |       0.781761 |   1.24535  |
| k-d_tree_sklearn     |     0.569096 |       2.14651  |   1.26305  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555756 |        5.55804 |   0.762773 |
| Bori_Aron_solution-1 |     0.553324 |       10.8653  |   0.851879 |
| k-d_tree_sklearn     |     0.550612 |       17.0458  |   1.36265  |
| k-d_tree_polars      |     0.551936 |        5.02217 |   6.8016   |
| barab-szabi-1        |     0.552708 |        5.05374 |   6.81366  |
| k-d_tree_pandas      |     0.556509 |        3.9564  |   7.2118   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567124 |        77.7415 |    2.8111  |
| k-d_tree_sklearn     |     1.18364  |       240.412  |    4.18458 |
| Bori_Aron_solution-1 |     0.557994 |       148.962  |   18.2299  |