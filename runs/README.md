# 2024-12-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.638131 |       0.43011  |   0.4022   |
| barab-szabi-2        |     0.649704 |       0.402171 |   0.413779 |
| k-d_tree_polars      |     0.645837 |       0.437021 |   0.428723 |
| solution-1           |     8.89503  |       1e-06    |   0.44227  |
| Bori_Aron_solution-1 |     0.632486 |       0.544302 |   0.573009 |
| k-d_tree_pandas      |     0.635198 |       0.424758 |   0.598026 |
| k-d_tree_sklearn     |    11.7705   |       1.11812  |   1.02735  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.65016  |       0.454775 |   0.439254 |
| barab-szabi-1        |     0.694148 |       0.4674   |   0.452204 |
| barab-szabi-2        |     0.660039 |       0.432998 |   0.454439 |
| k-d_tree_pandas      |     0.689469 |       0.433122 |   0.589875 |
| Bori_Aron_solution-1 |     0.691182 |       0.629592 |   0.601135 |
| k-d_tree_sklearn     |     0.706614 |       1.02777  |   1.04455  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.708528 |       0.442085 |   0.440554 |
| k-d_tree_polars      |     0.656552 |       0.481062 |   0.448432 |
| barab-szabi-1        |     0.651295 |       0.498508 |   0.458215 |
| Bori_Aron_solution-1 |     0.65895  |       0.621716 |   0.585072 |
| k-d_tree_pandas      |     0.676475 |       0.42262  |   0.595055 |
| k-d_tree_sklearn     |     0.663457 |       1.07088  |   1.1283   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.677533 |       0.511875 |   0.462514 |
| k-d_tree_polars      |     0.639546 |       0.576425 |   0.560293 |
| barab-szabi-1        |     0.645226 |       0.599645 |   0.583328 |
| Bori_Aron_solution-1 |     0.675505 |       0.82582  |   0.62638  |
| k-d_tree_pandas      |     0.670378 |       0.544118 |   0.780442 |
| k-d_tree_sklearn     |     0.689928 |       1.25037  |   1.12344  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.65878  |       1.49441  |   0.632243 |
| barab-szabi-2        |     0.675563 |       0.79098  |   0.645849 |
| k-d_tree_polars      |     0.686851 |       0.916449 |   0.949729 |
| barab-szabi-1        |     0.68452  |       0.923239 |   0.989634 |
| k-d_tree_pandas      |     0.692696 |       0.778344 |   1.2497   |
| k-d_tree_sklearn     |     0.680471 |       2.33965  |   1.29723  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.694239 |        6.12605 |   0.802027 |
| Bori_Aron_solution-1 |     0.683536 |       11.566   |   0.884663 |
| k-d_tree_sklearn     |     0.651733 |       18.6427  |   1.40004  |
| barab-szabi-1        |     0.674463 |        5.01396 |   7.38481  |
| k-d_tree_polars      |     0.67471  |        4.98368 |   7.39188  |
| k-d_tree_pandas      |     0.667767 |        3.99352 |   7.6544   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625747 |        72.1022 |    3.14212 |
| k-d_tree_sklearn     |     0.667263 |       227.351  |    4.26171 |
| Bori_Aron_solution-1 |     0.646024 |       149.214  |   17.9695  |