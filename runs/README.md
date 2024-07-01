# 2024-07-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539031 |       0.380319 |   0.371335 |
| k-d_tree_polars      |     0.535004 |       0.420698 |   0.388553 |
| barab-szabi-1        |     0.555654 |       0.403938 |   0.395707 |
| Bori_Aron_solution-1 |     0.528592 |       0.504555 |   0.510961 |
| solution-1           |     7.9056   |       1e-06    |   0.560405 |
| k-d_tree_sklearn     |     3.18348  |       1.13711  |   0.714562 |
| k-d_tree_pandas      |     8.61302  |       0.41789  |   0.755099 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565461 |       0.38545  |   0.380722 |
| k-d_tree_polars      |     0.549276 |       0.401374 |   0.389175 |
| barab-szabi-1        |     0.550097 |       0.40301  |   0.397033 |
| Bori_Aron_solution-1 |     0.546969 |       0.519664 |   0.508319 |
| k-d_tree_pandas      |     0.549235 |       0.380658 |   0.525213 |
| k-d_tree_sklearn     |     0.551811 |       0.91183  |   0.721669 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.556722 |       0.42071  |   0.41045  |
| barab-szabi-1        |     0.560872 |       0.439027 |   0.417749 |
| barab-szabi-2        |     0.581219 |       0.455964 |   0.447505 |
| Bori_Aron_solution-1 |     0.548369 |       0.55838  |   0.51302  |
| k-d_tree_pandas      |     0.569477 |       0.391521 |   0.576321 |
| k-d_tree_sklearn     |     0.594706 |       1.02608  |   0.782052 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567145 |       0.473307 |   0.443511 |
| k-d_tree_polars      |     0.559356 |       0.536652 |   0.518341 |
| barab-szabi-1        |     0.546041 |       0.529589 |   0.51866  |
| Bori_Aron_solution-1 |     0.555052 |       0.739123 |   0.558696 |
| k-d_tree_pandas      |     0.56023  |       0.476764 |   0.71441  |
| k-d_tree_sklearn     |     0.574822 |       1.18369  |   0.802    |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572628 |       0.73513  |   0.487528 |
| Bori_Aron_solution-1 |     0.564269 |       1.43159  |   0.588396 |
| k-d_tree_polars      |     0.585021 |       0.871681 |   0.891836 |
| k-d_tree_sklearn     |     0.574217 |       2.04723  |   0.911975 |
| barab-szabi-1        |     0.552766 |       0.868174 |   0.914261 |
| k-d_tree_pandas      |     0.552917 |       0.756079 |   1.19655  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548002 |        5.37118 |   0.761269 |
| Bori_Aron_solution-1 |     0.543993 |       10.4987  |   0.836436 |
| k-d_tree_sklearn     |     0.569155 |       15.5649  |   1.0735   |
| barab-szabi-1        |     0.563448 |        4.86091 |   6.56375  |
| k-d_tree_polars      |     0.55831  |        4.83141 |   6.70212  |
| k-d_tree_pandas      |     0.557615 |        3.8702  |   6.93089  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.819455 |        69.9951 |    4.01182 |
| k-d_tree_sklearn     |     0.644969 |       222.924  |    4.34493 |
| Bori_Aron_solution-1 |     0.568485 |       149.685  |   17.0419  |