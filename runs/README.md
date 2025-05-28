# 2025-05-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567014 |       0.437041 |   0.434116 |
| k-d_tree_polars      |     0.557863 |       0.416447 |   0.4344   |
| solution-1           |     7.72645  |       1e-06    |   0.453457 |
| barab-szabi-1        |     7.89841  |       0.453989 |   0.550486 |
| Bori_Aron_solution-1 |     0.546645 |       0.569088 |   0.563587 |
| k-d_tree_pandas      |     0.563858 |       0.401845 |   0.569083 |
| k-d_tree_sklearn     |     3.08074  |       1.10923  |   1.08454  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56996  |       0.433851 |   0.435711 |
| barab-szabi-1        |     0.566706 |       0.426083 |   0.43926  |
| k-d_tree_polars      |     0.569688 |       0.425186 |   0.442404 |
| Bori_Aron_solution-1 |     0.563479 |       0.584904 |   0.568647 |
| k-d_tree_pandas      |     0.571978 |       0.408023 |   0.580831 |
| k-d_tree_sklearn     |     0.583173 |       1.00735  |   1.10748  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567824 |       0.448889 |   0.447707 |
| k-d_tree_polars      |     0.568184 |       0.450413 |   0.46214  |
| barab-szabi-1        |     0.574489 |       0.468207 |   0.467025 |
| Bori_Aron_solution-1 |     0.568148 |       0.625977 |   0.592067 |
| k-d_tree_pandas      |     0.572213 |       0.423683 |   0.632776 |
| k-d_tree_sklearn     |     0.569993 |       1.0671   |   1.12576  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567811 |       0.509481 |   0.472724 |
| k-d_tree_polars      |     0.573594 |       0.56029  |   0.560415 |
| Bori_Aron_solution-1 |     0.558542 |       0.792273 |   0.577573 |
| barab-szabi-1        |     0.566629 |       0.564859 |   0.579801 |
| k-d_tree_pandas      |     0.577948 |       0.508182 |   0.769751 |
| k-d_tree_sklearn     |     0.571907 |       1.27884  |   1.19126  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567598 |       0.782082 |   0.530621 |
| Bori_Aron_solution-1 |     0.564382 |       1.49285  |   0.630583 |
| k-d_tree_polars      |     0.567893 |       0.909731 |   0.93961  |
| barab-szabi-1        |     0.582264 |       0.91027  |   0.986416 |
| k-d_tree_pandas      |     0.568795 |       0.777563 |   1.20945  |
| k-d_tree_sklearn     |     0.590882 |       2.18648  |   1.30632  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575423 |        5.84643 |   0.78001  |
| Bori_Aron_solution-1 |     0.569685 |       11.1932  |   0.909839 |
| k-d_tree_sklearn     |     0.571043 |       18.1033  |   1.38899  |
| k-d_tree_polars      |     0.562722 |        5.00868 |   6.91569  |
| barab-szabi-1        |     0.573841 |        5.07644 |   6.99636  |
| k-d_tree_pandas      |     0.571765 |        3.94335 |   7.57283  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610248 |        77.2147 |    3.12068 |
| k-d_tree_sklearn     |     0.68905  |       247.195  |    4.45516 |
| Bori_Aron_solution-1 |     0.56778  |       156.553  |   14.8686  |