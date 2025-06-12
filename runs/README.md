# 2025-06-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547118 |       0.431895 |   0.426084 |
| k-d_tree_polars      |     0.550659 |       0.408601 |   0.432903 |
| barab-szabi-1        |     0.547786 |       0.430025 |   0.451238 |
| solution-1           |     7.85589  |       1e-06    |   0.460837 |
| Bori_Aron_solution-1 |     0.71855  |       0.559147 |   0.563746 |
| k-d_tree_pandas      |     8.37228  |       0.424721 |   0.689329 |
| k-d_tree_sklearn     |     3.02223  |       1.08876  |   1.09884  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564092 |       0.439941 |   0.436491 |
| barab-szabi-1        |     0.560694 |       0.432328 |   0.437484 |
| k-d_tree_polars      |     0.55394  |       0.420314 |   0.453612 |
| Bori_Aron_solution-1 |     0.559646 |       0.573105 |   0.56132  |
| k-d_tree_pandas      |     0.568223 |       0.418857 |   0.586021 |
| k-d_tree_sklearn     |     0.57729  |       1.03937  |   1.10618  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571124 |       0.44364  |   0.444877 |
| k-d_tree_polars      |     0.571456 |       0.446384 |   0.463223 |
| barab-szabi-1        |     0.567831 |       0.451411 |   0.466961 |
| Bori_Aron_solution-1 |     0.564025 |       0.615864 |   0.576037 |
| k-d_tree_pandas      |     0.579747 |       0.421664 |   0.623108 |
| k-d_tree_sklearn     |     0.568428 |       1.05789  |   1.11881  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558954 |       0.492139 |   0.461621 |
| k-d_tree_polars      |     0.553798 |       0.552027 |   0.547861 |
| barab-szabi-1        |     0.548645 |       0.548605 |   0.558769 |
| Bori_Aron_solution-1 |     0.548291 |       0.768059 |   0.563509 |
| k-d_tree_pandas      |     0.556987 |       0.495523 |   0.755664 |
| k-d_tree_sklearn     |     0.561661 |       1.26698  |   1.1455   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56504  |       0.741606 |   0.496726 |
| Bori_Aron_solution-1 |     0.550995 |       1.4226   |   0.591282 |
| k-d_tree_polars      |     0.549208 |       0.897655 |   0.93086  |
| barab-szabi-1        |     0.551514 |       0.887466 |   0.954959 |
| k-d_tree_pandas      |     0.552991 |       0.76143  |   1.17581  |
| k-d_tree_sklearn     |     0.552936 |       2.06483  |   1.22709  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574918 |        5.44761 |   0.742888 |
| Bori_Aron_solution-1 |     0.550244 |       10.825   |   0.860367 |
| k-d_tree_sklearn     |     0.574226 |       16.3413  |   1.29906  |
| k-d_tree_polars      |     0.55462  |        4.99475 |   6.82785  |
| barab-szabi-1        |     0.56319  |        4.91118 |   6.90558  |
| k-d_tree_pandas      |     0.556043 |        3.96099 |   7.12349  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.821102 |        75.4397 |    3.10558 |
| k-d_tree_sklearn     |     0.695757 |       241.144  |    3.92374 |
| Bori_Aron_solution-1 |     0.556615 |       146.77   |   17.9269  |