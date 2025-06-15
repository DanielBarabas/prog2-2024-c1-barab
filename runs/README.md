# 2025-06-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.68823  |       1e-06    |   0.392015 |
| k-d_tree_polars      |     0.532088 |       0.393687 |   0.412385 |
| barab-szabi-2        |     0.58088  |       0.476737 |   0.416295 |
| barab-szabi-1        |     0.526295 |       0.395002 |   0.426313 |
| Bori_Aron_solution-1 |     0.530913 |       0.532752 |   0.533671 |
| k-d_tree_pandas      |     8.33169  |       0.43408  |   0.628598 |
| k-d_tree_sklearn     |     3.23224  |       1.04085  |   1.02697  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546594 |       0.418236 |   0.417211 |
| k-d_tree_polars      |     0.54665  |       0.40035  |   0.417568 |
| barab-szabi-1        |     0.545748 |       0.400957 |   0.417648 |
| Bori_Aron_solution-1 |     0.536183 |       0.538702 |   0.533397 |
| k-d_tree_pandas      |     0.542658 |       0.379356 |   0.542507 |
| k-d_tree_sklearn     |     0.548968 |       0.963269 |   1.03184  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547877 |       0.422461 |   0.429999 |
| k-d_tree_polars      |     0.552274 |       0.427479 |   0.441607 |
| barab-szabi-1        |     0.542993 |       0.42465  |   0.444016 |
| Bori_Aron_solution-1 |     0.537645 |       0.579822 |   0.534543 |
| k-d_tree_pandas      |     0.544451 |       0.400119 |   0.583305 |
| k-d_tree_sklearn     |     0.550593 |       1.00084  |   1.05469  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545233 |       0.490257 |   0.457432 |
| k-d_tree_polars      |     0.546057 |       0.538939 |   0.541797 |
| Bori_Aron_solution-1 |     0.536303 |       0.755298 |   0.549611 |
| barab-szabi-1        |     0.547135 |       0.539486 |   0.55155  |
| k-d_tree_pandas      |     0.54962  |       0.481648 |   0.725461 |
| k-d_tree_sklearn     |     0.546873 |       1.22318  |   1.11838  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562593 |       0.729342 |   0.488085 |
| Bori_Aron_solution-1 |     0.539526 |       1.38496  |   0.575424 |
| k-d_tree_polars      |     0.540542 |       0.863468 |   0.882775 |
| barab-szabi-1        |     0.543349 |       0.875109 |   0.924757 |
| k-d_tree_pandas      |     0.54765  |       0.751224 |   1.15226  |
| k-d_tree_sklearn     |     0.54916  |       2.04515  |   1.18097  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55178  |        5.2368  |   0.73115  |
| Bori_Aron_solution-1 |     0.540757 |       10.4636  |   0.829028 |
| k-d_tree_sklearn     |     0.550881 |       15.7974  |   1.30083  |
| k-d_tree_polars      |     0.545676 |        4.91761 |   6.48885  |
| barab-szabi-1        |     0.550971 |        4.94685 |   6.51464  |
| k-d_tree_pandas      |     0.545173 |        3.94278 |   6.90919  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.72237  |        72.4685 |    2.78482 |
| k-d_tree_sklearn     |     0.613141 |       230.789  |    3.84996 |
| Bori_Aron_solution-1 |     0.541186 |       140.742  |   16.9097  |