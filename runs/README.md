# 2024-03-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.690781 |       0.372774 |   0.356471 |
| k-d_tree_polars      |     0.724046 |       0.398021 |   0.36286  |
| barab-szabi-1        |     0.717711 |       0.400748 |   0.363174 |
| solution-1           |     8.31698  |       1e-06    |   0.410167 |
| Bori_Aron_solution-1 |     0.673358 |       0.493292 |   0.49612  |
| k-d_tree_pandas      |     8.99336  |       0.458859 |   0.530775 |
| k-d_tree_sklearn     |     3.51315  |       0.879072 |   0.664931 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.717345 |       0.36055  |   0.358207 |
| k-d_tree_polars      |     0.718768 |       0.406132 |   0.367928 |
| barab-szabi-1        |     0.717628 |       0.404016 |   0.367976 |
| k-d_tree_pandas      |     0.728386 |       0.381595 |   0.509265 |
| Bori_Aron_solution-1 |     0.706221 |       0.514354 |   0.509712 |
| k-d_tree_sklearn     |     0.882069 |       0.856103 |   0.669386 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.717701 |       0.37945  |   0.371264 |
| k-d_tree_polars      |     0.717423 |       0.428778 |   0.39361  |
| barab-szabi-1        |     0.726538 |       0.466933 |   0.407346 |
| Bori_Aron_solution-1 |     0.707977 |       0.550902 |   0.515616 |
| k-d_tree_pandas      |     0.71651  |       0.397966 |   0.547206 |
| k-d_tree_sklearn     |     0.74455  |       0.890875 |   0.697261 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.717058 |       0.440113 |   0.402171 |
| k-d_tree_polars      |     0.718309 |       0.53745  |   0.490534 |
| barab-szabi-1        |     0.723242 |       0.542782 |   0.502464 |
| Bori_Aron_solution-1 |     0.714363 |       0.728605 |   0.510751 |
| k-d_tree_pandas      |     0.72548  |       0.486525 |   0.68032  |
| k-d_tree_sklearn     |     0.730852 |       1.10737  |   0.760621 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.720652 |       0.684103 |   0.436029 |
| Bori_Aron_solution-1 |     0.702751 |       1.36517  |   0.53605  |
| k-d_tree_polars      |     0.716576 |       0.858179 |   0.831992 |
| k-d_tree_sklearn     |     0.728698 |       1.91524  |   0.859794 |
| barab-szabi-1        |     0.714354 |       0.864751 |   0.864755 |
| k-d_tree_pandas      |     0.725326 |       0.756743 |   1.10871  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.723069 |        5.31915 |   0.757746 |
| Bori_Aron_solution-1 |     0.707798 |       10.7425  |   0.801389 |
| k-d_tree_sklearn     |     0.732695 |       15.9004  |   1.06584  |
| barab-szabi-1        |     0.715544 |        4.89015 |   6.5188   |
| k-d_tree_polars      |     0.721454 |        4.8992  |   6.55864  |
| k-d_tree_pandas      |     0.717451 |        3.99158 |   6.81234  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.718641 |        74.9973 |    3.71167 |
| k-d_tree_sklearn     |     0.852669 |       229.695  |    4.88193 |
| Bori_Aron_solution-1 |     0.782514 |       142.606  |   18.487   |