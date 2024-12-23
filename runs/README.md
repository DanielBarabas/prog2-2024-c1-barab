# 2024-12-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.64011  |       1e-06    |   0.357975 |
| barab-szabi-1        |     0.613469 |       0.401091 |   0.388981 |
| barab-szabi-2        |     0.62358  |       0.391325 |   0.395345 |
| k-d_tree_polars      |     0.617272 |       0.401223 |   0.397324 |
| Bori_Aron_solution-1 |     0.61183  |       0.521385 |   0.52245  |
| k-d_tree_pandas      |     0.622248 |       0.377629 |   0.527589 |
| k-d_tree_sklearn     |    10.574    |       1.00318  |   0.965029 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615368 |       0.396545 |   0.389859 |
| k-d_tree_polars      |     0.615958 |       0.410148 |   0.396049 |
| barab-szabi-1        |     0.612577 |       0.412295 |   0.397852 |
| Bori_Aron_solution-1 |     0.610165 |       0.528076 |   0.530919 |
| k-d_tree_pandas      |     0.614587 |       0.386549 |   0.550698 |
| k-d_tree_sklearn     |     0.634339 |       0.902479 |   0.977347 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614275 |       0.413303 |   0.399285 |
| k-d_tree_polars      |     0.612815 |       0.424827 |   0.42097  |
| barab-szabi-1        |     0.616376 |       0.43596  |   0.422656 |
| Bori_Aron_solution-1 |     0.613929 |       0.567015 |   0.523474 |
| k-d_tree_pandas      |     0.613066 |       0.410325 |   0.576805 |
| k-d_tree_sklearn     |     0.617411 |       0.939862 |   0.997838 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612946 |       0.469578 |   0.427386 |
| barab-szabi-1        |     0.619325 |       0.531826 |   0.525368 |
| k-d_tree_polars      |     0.614339 |       0.539233 |   0.525976 |
| Bori_Aron_solution-1 |     0.606388 |       0.745558 |   0.537111 |
| k-d_tree_pandas      |     0.614467 |       0.478813 |   0.707903 |
| k-d_tree_sklearn     |     0.616279 |       1.16427  |   1.04947  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619925 |       0.718785 |   0.468315 |
| Bori_Aron_solution-1 |     0.606835 |       1.39018  |   0.559691 |
| k-d_tree_polars      |     0.622313 |       0.885028 |   0.864417 |
| barab-szabi-1        |     0.612423 |       0.863129 |   0.903054 |
| k-d_tree_pandas      |     0.614517 |       0.747048 |   1.14252  |
| k-d_tree_sklearn     |     0.620083 |       1.99864  |   1.15404  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610421 |        5.40619 |   0.746815 |
| Bori_Aron_solution-1 |     0.606585 |       10.7144  |   0.82273  |
| k-d_tree_sklearn     |     0.615676 |       16.0828  |   1.24694  |
| k-d_tree_polars      |     0.611397 |        4.91902 |   6.51308  |
| barab-szabi-1        |     0.60925  |        4.91876 |   6.60637  |
| k-d_tree_pandas      |     0.62831  |        3.91746 |   6.95671  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.63666  |        74.2592 |    3.33932 |
| k-d_tree_sklearn     |     0.617598 |       232.087  |    4.21046 |
| Bori_Aron_solution-1 |     0.730921 |       150.519  |   17.6332  |