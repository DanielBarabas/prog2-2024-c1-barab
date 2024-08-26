# 2024-08-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.602577 |       0.395665 |   0.381818 |
| barab-szabi-2        |     8.15732  |       0.588442 |   0.386326 |
| barab-szabi-1        |     0.598765 |       0.407103 |   0.399801 |
| solution-1           |     7.95765  |       1e-06    |   0.445563 |
| Bori_Aron_solution-1 |     0.611045 |       0.529471 |   0.519242 |
| k-d_tree_pandas      |     0.601007 |       0.441597 |   0.535828 |
| k-d_tree_sklearn     |     3.17613  |       0.989312 |   0.713934 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611411 |       0.387278 |   0.381752 |
| k-d_tree_polars      |     0.611956 |       0.399796 |   0.388078 |
| barab-szabi-1        |     0.61158  |       0.400907 |   0.396385 |
| Bori_Aron_solution-1 |     0.613795 |       0.535692 |   0.529076 |
| k-d_tree_pandas      |     0.607984 |       0.386646 |   0.554094 |
| k-d_tree_sklearn     |     0.634325 |       0.898784 |   0.728771 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621823 |       0.409459 |   0.410624 |
| k-d_tree_polars      |     0.621959 |       0.435927 |   0.419836 |
| barab-szabi-1        |     0.609026 |       0.437012 |   0.42881  |
| Bori_Aron_solution-1 |     0.608448 |       0.58147  |   0.540482 |
| k-d_tree_pandas      |     0.624482 |       0.407169 |   0.586249 |
| k-d_tree_sklearn     |     0.621725 |       0.96652  |   0.749634 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622607 |       0.468417 |   0.43602  |
| k-d_tree_polars      |     0.624751 |       0.557956 |   0.530171 |
| barab-szabi-1        |     0.621786 |       0.539512 |   0.539186 |
| Bori_Aron_solution-1 |     0.610745 |       0.750548 |   0.553836 |
| k-d_tree_pandas      |     0.622572 |       0.474739 |   0.715498 |
| k-d_tree_sklearn     |     0.650384 |       1.21766  |   0.797016 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611987 |       0.740535 |   0.473958 |
| Bori_Aron_solution-1 |     0.611438 |       1.40518  |   0.571567 |
| k-d_tree_polars      |     0.620374 |       0.866399 |   0.881198 |
| k-d_tree_sklearn     |     0.629993 |       2.02337  |   0.883164 |
| barab-szabi-1        |     0.620651 |       0.859976 |   0.944203 |
| k-d_tree_pandas      |     0.624245 |       0.753769 |   1.16728  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615393 |        5.75655 |   0.755078 |
| Bori_Aron_solution-1 |     0.602642 |       11.1126  |   0.854271 |
| k-d_tree_sklearn     |     0.635109 |       16.2605  |   0.98673  |
| barab-szabi-1        |     0.617462 |        4.84792 |   6.67154  |
| k-d_tree_polars      |     0.624192 |        4.90873 |   6.70566  |
| k-d_tree_pandas      |     0.629109 |        3.9159  |   6.94326  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.64006  |        76.5177 |    2.93217 |
| k-d_tree_sklearn     |     0.658107 |       238.834  |    3.89763 |
| Bori_Aron_solution-1 |     0.709379 |       150.774  |   17.6588  |