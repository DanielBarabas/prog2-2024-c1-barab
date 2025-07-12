# 2025-07-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.551026 |       0.421637 |   0.428365 |
| barab-szabi-2        |     7.72919  |       0.821245 |   0.433575 |
| k-d_tree_polars      |     0.574152 |       0.412313 |   0.465764 |
| solution-1           |     7.47961  |       1e-06    |   0.471857 |
| Bori_Aron_solution-1 |     0.549743 |       0.572231 |   0.550516 |
| k-d_tree_pandas      |     0.566301 |       0.399395 |   0.577269 |
| k-d_tree_sklearn     |     3.09366  |       1.2288   |   1.08443  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569672 |       0.427567 |   0.428197 |
| barab-szabi-1        |     0.560295 |       0.425726 |   0.442753 |
| k-d_tree_polars      |     0.572376 |       0.427948 |   0.451261 |
| Bori_Aron_solution-1 |     0.576758 |       0.578903 |   0.575339 |
| k-d_tree_pandas      |     0.574502 |       0.402116 |   0.583773 |
| k-d_tree_sklearn     |     0.581289 |       1.01372  |   1.10172  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57516  |       0.450603 |   0.448516 |
| k-d_tree_polars      |     0.569878 |       0.447088 |   0.470521 |
| barab-szabi-1        |     0.58011  |       0.446439 |   0.489738 |
| Bori_Aron_solution-1 |     0.564429 |       0.609851 |   0.576199 |
| k-d_tree_pandas      |     0.57065  |       0.421487 |   0.613907 |
| k-d_tree_sklearn     |     0.57227  |       1.0569   |   1.13285  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578284 |       0.519566 |   0.471347 |
| k-d_tree_polars      |     0.573445 |       0.552948 |   0.556274 |
| barab-szabi-1        |     0.561818 |       0.565579 |   0.569308 |
| Bori_Aron_solution-1 |     0.555911 |       0.786611 |   0.579184 |
| k-d_tree_pandas      |     0.570195 |       0.507276 |   0.756738 |
| k-d_tree_sklearn     |     0.566994 |       1.29924  |   1.14744  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570862 |       0.758698 |   0.503336 |
| Bori_Aron_solution-1 |     0.556141 |       1.44727  |   0.602853 |
| k-d_tree_polars      |     0.571376 |       0.895658 |   0.934007 |
| barab-szabi-1        |     0.561162 |       0.892188 |   0.957258 |
| k-d_tree_pandas      |     0.572405 |       0.78992  |   1.22602  |
| k-d_tree_sklearn     |     0.565438 |       2.13281  |   1.26911  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578293 |        5.21388 |   0.745633 |
| Bori_Aron_solution-1 |     0.564752 |       10.5825  |   0.842028 |
| k-d_tree_sklearn     |     0.567025 |       15.7714  |   1.30205  |
| k-d_tree_polars      |     0.554386 |        4.99606 |   6.41738  |
| barab-szabi-1        |     0.570462 |        5.00268 |   6.64898  |
| k-d_tree_pandas      |     0.55396  |        4.00482 |   6.86921  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55242  |        72.6964 |    2.68598 |
| k-d_tree_sklearn     |     0.779552 |       232.489  |    3.96909 |
| Bori_Aron_solution-1 |     0.570394 |       142.952  |   17.9943  |