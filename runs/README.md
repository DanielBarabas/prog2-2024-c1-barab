# 2024-10-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618334 |       0.385322 |   0.383494 |
| barab-szabi-1        |     0.615217 |       0.397331 |   0.385605 |
| k-d_tree_polars      |     0.617696 |       0.399072 |   0.387059 |
| solution-1           |     7.77501  |       1e-06    |   0.399887 |
| Bori_Aron_solution-1 |     0.607806 |       0.523971 |   0.518547 |
| k-d_tree_pandas      |     0.613938 |       0.379129 |   0.522838 |
| k-d_tree_sklearn     |    10.4095   |       1.00173  |   0.979367 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613115 |       0.391089 |   0.389759 |
| barab-szabi-1        |     0.619649 |       0.404738 |   0.392122 |
| k-d_tree_polars      |     0.615033 |       0.412211 |   0.393077 |
| k-d_tree_pandas      |     0.613452 |       0.381781 |   0.533464 |
| Bori_Aron_solution-1 |     0.609045 |       0.526385 |   0.548347 |
| k-d_tree_sklearn     |     0.613464 |       0.888661 |   0.962458 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61595  |       0.405345 |   0.397778 |
| k-d_tree_polars      |     0.618329 |       0.448288 |   0.417859 |
| barab-szabi-1        |     0.616082 |       0.427435 |   0.420287 |
| Bori_Aron_solution-1 |     0.607644 |       0.578484 |   0.529666 |
| k-d_tree_pandas      |     0.614947 |       0.401732 |   0.571795 |
| k-d_tree_sklearn     |     0.616612 |       0.928973 |   0.981282 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616674 |       0.461855 |   0.42326  |
| k-d_tree_polars      |     0.614083 |       0.538696 |   0.518754 |
| barab-szabi-1        |     0.619041 |       0.536396 |   0.531778 |
| Bori_Aron_solution-1 |     0.607994 |       0.743475 |   0.533872 |
| k-d_tree_pandas      |     0.615897 |       0.477414 |   0.71279  |
| k-d_tree_sklearn     |     0.617441 |       1.14639  |   1.02919  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613811 |       0.720685 |   0.463142 |
| Bori_Aron_solution-1 |     0.601809 |       1.38859  |   0.562688 |
| k-d_tree_polars      |     0.617217 |       0.852559 |   0.87934  |
| barab-szabi-1        |     0.614832 |       0.844148 |   0.907502 |
| k-d_tree_sklearn     |     0.621573 |       2.03705  |   1.12519  |
| k-d_tree_pandas      |     0.613059 |       0.749129 |   1.15695  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616057 |        5.39018 |   0.735773 |
| Bori_Aron_solution-1 |     0.607599 |       11.065   |   0.808555 |
| k-d_tree_sklearn     |     0.614316 |       16.0129  |   1.24517  |
| k-d_tree_polars      |     0.614362 |        4.81766 |   6.54125  |
| barab-szabi-1        |     0.612614 |        4.85891 |   6.58178  |
| k-d_tree_pandas      |     0.623149 |        3.90257 |   7.05012  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.645243 |        71.7603 |    2.94378 |
| k-d_tree_sklearn     |     0.63109  |       227.582  |    4.28368 |
| Bori_Aron_solution-1 |     0.660246 |       151.563  |   15.6208  |