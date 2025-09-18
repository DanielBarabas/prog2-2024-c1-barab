# 2025-09-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.29413  |       1e-06    |   0.421031 |
| k-d_tree_polars      |     0.541787 |       0.4186   |   0.441425 |
| barab-szabi-2        |     8.10156  |       0.633155 |   0.445491 |
| barab-szabi-1        |     0.533807 |       0.418383 |   0.447523 |
| Bori_Aron_solution-1 |     0.533902 |       0.571377 |   0.567653 |
| k-d_tree_pandas      |     0.541071 |       0.403284 |   0.571456 |
| k-d_tree_sklearn     |     3.04098  |       1.07544  |   1.10363  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.592859 |       0.445722 |   0.441633 |
| barab-szabi-1        |     0.554292 |       0.447605 |   0.445792 |
| k-d_tree_polars      |     0.558517 |       0.449382 |   0.446819 |
| Bori_Aron_solution-1 |     0.546957 |       0.596538 |   0.56788  |
| k-d_tree_pandas      |     0.556418 |       0.418413 |   0.5804   |
| k-d_tree_sklearn     |     0.557577 |       1.00471  |   1.14278  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551374 |       0.452857 |   0.45691  |
| k-d_tree_polars      |     0.572942 |       0.447938 |   0.467418 |
| barab-szabi-1        |     0.552915 |       0.441827 |   0.476811 |
| Bori_Aron_solution-1 |     0.54724  |       0.620161 |   0.577084 |
| k-d_tree_pandas      |     0.554121 |       0.42238  |   0.625379 |
| k-d_tree_sklearn     |     0.568406 |       1.0417   |   1.1358   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56454  |       0.518044 |   0.48264  |
| k-d_tree_polars      |     0.553037 |       0.565564 |   0.56548  |
| barab-szabi-1        |     0.55356  |       0.567796 |   0.577966 |
| Bori_Aron_solution-1 |     0.554862 |       0.829827 |   0.582069 |
| k-d_tree_pandas      |     0.555641 |       0.494715 |   0.755017 |
| k-d_tree_sklearn     |     0.560085 |       1.28577  |   1.16356  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553867 |       0.783    |   0.53612  |
| Bori_Aron_solution-1 |     0.545504 |       1.43952  |   0.603322 |
| k-d_tree_polars      |     0.563784 |       0.921116 |   0.971488 |
| barab-szabi-1        |     0.563264 |       0.921697 |   1.00065  |
| k-d_tree_pandas      |     0.553299 |       0.76403  |   1.20474  |
| k-d_tree_sklearn     |     0.565153 |       2.1904   |   1.25141  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562837 |        5.45305 |   0.760864 |
| Bori_Aron_solution-1 |     0.54778  |       10.8693  |   0.864195 |
| k-d_tree_sklearn     |     0.590317 |       17.1355  |   1.34848  |
| k-d_tree_polars      |     0.563579 |        5.11371 |   6.85089  |
| barab-szabi-1        |     0.566263 |        5.09442 |   6.85461  |
| k-d_tree_pandas      |     0.556632 |        3.95778 |   7.1585   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553807 |         76.376 |    2.81075 |
| k-d_tree_sklearn     |     0.69415  |        238.232 |    4.09145 |
| Bori_Aron_solution-1 |     0.568179 |        145.903 |   17.6709  |