# 2025-09-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     9.05362  |       0.831629 |   0.435932 |
| barab-szabi-1        |     0.613238 |       0.425044 |   0.443741 |
| k-d_tree_polars      |     0.560305 |       0.435321 |   0.458616 |
| solution-1           |     8.6297   |       1e-06    |   0.503449 |
| k-d_tree_pandas      |     0.546738 |       0.398853 |   0.584192 |
| Bori_Aron_solution-1 |     0.733314 |       0.579873 |   0.593599 |
| k-d_tree_sklearn     |     3.36411  |       1.17627  |   1.10053  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551902 |       0.430686 |   0.43963  |
| k-d_tree_polars      |     0.555702 |       0.414217 |   0.440001 |
| barab-szabi-1        |     0.547669 |       0.414505 |   0.442186 |
| Bori_Aron_solution-1 |     0.547369 |       0.570881 |   0.559969 |
| k-d_tree_pandas      |     0.549387 |       0.422101 |   0.570896 |
| k-d_tree_sklearn     |     0.552575 |       1.00094  |   1.10152  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57194  |       0.454913 |   0.464382 |
| k-d_tree_polars      |     0.550292 |       0.449987 |   0.471386 |
| barab-szabi-1        |     0.562164 |       0.444817 |   0.488816 |
| Bori_Aron_solution-1 |     0.549482 |       0.600566 |   0.571939 |
| k-d_tree_pandas      |     0.562907 |       0.425333 |   0.627699 |
| k-d_tree_sklearn     |     0.564161 |       1.04072  |   1.16575  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559502 |       0.509481 |   0.479555 |
| k-d_tree_polars      |     0.557007 |       0.575457 |   0.57342  |
| Bori_Aron_solution-1 |     0.542747 |       0.787634 |   0.578027 |
| barab-szabi-1        |     0.569626 |       0.577322 |   0.588067 |
| k-d_tree_pandas      |     0.557362 |       0.504788 |   0.755894 |
| k-d_tree_sklearn     |     0.568102 |       1.27371  |   1.16296  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5458   |       0.776853 |   0.52234  |
| Bori_Aron_solution-1 |     0.539004 |       1.44212  |   0.615582 |
| k-d_tree_polars      |     0.543695 |       0.913288 |   0.936955 |
| barab-szabi-1        |     0.561852 |       0.906734 |   0.986079 |
| k-d_tree_pandas      |     0.557391 |       0.771751 |   1.20281  |
| k-d_tree_sklearn     |     0.5559   |       2.14455  |   1.25184  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544706 |        5.28978 |   0.772247 |
| Bori_Aron_solution-1 |     0.537759 |       10.8089  |   0.8666   |
| k-d_tree_sklearn     |     0.556975 |       16.6614  |   1.37694  |
| k-d_tree_polars      |     0.572205 |        5.06812 |   6.68598  |
| barab-szabi-1        |     0.555428 |        5.06939 |   6.70186  |
| k-d_tree_pandas      |     0.558949 |        3.93472 |   7.45696  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55614  |        74.7951 |    2.82902 |
| k-d_tree_sklearn     |     1.19546  |       240.724  |    4.23399 |
| Bori_Aron_solution-1 |     0.553658 |       141.383  |   18.3049  |