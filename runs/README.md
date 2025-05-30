# 2025-05-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.28211  |       1e-06    |   0.356792 |
| barab-szabi-2        |     0.547765 |       0.412499 |   0.416348 |
| k-d_tree_polars      |     0.53541  |       0.405007 |   0.419432 |
| Bori_Aron_solution-1 |     0.528149 |       0.542019 |   0.535135 |
| k-d_tree_pandas      |     0.552026 |       0.384578 |   0.550024 |
| barab-szabi-1        |     7.55176  |       0.447598 |   0.5902   |
| k-d_tree_sklearn     |     2.85277  |       1.05899  |   1.05895  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550146 |       0.41221  |   0.41589  |
| k-d_tree_polars      |     0.548043 |       0.411511 |   0.423892 |
| barab-szabi-1        |     0.56167  |       0.408769 |   0.424262 |
| Bori_Aron_solution-1 |     0.540675 |       0.547826 |   0.541981 |
| k-d_tree_pandas      |     0.551772 |       0.387854 |   0.558895 |
| k-d_tree_sklearn     |     0.552196 |       0.965615 |   1.03672  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550357 |       0.428813 |   0.43061  |
| k-d_tree_polars      |     0.554926 |       0.433931 |   0.449926 |
| barab-szabi-1        |     0.545778 |       0.430403 |   0.451768 |
| Bori_Aron_solution-1 |     0.539979 |       0.584138 |   0.544072 |
| k-d_tree_pandas      |     0.550983 |       0.404556 |   0.595872 |
| k-d_tree_sklearn     |     0.552238 |       1.00642  |   1.07948  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54652  |       0.493664 |   0.459426 |
| k-d_tree_polars      |     0.549287 |       0.544387 |   0.543305 |
| barab-szabi-1        |     0.551482 |       0.545134 |   0.553582 |
| Bori_Aron_solution-1 |     0.543545 |       0.762203 |   0.556163 |
| k-d_tree_pandas      |     0.545007 |       0.491285 |   0.738963 |
| k-d_tree_sklearn     |     0.557511 |       1.23117  |   1.12059  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547148 |       0.739918 |   0.487531 |
| Bori_Aron_solution-1 |     0.543344 |       1.40493  |   0.580939 |
| k-d_tree_polars      |     0.548723 |       0.877056 |   0.895942 |
| barab-szabi-1        |     0.550756 |       0.884597 |   0.942097 |
| k-d_tree_pandas      |     0.553876 |       0.765723 |   1.17544  |
| k-d_tree_sklearn     |     0.560252 |       2.07799  |   1.23741  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545517 |        5.24718 |   0.73243  |
| Bori_Aron_solution-1 |     0.547828 |       10.5088  |   0.868278 |
| k-d_tree_sklearn     |     0.55722  |       15.8513  |   1.31129  |
| k-d_tree_polars      |     0.554629 |        4.95921 |   6.41848  |
| barab-szabi-1        |     0.547828 |        4.94362 |   6.4518   |
| k-d_tree_pandas      |     0.558198 |        3.9602  |   6.8578   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598773 |        79.8225 |    3.93314 |
| k-d_tree_sklearn     |     0.716    |       230.186  |    4.41407 |
| Bori_Aron_solution-1 |     0.543756 |       147.517  |   15.6065  |