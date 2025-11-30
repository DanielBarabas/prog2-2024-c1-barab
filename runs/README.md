# 2025-11-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.531897 |       0.407315 |   0.430047 |
| barab-szabi-2        |     0.517115 |       0.498418 |   0.433172 |
| barab-szabi-1        |     0.537597 |       0.424088 |   0.434895 |
| solution-1           |     7.37572  |       1e-06    |   0.449015 |
| Bori_Aron_solution-1 |     0.526616 |       0.54024  |   0.547683 |
| k-d_tree_pandas      |     8.18595  |       0.417506 |   1.02157  |
| k-d_tree_sklearn     |     3.12506  |       1.1644   |   1.06305  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53758  |       0.432413 |   0.433795 |
| barab-szabi-1        |     0.551567 |       0.413663 |   0.439937 |
| k-d_tree_polars      |     0.531014 |       0.414429 |   0.444783 |
| Bori_Aron_solution-1 |     0.519498 |       0.552861 |   0.545932 |
| k-d_tree_pandas      |     0.538419 |       0.405358 |   0.563178 |
| k-d_tree_sklearn     |     0.544853 |       0.972049 |   1.06961  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530088 |       0.441955 |   0.44477  |
| k-d_tree_polars      |     0.530393 |       0.447551 |   0.462471 |
| barab-szabi-1        |     0.536965 |       0.445509 |   0.465346 |
| Bori_Aron_solution-1 |     0.525624 |       0.598738 |   0.550299 |
| k-d_tree_pandas      |     0.531954 |       0.418635 |   0.607314 |
| k-d_tree_sklearn     |     0.538543 |       1.01139  |   1.10721  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533426 |       0.508548 |   0.481129 |
| k-d_tree_polars      |     0.531753 |       0.562649 |   0.556674 |
| Bori_Aron_solution-1 |     0.522161 |       0.785382 |   0.564536 |
| barab-szabi-1        |     0.52936  |       0.556446 |   0.570271 |
| k-d_tree_pandas      |     0.528304 |       0.506148 |   0.732667 |
| k-d_tree_sklearn     |     0.531863 |       1.25271  |   1.13652  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5321   |       0.755405 |   0.503667 |
| Bori_Aron_solution-1 |     0.523107 |       1.45558  |   0.588443 |
| k-d_tree_polars      |     0.531102 |       0.922196 |   0.90961  |
| barab-szabi-1        |     0.541666 |       0.916851 |   0.937681 |
| k-d_tree_pandas      |     0.533745 |       0.819289 |   1.17261  |
| k-d_tree_sklearn     |     0.53299  |       2.10029  |   1.22152  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533791 |        5.27291 |   0.739532 |
| Bori_Aron_solution-1 |     0.526109 |       11.0181  |   0.842583 |
| k-d_tree_sklearn     |     0.538966 |       16.54    |   1.32184  |
| barab-szabi-1        |     0.53425  |        5.3886  |   6.50728  |
| k-d_tree_polars      |     0.536875 |        5.42955 |   6.57911  |
| k-d_tree_pandas      |     0.539615 |        4.43229 |   6.97284  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527021 |        75.9381 |    2.68129 |
| k-d_tree_sklearn     |     0.549976 |       231.27   |    4.38431 |
| Bori_Aron_solution-1 |     0.726139 |       153.095  |   16.6339  |