# 2025-09-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522722 |       0.572205 |   0.419348 |
| barab-szabi-1        |     0.557481 |       0.40488  |   0.42329  |
| k-d_tree_polars      |     0.536328 |       0.403378 |   0.426698 |
| solution-1           |     7.5738   |       1e-06    |   0.463513 |
| Bori_Aron_solution-1 |     0.530519 |       0.555527 |   0.54243  |
| k-d_tree_pandas      |     8.41768  |       0.402577 |   0.719629 |
| k-d_tree_sklearn     |     3.14234  |       1.09665  |   1.04823  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537474 |       0.419827 |   0.420265 |
| k-d_tree_polars      |     0.538022 |       0.406534 |   0.42509  |
| barab-szabi-1        |     0.535548 |       0.407615 |   0.427925 |
| Bori_Aron_solution-1 |     0.532254 |       0.548498 |   0.540239 |
| k-d_tree_pandas      |     0.53803  |       0.388705 |   0.551011 |
| k-d_tree_sklearn     |     0.5396   |       0.961254 |   1.05347  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5347   |       0.431205 |   0.435365 |
| k-d_tree_polars      |     0.533111 |       0.433408 |   0.457318 |
| barab-szabi-1        |     0.536277 |       0.431018 |   0.459053 |
| Bori_Aron_solution-1 |     0.533587 |       0.582883 |   0.543854 |
| k-d_tree_pandas      |     0.538893 |       0.401646 |   0.599669 |
| k-d_tree_sklearn     |     0.542333 |       0.997054 |   1.08127  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535776 |       0.496231 |   0.46248  |
| k-d_tree_polars      |     0.539613 |       0.543596 |   0.549634 |
| Bori_Aron_solution-1 |     0.5337   |       0.753572 |   0.557389 |
| barab-szabi-1        |     0.53957  |       0.542951 |   0.562833 |
| k-d_tree_pandas      |     0.543106 |       0.486629 |   0.730094 |
| k-d_tree_sklearn     |     0.550944 |       1.22941  |   1.11088  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538641 |       0.736852 |   0.495263 |
| Bori_Aron_solution-1 |     0.533971 |       1.3752   |   0.582328 |
| k-d_tree_polars      |     0.537672 |       0.885104 |   0.892322 |
| barab-szabi-1        |     0.537554 |       0.878731 |   0.928677 |
| k-d_tree_pandas      |     0.53534  |       0.760161 |   1.15314  |
| k-d_tree_sklearn     |     0.539366 |       2.03238  |   1.20605  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538874 |        5.0795  |   0.732929 |
| Bori_Aron_solution-1 |     0.533485 |       10.3773  |   0.837527 |
| k-d_tree_sklearn     |     0.540908 |       15.5866  |   1.29454  |
| barab-szabi-1        |     0.540088 |        4.94687 |   6.37196  |
| k-d_tree_polars      |     0.542494 |        5.04341 |   6.37233  |
| k-d_tree_pandas      |     0.5379   |        3.93918 |   6.79192  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533988 |        71.5651 |    2.70785 |
| k-d_tree_sklearn     |     0.550433 |       236.545  |    4.06142 |
| Bori_Aron_solution-1 |     0.777035 |       138.735  |   18.3681  |