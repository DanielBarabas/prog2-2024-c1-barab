# 2024-11-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.664099 |       0.397167 |   0.387634 |
| barab-szabi-2        |     0.613406 |       0.394406 |   0.391795 |
| k-d_tree_polars      |     0.609839 |       0.394568 |   0.460416 |
| Bori_Aron_solution-1 |     0.603303 |       0.511571 |   0.509397 |
| k-d_tree_pandas      |     0.610054 |       0.374992 |   0.520792 |
| solution-1           |     8.5584   |       1e-06    |   0.670319 |
| k-d_tree_sklearn     |    10.4756   |       1.4992   |   1.01729  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612365 |       0.39654  |   0.389459 |
| barab-szabi-1        |     0.624683 |       0.416667 |   0.394725 |
| k-d_tree_polars      |     0.611265 |       0.402478 |   0.397015 |
| Bori_Aron_solution-1 |     0.608363 |       0.543319 |   0.531507 |
| k-d_tree_pandas      |     0.610364 |       0.381994 |   0.541323 |
| k-d_tree_sklearn     |     0.618058 |       0.940666 |   0.950037 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633487 |       0.404721 |   0.400572 |
| barab-szabi-1        |     0.655949 |       0.428761 |   0.422881 |
| k-d_tree_polars      |     0.639201 |       0.450565 |   0.429718 |
| Bori_Aron_solution-1 |     0.609753 |       0.561346 |   0.517105 |
| k-d_tree_pandas      |     0.634669 |       0.404182 |   0.572839 |
| k-d_tree_sklearn     |     0.620872 |       0.931769 |   0.997168 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609044 |       0.468535 |   0.429699 |
| k-d_tree_polars      |     0.608477 |       0.530335 |   0.519878 |
| barab-szabi-1        |     0.61324  |       0.533065 |   0.5261   |
| Bori_Aron_solution-1 |     0.61154  |       0.75406  |   0.547156 |
| k-d_tree_pandas      |     0.618738 |       0.480471 |   0.702019 |
| k-d_tree_sklearn     |     0.66305  |       1.16063  |   1.03965  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614225 |       0.713362 |   0.462573 |
| Bori_Aron_solution-1 |     0.603514 |       1.37854  |   0.558409 |
| k-d_tree_polars      |     0.614576 |       0.914149 |   0.869327 |
| barab-szabi-1        |     0.611335 |       0.862894 |   0.905522 |
| k-d_tree_sklearn     |     0.622933 |       1.98449  |   1.12368  |
| k-d_tree_pandas      |     0.609292 |       0.748052 |   1.13421  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612831 |        5.47192 |   0.760146 |
| Bori_Aron_solution-1 |     0.602778 |       10.6205  |   0.805417 |
| k-d_tree_sklearn     |     0.614484 |       15.8687  |   1.24109  |
| barab-szabi-1        |     0.614778 |        4.80886 |   6.49342  |
| k-d_tree_polars      |     0.612613 |        4.87838 |   6.52458  |
| k-d_tree_pandas      |     0.611855 |        3.85832 |   6.83159  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62716  |        72.3925 |    2.95374 |
| k-d_tree_sklearn     |     0.613856 |       227.801  |    4.14742 |
| Bori_Aron_solution-1 |     0.63096  |       145.588  |   18.4859  |