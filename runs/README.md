# 2025-02-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.3198   |       1e-06    |   0.35879  |
| barab-szabi-2        |     3.80412  |       0.41949  |   0.403578 |
| k-d_tree_polars      |     0.605112 |       0.4097   |   0.414202 |
| barab-szabi-1        |     0.599513 |       0.413099 |   0.415035 |
| Bori_Aron_solution-1 |     4.55121  |       0.590206 |   0.478234 |
| k-d_tree_pandas      |     0.598365 |       0.388468 |   0.558146 |
| k-d_tree_sklearn     |     3.03486  |       1.11748  |   1.0544   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.592518 |       0.409879 |   0.412323 |
| barab-szabi-1        |     0.597504 |       0.421117 |   0.423333 |
| barab-szabi-2        |     0.593101 |       0.425893 |   0.431038 |
| Bori_Aron_solution-1 |     0.602473 |       0.560307 |   0.565635 |
| k-d_tree_pandas      |     0.591846 |       0.411881 |   0.590482 |
| k-d_tree_sklearn     |     0.595191 |       0.956827 |   1.03109  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.598769 |       0.443908 |   0.436681 |
| k-d_tree_polars      |     0.600269 |       0.444127 |   0.442942 |
| barab-szabi-2        |     0.597266 |       0.426631 |   0.446761 |
| Bori_Aron_solution-1 |     0.594864 |       0.601667 |   0.558431 |
| k-d_tree_pandas      |     0.597815 |       0.421829 |   0.607841 |
| k-d_tree_sklearn     |     0.593811 |       1.02222  |   1.09532  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60558  |       0.500664 |   0.455425 |
| k-d_tree_polars      |     0.591502 |       0.544692 |   0.53676  |
| barab-szabi-1        |     0.593603 |       0.546352 |   0.544897 |
| Bori_Aron_solution-1 |     0.591192 |       0.757628 |   0.573462 |
| k-d_tree_pandas      |     0.59559  |       0.482218 |   0.735873 |
| k-d_tree_sklearn     |     0.605563 |       1.21621  |   1.1337   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590649 |       0.744595 |   0.492108 |
| Bori_Aron_solution-1 |     0.591697 |       1.40493  |   0.594208 |
| k-d_tree_polars      |     0.587561 |       0.898538 |   0.900099 |
| barab-szabi-1        |     0.583312 |       0.871216 |   0.925308 |
| k-d_tree_pandas      |     0.5996   |       0.749169 |   1.18448  |
| k-d_tree_sklearn     |     0.602532 |       2.0564   |   1.20343  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584677 |        5.38516 |   0.76192  |
| Bori_Aron_solution-1 |     0.582284 |       10.6468  |   0.878156 |
| k-d_tree_sklearn     |     0.593546 |       16.1608  |   1.30377  |
| k-d_tree_polars      |     0.589402 |        4.88778 |   6.67079  |
| barab-szabi-1        |     0.597442 |        4.88742 |   6.70397  |
| k-d_tree_pandas      |     0.583103 |        3.82601 |   7.10803  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.828949 |        73.9436 |    3.8748  |
| k-d_tree_sklearn     |     0.691423 |       237.084  |    4.32341 |
| Bori_Aron_solution-1 |     0.579577 |       150.246  |   16.949   |