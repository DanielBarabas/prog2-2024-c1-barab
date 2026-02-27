# 2026-02-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483407 |       0.439644 |   0.435944 |
| k-d_tree_polars      |     0.499509 |       0.424015 |   0.480228 |
| solution-1           |     8.01554  |       1e-06    |   0.51493  |
| k-d_tree_pandas      |     0.500569 |       0.40396  |   0.577408 |
| Bori_Aron_solution-1 |     0.473699 |       0.562554 |   0.578607 |
| barab-szabi-1        |     8.53802  |       0.486834 |   0.591136 |
| k-d_tree_sklearn     |     3.09339  |       1.25187  |   1.08529  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.502702 |       0.436456 |   0.43336  |
| k-d_tree_polars      |     0.491293 |       0.4076   |   0.446982 |
| barab-szabi-1        |     0.504082 |       0.425132 |   0.467579 |
| Bori_Aron_solution-1 |     0.484423 |       0.559274 |   0.545428 |
| k-d_tree_pandas      |     0.507594 |       0.38891  |   0.560309 |
| k-d_tree_sklearn     |     0.492703 |       0.967964 |   1.05798  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491423 |       0.444788 |   0.445696 |
| barab-szabi-1        |     0.491837 |       0.437338 |   0.469477 |
| k-d_tree_polars      |     0.487057 |       0.453438 |   0.47058  |
| Bori_Aron_solution-1 |     0.496041 |       0.597791 |   0.554808 |
| k-d_tree_pandas      |     0.490041 |       0.407648 |   0.61389  |
| k-d_tree_sklearn     |     0.491696 |       1.01631  |   1.08503  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492557 |       0.503238 |   0.473554 |
| k-d_tree_polars      |     0.514641 |       0.565825 |   0.563242 |
| Bori_Aron_solution-1 |     0.484874 |       0.781521 |   0.573207 |
| barab-szabi-1        |     0.488285 |       0.561106 |   0.587728 |
| k-d_tree_pandas      |     0.490002 |       0.504482 |   0.743275 |
| k-d_tree_sklearn     |     0.494021 |       1.27564  |   1.13697  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492149 |       0.725881 |   0.502247 |
| Bori_Aron_solution-1 |     0.480393 |       1.48062  |   0.597655 |
| k-d_tree_polars      |     0.507725 |       0.936923 |   0.941401 |
| barab-szabi-1        |     0.488811 |       0.941181 |   0.968548 |
| k-d_tree_pandas      |     0.493977 |       0.823705 |   1.19107  |
| k-d_tree_sklearn     |     0.496796 |       2.20539  |   1.24192  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490031 |        4.97018 |   0.735883 |
| Bori_Aron_solution-1 |     0.482658 |       10.7775  |   0.814768 |
| k-d_tree_sklearn     |     0.493441 |       16.2135  |   1.29751  |
| k-d_tree_polars      |     0.489181 |        5.49216 |   6.3933   |
| barab-szabi-1        |     0.495685 |        5.57737 |   6.4073   |
| k-d_tree_pandas      |     0.489454 |        4.44622 |   6.80062  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485444 |        70.5258 |    2.5828  |
| k-d_tree_sklearn     |     0.820459 |       229.022  |    3.92162 |
| Bori_Aron_solution-1 |     0.500884 |       147.237  |   14.3815  |