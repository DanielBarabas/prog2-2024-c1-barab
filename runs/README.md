# 2024-09-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623321 |       0.405021 |   0.404224 |
| barab-szabi-1        |     0.643485 |       0.420269 |   0.410957 |
| solution-1           |     7.902    |       2e-06    |   0.412188 |
| k-d_tree_polars      |     4.27409  |       0.440682 |   0.41853  |
| Bori_Aron_solution-1 |     4.58462  |       0.516689 |   0.485537 |
| k-d_tree_pandas      |     0.638634 |       0.404204 |   0.586449 |
| k-d_tree_sklearn     |     3.05122  |       0.991272 |   0.737712 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.646562 |       0.417038 |   0.402521 |
| barab-szabi-1        |     0.65748  |       0.425264 |   0.402707 |
| k-d_tree_polars      |     0.652014 |       0.417211 |   0.413809 |
| Bori_Aron_solution-1 |     0.627453 |       0.598449 |   0.540027 |
| k-d_tree_pandas      |     0.6404   |       0.38664  |   0.547954 |
| k-d_tree_sklearn     |     0.632662 |       0.949754 |   0.732454 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.667255 |       0.413173 |   0.401833 |
| k-d_tree_polars      |     0.627877 |       0.455773 |   0.435471 |
| barab-szabi-1        |     0.638621 |       0.451225 |   0.445437 |
| Bori_Aron_solution-1 |     0.622425 |       0.625675 |   0.549548 |
| k-d_tree_pandas      |     0.6482   |       0.432181 |   0.629716 |
| k-d_tree_sklearn     |     0.663895 |       1.04933  |   0.807206 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.636197 |       0.485782 |   0.443167 |
| k-d_tree_polars      |     0.652695 |       0.568721 |   0.523166 |
| Bori_Aron_solution-1 |     0.628446 |       0.765704 |   0.572755 |
| barab-szabi-1        |     0.667754 |       0.571342 |   0.578632 |
| k-d_tree_pandas      |     0.633685 |       0.491673 |   0.73565  |
| k-d_tree_sklearn     |     0.630485 |       1.25009  |   0.826776 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639492 |       0.74341  |   0.550962 |
| Bori_Aron_solution-1 |     0.659387 |       1.48819  |   0.603855 |
| k-d_tree_sklearn     |     0.662698 |       2.21169  |   0.916263 |
| barab-szabi-1        |     0.631286 |       0.873656 |   0.95014  |
| k-d_tree_polars      |     0.636129 |       0.918907 |   0.97254  |
| k-d_tree_pandas      |     0.679325 |       0.791953 |   1.25708  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.653672 |        5.84742 |   0.79155  |
| Bori_Aron_solution-1 |     0.631302 |       11.1973  |   0.862254 |
| k-d_tree_sklearn     |     0.652784 |       18.1886  |   1.10201  |
| barab-szabi-1        |     0.659266 |        4.8067  |   6.6843   |
| k-d_tree_polars      |     0.645628 |        4.91097 |   7.20746  |
| k-d_tree_pandas      |     0.629612 |        3.9254  |   7.41245  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.702819 |        74.8163 |    3.10632 |
| k-d_tree_sklearn     |     0.94066  |       233.187  |    3.87924 |
| Bori_Aron_solution-1 |     0.604941 |       150.117  |   17.3526  |