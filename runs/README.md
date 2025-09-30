# 2025-09-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.695351 |       0.401242 |   0.421216 |
| barab-szabi-2        |     0.983708 |       1.01091  |   0.424071 |
| barab-szabi-1        |     0.993839 |       0.40014  |   0.425646 |
| Bori_Aron_solution-1 |     0.533542 |       0.542355 |   0.547875 |
| solution-1           |     7.95457  |       1e-06    |   0.793841 |
| k-d_tree_pandas      |     8.33215  |       0.434373 |   0.8192   |
| k-d_tree_sklearn     |     3.50479  |       1.29905  |   1.05071  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534454 |       0.421304 |   0.42212  |
| k-d_tree_polars      |     0.544392 |       0.409131 |   0.43215  |
| barab-szabi-1        |     0.539784 |       0.411319 |   0.43247  |
| Bori_Aron_solution-1 |     0.533272 |       0.552348 |   0.541747 |
| k-d_tree_pandas      |     0.537003 |       0.392283 |   0.551478 |
| k-d_tree_sklearn     |     0.540345 |       0.980863 |   1.05964  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538586 |       0.432625 |   0.439005 |
| k-d_tree_polars      |     0.538038 |       0.435417 |   0.456261 |
| barab-szabi-1        |     0.539591 |       0.44251  |   0.461355 |
| Bori_Aron_solution-1 |     0.532386 |       0.592147 |   0.544485 |
| k-d_tree_pandas      |     0.54091  |       0.406672 |   0.597703 |
| k-d_tree_sklearn     |     0.540675 |       1.01819  |   1.07231  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537212 |       0.51304  |   0.465857 |
| k-d_tree_polars      |     0.543941 |       0.570999 |   0.559847 |
| barab-szabi-1        |     0.544835 |       0.568706 |   0.56891  |
| Bori_Aron_solution-1 |     0.534467 |       0.789778 |   0.569144 |
| k-d_tree_pandas      |     0.535604 |       0.502368 |   0.740232 |
| k-d_tree_sklearn     |     0.54427  |       1.25559  |   1.12431  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544071 |       0.744609 |   0.500797 |
| Bori_Aron_solution-1 |     0.537479 |       1.47394  |   0.582164 |
| k-d_tree_polars      |     0.540003 |       0.948979 |   0.91261  |
| barab-szabi-1        |     0.537107 |       0.986775 |   0.953701 |
| k-d_tree_pandas      |     0.542659 |       0.832587 |   1.17871  |
| k-d_tree_sklearn     |     0.552558 |       2.1781   |   1.21053  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54279  |        5.40867 |   0.738423 |
| Bori_Aron_solution-1 |     0.556278 |       11.442   |   0.858384 |
| k-d_tree_sklearn     |     0.550419 |       18.4392  |   1.38495  |
| barab-szabi-1        |     0.577565 |        5.67903 |   6.9927   |
| k-d_tree_pandas      |     0.537522 |        4.62198 |   7.06235  |
| k-d_tree_polars      |     0.563474 |        5.73473 |   7.06458  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552698 |        74.2821 |    2.70154 |
| k-d_tree_sklearn     |     0.590098 |       233.367  |    4.12756 |
| Bori_Aron_solution-1 |     0.764606 |       143.43   |   18.0244  |