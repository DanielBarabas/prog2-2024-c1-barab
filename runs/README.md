# 2024-06-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.66474  |       0.396217 |   0.343314 |
| barab-szabi-1        |     0.790432 |       0.39392  |   0.345829 |
| k-d_tree_polars      |     0.782493 |       0.400535 |   0.348806 |
| Bori_Aron_solution-1 |     4.63515  |       0.405897 |   0.39849  |
| k-d_tree_pandas      |     0.815604 |       0.375357 |   0.473199 |
| solution-1           |     8.26809  |       1e-06    |   0.583882 |
| k-d_tree_sklearn     |     3.42896  |       1.1531   |   0.668133 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.791428 |       0.344846 |   0.342763 |
| k-d_tree_polars      |     0.798501 |       0.404137 |   0.350569 |
| barab-szabi-1        |     0.790014 |       0.401521 |   0.383166 |
| Bori_Aron_solution-1 |     0.778629 |       0.480904 |   0.468382 |
| k-d_tree_pandas      |     0.793129 |       0.397398 |   0.478183 |
| k-d_tree_sklearn     |     0.802752 |       0.843472 |   0.677277 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.787786 |       0.357559 |   0.351096 |
| k-d_tree_polars      |     0.785678 |       0.428967 |   0.373932 |
| barab-szabi-1        |     0.793631 |       0.42636  |   0.37902  |
| Bori_Aron_solution-1 |     0.780571 |       0.52019  |   0.480912 |
| k-d_tree_pandas      |     0.784432 |       0.400373 |   0.524351 |
| k-d_tree_sklearn     |     0.793832 |       0.889138 |   0.694008 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.789058 |       0.423918 |   0.386471 |
| k-d_tree_polars      |     0.787843 |       0.536983 |   0.474643 |
| Bori_Aron_solution-1 |     0.815858 |       0.70215  |   0.48385  |
| barab-szabi-1        |     0.797877 |       0.546263 |   0.490438 |
| k-d_tree_pandas      |     0.80767  |       0.485079 |   0.667283 |
| k-d_tree_sklearn     |     0.803525 |       1.14052  |   0.753406 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.78682  |       0.669595 |   0.424773 |
| Bori_Aron_solution-1 |     0.783247 |       1.37905  |   0.514569 |
| k-d_tree_polars      |     0.788706 |       0.865293 |   0.822977 |
| k-d_tree_sklearn     |     0.793875 |       1.9891   |   0.869369 |
| barab-szabi-1        |     0.792812 |       0.873524 |   0.902526 |
| k-d_tree_pandas      |     0.820456 |       0.75963  |   1.10178  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.789628 |        5.28358 |   0.734864 |
| Bori_Aron_solution-1 |     0.779849 |       10.7839  |   0.769103 |
| k-d_tree_sklearn     |     0.79238  |       16.5085  |   1.04428  |
| k-d_tree_polars      |     0.795949 |        4.95981 |   6.65587  |
| barab-szabi-1        |     0.791098 |        5.00842 |   6.75074  |
| k-d_tree_pandas      |     0.793294 |        3.99938 |   7.02543  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.07018  |        72.6709 |    3.90729 |
| k-d_tree_sklearn     |     0.890532 |       235.065  |    4.58942 |
| Bori_Aron_solution-1 |     0.802935 |       150.194  |   17.4689  |