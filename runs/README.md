# 2025-06-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.57033  |       0.431874 |   0.452973 |
| barab-szabi-2        |     0.586733 |       0.499338 |   0.486278 |
| solution-1           |     8.00968  |       1e-06    |   0.519484 |
| Bori_Aron_solution-1 |     0.565937 |       0.593025 |   0.577258 |
| barab-szabi-1        |     7.88133  |       0.492761 |   0.590881 |
| k-d_tree_pandas      |     0.591168 |       0.418091 |   0.593606 |
| k-d_tree_sklearn     |     3.17508  |       1.20086  |   1.1675   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577476 |       0.439922 |   0.44408  |
| k-d_tree_polars      |     0.572037 |       0.430175 |   0.444274 |
| barab-szabi-1        |     0.592771 |       0.437601 |   0.446892 |
| Bori_Aron_solution-1 |     0.570099 |       0.582665 |   0.586895 |
| k-d_tree_pandas      |     0.578155 |       0.417768 |   0.589992 |
| k-d_tree_sklearn     |     0.580192 |       1.03921  |   1.11427  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578086 |       0.443657 |   0.447468 |
| k-d_tree_polars      |     0.585104 |       0.470266 |   0.477945 |
| barab-szabi-1        |     0.578483 |       0.459522 |   0.480463 |
| Bori_Aron_solution-1 |     0.574438 |       0.622977 |   0.582577 |
| k-d_tree_pandas      |     0.57906  |       0.422255 |   0.622498 |
| k-d_tree_sklearn     |     0.579739 |       1.06241  |   1.14051  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577967 |       0.531474 |   0.478204 |
| k-d_tree_polars      |     0.572718 |       0.567676 |   0.570144 |
| barab-szabi-1        |     0.576426 |       0.572046 |   0.585748 |
| Bori_Aron_solution-1 |     0.570934 |       0.800827 |   0.592884 |
| k-d_tree_pandas      |     0.587379 |       0.509629 |   0.768878 |
| k-d_tree_sklearn     |     0.581877 |       1.31393  |   1.20082  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586895 |       0.773371 |   0.628892 |
| Bori_Aron_solution-1 |     0.573988 |       1.50382  |   0.654715 |
| k-d_tree_polars      |     0.579709 |       0.904524 |   0.945009 |
| barab-szabi-1        |     0.57324  |       0.900155 |   0.97428  |
| k-d_tree_pandas      |     0.588433 |       0.784527 |   1.24012  |
| k-d_tree_sklearn     |     0.592704 |       2.3014   |   1.27623  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579447 |        5.41383 |   0.733171 |
| Bori_Aron_solution-1 |     0.564149 |       11.0267  |   0.859324 |
| k-d_tree_sklearn     |     0.573448 |       17.2798  |   1.39925  |
| k-d_tree_polars      |     0.57567  |        5.05    |   6.94276  |
| barab-szabi-1        |     0.578911 |        5.08101 |   6.98419  |
| k-d_tree_pandas      |     0.580021 |        3.98803 |   7.40563  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.65624  |        73.9097 |    2.90685 |
| k-d_tree_sklearn     |     0.805041 |       239.14   |    4.08472 |
| Bori_Aron_solution-1 |     0.550314 |       144.963  |   17.8398  |