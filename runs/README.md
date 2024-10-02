# 2024-10-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.87644  |       1e-06    |   0.367899 |
| barab-szabi-2        |     0.679597 |       0.413238 |   0.413222 |
| barab-szabi-1        |     0.668129 |       0.428027 |   0.415432 |
| k-d_tree_polars      |     0.63745  |       0.432498 |   0.42199  |
| Bori_Aron_solution-1 |     4.47792  |       0.572206 |   0.49739  |
| k-d_tree_pandas      |     4.43129  |       0.446403 |   0.57596  |
| k-d_tree_sklearn     |     3.04176  |       1.03513  |   1.04795  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.663005 |       0.414196 |   0.415317 |
| k-d_tree_polars      |     0.660187 |       0.442981 |   0.420079 |
| barab-szabi-1        |     0.654345 |       0.441571 |   0.4226   |
| Bori_Aron_solution-1 |     0.653776 |       0.585823 |   0.56605  |
| k-d_tree_pandas      |     0.66964  |       0.417897 |   0.582628 |
| k-d_tree_sklearn     |     0.658486 |       0.978532 |   1.07559  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.638943 |       0.416787 |   0.410174 |
| barab-szabi-1        |     0.653579 |       0.45057  |   0.437763 |
| k-d_tree_polars      |     0.655999 |       0.47582  |   0.446077 |
| Bori_Aron_solution-1 |     0.659544 |       0.61487  |   0.5791   |
| k-d_tree_pandas      |     0.654349 |       0.449811 |   0.639319 |
| k-d_tree_sklearn     |     0.634643 |       0.97657  |   1.04236  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.668359 |       0.488904 |   0.461608 |
| k-d_tree_polars      |     0.675013 |       0.597019 |   0.568034 |
| barab-szabi-1        |     0.671878 |       0.589061 |   0.580045 |
| Bori_Aron_solution-1 |     0.647664 |       0.811448 |   0.589012 |
| k-d_tree_pandas      |     0.66282  |       0.523383 |   0.782459 |
| k-d_tree_sklearn     |     0.68952  |       1.28362  |   1.17915  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.636971 |       0.738389 |   0.548657 |
| Bori_Aron_solution-1 |     0.663506 |       1.46697  |   0.621757 |
| k-d_tree_polars      |     0.638917 |       0.877554 |   0.903206 |
| barab-szabi-1        |     0.63838  |       0.889705 |   0.965783 |
| k-d_tree_pandas      |     0.656623 |       0.763078 |   1.19751  |
| k-d_tree_sklearn     |     0.660707 |       2.11736  |   1.20368  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.654896 |        5.85903 |   0.792302 |
| Bori_Aron_solution-1 |     0.650033 |       11.3298  |   0.880525 |
| k-d_tree_sklearn     |     0.673449 |       17.8937  |   1.36542  |
| barab-szabi-1        |     0.665402 |        4.85385 |   7.30852  |
| k-d_tree_polars      |     0.654686 |        4.87535 |   7.35155  |
| k-d_tree_pandas      |     0.667655 |        3.87646 |   7.56884  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.742604 |        73.9506 |    3.20734 |
| k-d_tree_sklearn     |     0.936208 |       233.191  |    4.45306 |
| Bori_Aron_solution-1 |     0.661179 |       155.216  |   16.7808  |