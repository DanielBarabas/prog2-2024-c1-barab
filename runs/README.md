# 2025-06-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.78622  |       1e-06    |   0.41585  |
| k-d_tree_polars      |     0.542702 |       0.409679 |   0.428117 |
| barab-szabi-1        |     0.543109 |       0.421744 |   0.433706 |
| barab-szabi-2        |     0.544088 |       0.429524 |   0.44284  |
| Bori_Aron_solution-1 |     0.543228 |       0.555176 |   0.558756 |
| k-d_tree_pandas      |     8.32061  |       0.419646 |   0.668098 |
| k-d_tree_sklearn     |     3.24222  |       1.06768  |   1.1065   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587158 |       0.455271 |   0.431088 |
| k-d_tree_polars      |     0.600541 |       0.416904 |   0.434989 |
| barab-szabi-1        |     0.56866  |       0.425041 |   0.44448  |
| k-d_tree_pandas      |     0.571318 |       0.399401 |   0.561317 |
| Bori_Aron_solution-1 |     0.556656 |       0.57129  |   0.56892  |
| k-d_tree_sklearn     |     0.56415  |       1.00497  |   1.0636   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559635 |       0.435866 |   0.443274 |
| k-d_tree_polars      |     0.571171 |       0.459052 |   0.454446 |
| barab-szabi-1        |     0.569271 |       0.46807  |   0.47368  |
| Bori_Aron_solution-1 |     0.550479 |       0.631061 |   0.587056 |
| k-d_tree_pandas      |     0.561793 |       0.413196 |   0.607446 |
| k-d_tree_sklearn     |     0.56268  |       1.07313  |   1.11793  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565056 |       0.507431 |   0.467341 |
| k-d_tree_polars      |     0.570893 |       0.561416 |   0.562572 |
| barab-szabi-1        |     0.568404 |       0.553351 |   0.578644 |
| Bori_Aron_solution-1 |     0.547435 |       0.783591 |   0.580967 |
| k-d_tree_pandas      |     0.571099 |       0.506003 |   0.741503 |
| k-d_tree_sklearn     |     0.562651 |       1.25931  |   1.1391   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565414 |       0.760461 |   0.513194 |
| Bori_Aron_solution-1 |     0.551498 |       1.4231   |   0.591742 |
| k-d_tree_polars      |     0.558665 |       0.883628 |   0.918455 |
| barab-szabi-1        |     0.566821 |       0.893039 |   0.977188 |
| k-d_tree_pandas      |     0.553114 |       0.763296 |   1.19548  |
| k-d_tree_sklearn     |     0.571398 |       2.13581  |   1.23697  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565857 |        5.34027 |   0.754517 |
| Bori_Aron_solution-1 |     0.546902 |       10.6323  |   0.849117 |
| k-d_tree_sklearn     |     0.568753 |       16.2763  |   1.32371  |
| barab-szabi-1        |     0.561697 |        4.99339 |   6.56417  |
| k-d_tree_polars      |     0.558465 |        4.97561 |   6.59313  |
| k-d_tree_pandas      |     0.567511 |        3.89836 |   6.87011  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.84611  |        74.3354 |    2.91179 |
| k-d_tree_sklearn     |     0.661621 |       245.518  |    4.18055 |
| Bori_Aron_solution-1 |     0.558956 |       155.491  |   16.6497  |