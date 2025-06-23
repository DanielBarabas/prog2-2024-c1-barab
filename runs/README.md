# 2025-06-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534658 |       0.413944 |   0.416567 |
| k-d_tree_polars      |     0.538426 |       0.397896 |   0.417194 |
| barab-szabi-1        |     0.539054 |       0.401985 |   0.426698 |
| solution-1           |     7.32858  |       1e-06    |   0.442908 |
| Bori_Aron_solution-1 |     0.532336 |       0.533862 |   0.537436 |
| k-d_tree_pandas      |     7.57115  |       0.432557 |   0.710899 |
| k-d_tree_sklearn     |     2.98225  |       1.05944  |   1.03801  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567546 |       0.413399 |   0.414721 |
| k-d_tree_polars      |     0.545991 |       0.402903 |   0.421701 |
| barab-szabi-1        |     0.545969 |       0.410328 |   0.423366 |
| Bori_Aron_solution-1 |     0.539042 |       0.55226  |   0.535914 |
| k-d_tree_pandas      |     0.547809 |       0.384983 |   0.615159 |
| k-d_tree_sklearn     |     0.549282 |       0.960416 |   1.04123  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553106 |       0.434697 |   0.432657 |
| barab-szabi-1        |     0.54973  |       0.435624 |   0.453172 |
| k-d_tree_polars      |     0.546161 |       0.431525 |   0.517903 |
| Bori_Aron_solution-1 |     0.544981 |       0.588016 |   0.539211 |
| k-d_tree_pandas      |     0.545242 |       0.401169 |   0.608159 |
| k-d_tree_sklearn     |     0.550677 |       1.01057  |   1.06622  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547758 |       0.493895 |   0.457853 |
| k-d_tree_polars      |     0.553319 |       0.54074  |   0.545652 |
| barab-szabi-1        |     0.552747 |       0.547094 |   0.559464 |
| Bori_Aron_solution-1 |     0.543837 |       0.768687 |   0.568731 |
| k-d_tree_pandas      |     0.544591 |       0.50441  |   0.728903 |
| k-d_tree_sklearn     |     0.552204 |       1.22907  |   1.11681  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545679 |       0.74361  |   0.490694 |
| Bori_Aron_solution-1 |     0.539979 |       1.388    |   0.579594 |
| k-d_tree_polars      |     0.548598 |       0.871245 |   0.897666 |
| barab-szabi-1        |     0.544629 |       0.87466  |   0.936153 |
| k-d_tree_pandas      |     0.546782 |       0.759861 |   1.16375  |
| k-d_tree_sklearn     |     0.546133 |       2.05538  |   1.19888  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543965 |        5.19649 |   0.717851 |
| Bori_Aron_solution-1 |     0.551667 |       10.6662  |   0.849979 |
| k-d_tree_sklearn     |     0.549723 |       15.9659  |   1.29345  |
| barab-szabi-1        |     0.558704 |        5.02397 |   6.5348   |
| k-d_tree_polars      |     0.54708  |        4.86042 |   6.53502  |
| k-d_tree_pandas      |     0.549253 |        3.92093 |   7.08476  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.692687 |        70.6142 |    2.79188 |
| k-d_tree_sklearn     |     0.617011 |       228.574  |    3.96788 |
| Bori_Aron_solution-1 |     0.54409  |       142.75   |   17.5726  |