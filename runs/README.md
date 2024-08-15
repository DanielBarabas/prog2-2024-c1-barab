# 2024-08-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.99902  |       0.840636 |   0.382939 |
| barab-szabi-1        |     0.590306 |       0.395665 |   0.387875 |
| k-d_tree_polars      |     0.59414  |       0.400779 |   0.392737 |
| Bori_Aron_solution-1 |     0.613562 |       0.518456 |   0.512398 |
| k-d_tree_pandas      |     0.608107 |       0.461712 |   0.542821 |
| solution-1           |     7.90407  |       1e-06    |   0.594034 |
| k-d_tree_sklearn     |     3.02937  |       1.14846  |   0.717083 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.603886 |       0.399107 |   0.388816 |
| barab-szabi-1        |     0.605481 |       0.398595 |   0.389093 |
| barab-szabi-2        |     0.610566 |       0.389611 |   0.39348  |
| Bori_Aron_solution-1 |     0.59296  |       0.524833 |   0.519213 |
| k-d_tree_pandas      |     0.608308 |       0.408196 |   0.527025 |
| k-d_tree_sklearn     |     0.641147 |       0.877888 |   0.700843 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611564 |       0.406815 |   0.392654 |
| k-d_tree_polars      |     0.61074  |       0.423171 |   0.42379  |
| barab-szabi-1        |     0.606947 |       0.479203 |   0.425719 |
| Bori_Aron_solution-1 |     0.633553 |       0.5833   |   0.548207 |
| k-d_tree_pandas      |     0.607376 |       0.406853 |   0.57872  |
| k-d_tree_sklearn     |     0.61413  |       0.930634 |   0.727448 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621013 |       0.461859 |   0.428107 |
| k-d_tree_polars      |     0.606646 |       0.525334 |   0.514527 |
| barab-szabi-1        |     0.616735 |       0.529246 |   0.524355 |
| Bori_Aron_solution-1 |     0.595265 |       0.733523 |   0.529527 |
| k-d_tree_pandas      |     0.615045 |       0.472163 |   0.706081 |
| k-d_tree_sklearn     |     0.608117 |       1.15236  |   0.776689 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611925 |       0.711168 |   0.461028 |
| Bori_Aron_solution-1 |     0.59825  |       1.39222  |   0.565368 |
| k-d_tree_polars      |     0.60058  |       0.849748 |   0.861556 |
| k-d_tree_sklearn     |     0.607281 |       1.94493  |   0.862896 |
| barab-szabi-1        |     0.602702 |       0.862615 |   0.913799 |
| k-d_tree_pandas      |     0.606055 |       0.739837 |   1.12357  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621216 |        5.04973 |   0.7158   |
| Bori_Aron_solution-1 |     0.628201 |       10.3357  |   0.845565 |
| k-d_tree_sklearn     |     0.614176 |       15.4608  |   0.988863 |
| k-d_tree_polars      |     0.607673 |        4.85114 |   6.2785   |
| barab-szabi-1        |     0.606991 |        4.8263  |   6.28972  |
| k-d_tree_pandas      |     0.603096 |        3.8556  |   6.61563  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607205 |        73.5675 |    2.9203  |
| k-d_tree_sklearn     |     0.675591 |       234.053  |    3.98188 |
| Bori_Aron_solution-1 |     0.715487 |       147.074  |   18.2967  |