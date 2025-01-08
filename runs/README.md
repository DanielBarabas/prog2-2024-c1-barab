# 2025-01-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.44914  |       1e-06    |   0.382747 |
| barab-szabi-2        |     0.602057 |       0.427179 |   0.414178 |
| barab-szabi-1        |     0.598959 |       0.42339  |   0.418746 |
| k-d_tree_polars      |     0.612964 |       0.425454 |   0.42517  |
| Bori_Aron_solution-1 |     0.604626 |       0.552664 |   0.551108 |
| k-d_tree_pandas      |     7.89922  |       0.417396 |   0.626789 |
| k-d_tree_sklearn     |     2.99886  |       1.06086  |   1.11658  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.630308 |       0.457586 |   0.434426 |
| barab-szabi-1        |     0.638    |       0.43746  |   0.435287 |
| barab-szabi-2        |     0.611069 |       0.429065 |   0.481001 |
| Bori_Aron_solution-1 |     0.610617 |       0.57492  |   0.559027 |
| k-d_tree_pandas      |     0.604136 |       0.406908 |   0.57599  |
| k-d_tree_sklearn     |     0.634825 |       1.01356  |   1.13454  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616479 |       0.430232 |   0.436296 |
| k-d_tree_polars      |     0.619641 |       0.454339 |   0.456088 |
| barab-szabi-1        |     0.615321 |       0.457627 |   0.462925 |
| Bori_Aron_solution-1 |     0.601452 |       0.59484  |   0.577114 |
| k-d_tree_pandas      |     0.616423 |       0.427881 |   0.633731 |
| k-d_tree_sklearn     |     0.608972 |       1.09039  |   1.1416   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600951 |       0.502766 |   0.471256 |
| k-d_tree_polars      |     0.617171 |       0.565186 |   0.554529 |
| barab-szabi-1        |     0.628948 |       0.608149 |   0.573189 |
| Bori_Aron_solution-1 |     0.618239 |       0.790843 |   0.600529 |
| k-d_tree_pandas      |     0.613478 |       0.508766 |   0.757767 |
| k-d_tree_sklearn     |     0.623583 |       1.27279  |   1.18267  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604626 |       0.754444 |   0.496069 |
| Bori_Aron_solution-1 |     0.60874  |       1.46149  |   0.615602 |
| k-d_tree_polars      |     0.627894 |       0.889178 |   0.930829 |
| barab-szabi-1        |     0.606194 |       0.891361 |   0.9654   |
| k-d_tree_pandas      |     0.624995 |       0.776804 |   1.23017  |
| k-d_tree_sklearn     |     0.613716 |       2.27823  |   1.29861  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609311 |        5.48359 |   0.783701 |
| Bori_Aron_solution-1 |     0.608151 |       10.8109  |   0.913513 |
| k-d_tree_sklearn     |     0.614413 |       16.8181  |   1.36734  |
| barab-szabi-1        |     0.623397 |        4.81024 |   6.80046  |
| k-d_tree_polars      |     0.61635  |        4.88695 |   6.81623  |
| k-d_tree_pandas      |     0.630664 |        3.90557 |   7.23581  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608631 |        78.2736 |    3.11017 |
| k-d_tree_sklearn     |     0.609365 |       240.153  |    4.49425 |
| Bori_Aron_solution-1 |     0.716546 |       154.651  |   17.6224  |