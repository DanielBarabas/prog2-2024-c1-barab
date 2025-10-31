# 2025-10-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.542791 |       0.415303 |   0.43965  |
| barab-szabi-1        |     0.554699 |       0.415486 |   0.441365 |
| barab-szabi-2        |     0.527885 |       0.702431 |   0.442951 |
| Bori_Aron_solution-1 |     0.525753 |       0.566597 |   0.571023 |
| solution-1           |     8.47099  |       1e-06    |   0.791293 |
| k-d_tree_pandas      |     9.0316   |       0.464711 |   1.04683  |
| k-d_tree_sklearn     |     3.27694  |       1.51367  |   1.10254  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557053 |       0.450693 |   0.447957 |
| k-d_tree_polars      |     0.548357 |       0.434354 |   0.452593 |
| barab-szabi-1        |     0.539966 |       0.428372 |   0.491192 |
| Bori_Aron_solution-1 |     0.528604 |       0.574893 |   0.565732 |
| k-d_tree_pandas      |     0.536071 |       0.406507 |   0.570956 |
| k-d_tree_sklearn     |     0.535651 |       0.991651 |   1.09735  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54348  |       0.447121 |   0.456819 |
| k-d_tree_polars      |     0.545519 |       0.450607 |   0.47203  |
| barab-szabi-1        |     0.579354 |       0.477749 |   0.475515 |
| Bori_Aron_solution-1 |     0.536109 |       0.603574 |   0.571796 |
| k-d_tree_pandas      |     0.535326 |       0.428459 |   0.650429 |
| k-d_tree_sklearn     |     0.54163  |       1.06041  |   1.15004  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537857 |       0.511855 |   0.483981 |
| k-d_tree_polars      |     0.539551 |       0.578474 |   0.570541 |
| barab-szabi-1        |     0.547433 |       0.574679 |   0.579202 |
| Bori_Aron_solution-1 |     0.526919 |       0.804694 |   0.594763 |
| k-d_tree_pandas      |     0.545084 |       0.507324 |   0.769713 |
| k-d_tree_sklearn     |     0.550643 |       1.32916  |   1.19633  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542609 |       0.765991 |   0.533766 |
| Bori_Aron_solution-1 |     0.534971 |       1.49701  |   0.61579  |
| k-d_tree_polars      |     0.544308 |       0.945477 |   0.941648 |
| barab-szabi-1        |     0.539106 |       0.951115 |   0.979265 |
| k-d_tree_pandas      |     0.543491 |       0.833292 |   1.22459  |
| k-d_tree_sklearn     |     0.543474 |       2.20715  |   1.28549  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539642 |        5.80212 |   0.816416 |
| Bori_Aron_solution-1 |     0.54427  |       11.4949  |   0.859122 |
| k-d_tree_sklearn     |     0.552595 |       18.4053  |   1.41265  |
| k-d_tree_polars      |     0.562459 |        5.44998 |   7.03911  |
| k-d_tree_pandas      |     0.544102 |        4.5243  |   7.37543  |
| barab-szabi-1        |     0.560369 |        5.51113 |   7.38288  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537426 |        76.8017 |    2.81546 |
| k-d_tree_sklearn     |     0.566317 |       253.281  |    4.26321 |
| Bori_Aron_solution-1 |     0.743925 |       150.712  |   17.963   |