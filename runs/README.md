# 2024-07-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.81361  |       1e-06    |   0.354077 |
| barab-szabi-2        |     0.552625 |       0.40927  |   0.380959 |
| barab-szabi-1        |     0.56091  |       0.396369 |   0.387351 |
| k-d_tree_polars      |     0.552231 |       0.398753 |   0.391002 |
| Bori_Aron_solution-1 |     0.5457   |       0.522333 |   0.520156 |
| k-d_tree_pandas      |     0.555312 |       0.376593 |   0.528839 |
| k-d_tree_sklearn     |    10.358    |       0.978201 |   0.692232 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.555772 |       0.400559 |   0.391455 |
| k-d_tree_polars      |     0.552558 |       0.403164 |   0.39731  |
| barab-szabi-2        |     0.555193 |       0.389766 |   0.415694 |
| Bori_Aron_solution-1 |     0.54845  |       0.527751 |   0.519086 |
| k-d_tree_pandas      |     0.559433 |       0.393107 |   0.536024 |
| k-d_tree_sklearn     |     0.571986 |       0.884725 |   0.712811 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56099  |       0.402919 |   0.407487 |
| k-d_tree_polars      |     0.55352  |       0.432396 |   0.413777 |
| barab-szabi-1        |     0.558778 |       0.429941 |   0.422779 |
| Bori_Aron_solution-1 |     0.547291 |       0.560163 |   0.53526  |
| k-d_tree_pandas      |     0.552173 |       0.405071 |   0.592829 |
| k-d_tree_sklearn     |     0.571063 |       1.01324  |   0.775935 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57916  |       0.461905 |   0.438727 |
| barab-szabi-1        |     0.557424 |       0.545346 |   0.527827 |
| k-d_tree_polars      |     0.572176 |       0.570843 |   0.547686 |
| Bori_Aron_solution-1 |     0.549304 |       0.768859 |   0.558818 |
| k-d_tree_pandas      |     0.580313 |       0.493539 |   0.7219   |
| k-d_tree_sklearn     |     0.596259 |       1.17756  |   0.809238 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550401 |       0.714535 |   0.467844 |
| Bori_Aron_solution-1 |     0.558213 |       1.39944  |   0.56579  |
| k-d_tree_polars      |     0.569863 |       0.851345 |   0.867801 |
| k-d_tree_sklearn     |     0.558645 |       2.01779  |   0.886459 |
| barab-szabi-1        |     0.558079 |       0.856922 |   0.918901 |
| k-d_tree_pandas      |     0.553419 |       0.751967 |   1.14725  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562885 |        5.43231 |   0.739643 |
| Bori_Aron_solution-1 |     0.554573 |       10.7462  |   0.869431 |
| k-d_tree_sklearn     |     0.561651 |       16.48    |   1.00023  |
| barab-szabi-1        |     0.559938 |        4.8653  |   6.53827  |
| k-d_tree_polars      |     0.551877 |        4.87972 |   6.54994  |
| k-d_tree_pandas      |     0.551889 |        3.87572 |   7.00966  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.817962 |        74.8096 |    3.88195 |
| k-d_tree_sklearn     |     0.568549 |       231.674  |    3.99863 |
| Bori_Aron_solution-1 |     0.563922 |       149.92   |   18.2098  |