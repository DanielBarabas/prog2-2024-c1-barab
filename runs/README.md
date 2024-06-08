# 2024-06-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.805782 |       0.40163  |   0.349204 |
| k-d_tree_polars      |     0.794463 |       0.405571 |   0.349564 |
| barab-szabi-2        |     4.63863  |       0.367188 |   0.353017 |
| Bori_Aron_solution-1 |     4.83633  |       0.419045 |   0.415807 |
| k-d_tree_pandas      |     0.800803 |       0.388817 |   0.487543 |
| solution-1           |     8.3817   |       1e-06    |   0.517318 |
| k-d_tree_sklearn     |     3.66847  |       1.09195  |   0.675543 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.800953 |       0.350273 |   0.349178 |
| barab-szabi-1        |     0.798967 |       0.419405 |   0.354625 |
| k-d_tree_polars      |     0.808267 |       0.419019 |   0.355852 |
| Bori_Aron_solution-1 |     0.788546 |       0.481102 |   0.483321 |
| k-d_tree_pandas      |     0.799962 |       0.390777 |   0.490398 |
| k-d_tree_sklearn     |     0.80473  |       0.856669 |   0.686213 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.791844 |       0.36907  |   0.36489  |
| k-d_tree_polars      |     0.802    |       0.450719 |   0.378411 |
| barab-szabi-1        |     0.803865 |       0.434377 |   0.384392 |
| Bori_Aron_solution-1 |     0.787059 |       0.544519 |   0.483418 |
| k-d_tree_pandas      |     0.802921 |       0.410259 |   0.533834 |
| k-d_tree_sklearn     |     0.80124  |       0.92283  |   0.726929 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.797487 |       0.425793 |   0.394153 |
| k-d_tree_polars      |     0.817615 |       0.557414 |   0.480536 |
| barab-szabi-1        |     0.797709 |       0.546874 |   0.488287 |
| Bori_Aron_solution-1 |     0.796641 |       0.705316 |   0.501801 |
| k-d_tree_pandas      |     0.787809 |       0.491196 |   0.663549 |
| k-d_tree_sklearn     |     0.806502 |       1.13084  |   0.772887 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.795276 |       0.695794 |   0.438715 |
| Bori_Aron_solution-1 |     0.78973  |       1.37071  |   0.527377 |
| k-d_tree_polars      |     0.813063 |       0.869462 |   0.843305 |
| barab-szabi-1        |     0.808515 |       0.868109 |   0.875539 |
| k-d_tree_sklearn     |     0.827921 |       1.98025  |   0.877599 |
| k-d_tree_pandas      |     0.791116 |       0.760312 |   1.10832  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.800095 |        5.14098 |   0.726606 |
| Bori_Aron_solution-1 |     0.792946 |       10.634   |   0.770585 |
| k-d_tree_sklearn     |     0.813329 |       15.9994  |   1.06293  |
| k-d_tree_polars      |     0.797937 |        5.0176  |   6.43879  |
| barab-szabi-1        |     0.800772 |        5.02695 |   6.45259  |
| k-d_tree_pandas      |     0.804212 |        4.03109 |   6.82146  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.08857  |        72.2257 |    3.84553 |
| k-d_tree_sklearn     |     0.974853 |       227.078  |    4.54517 |
| Bori_Aron_solution-1 |     0.805305 |       149.73   |   17.8575  |