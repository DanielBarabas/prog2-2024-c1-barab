# 2025-12-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52877  |       0.475054 |   0.436308 |
| k-d_tree_polars      |     0.53195  |       0.405263 |   0.438441 |
| barab-szabi-1        |     0.547507 |       0.413971 |   0.44154  |
| solution-1           |     7.71078  |       1e-06    |   0.451457 |
| Bori_Aron_solution-1 |     0.586599 |       0.556646 |   0.554933 |
| k-d_tree_pandas      |     8.51107  |       0.421031 |   0.652095 |
| k-d_tree_sklearn     |     3.25631  |       1.14297  |   1.10389  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531477 |       0.439169 |   0.435869 |
| k-d_tree_polars      |     0.533619 |       0.413502 |   0.43623  |
| barab-szabi-1        |     0.534508 |       0.417777 |   0.44118  |
| Bori_Aron_solution-1 |     0.520831 |       0.59541  |   0.550762 |
| k-d_tree_pandas      |     0.544877 |       0.396026 |   0.564253 |
| k-d_tree_sklearn     |     0.535733 |       0.981743 |   1.07854  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53239  |       0.444059 |   0.449311 |
| barab-szabi-1        |     0.534357 |       0.438935 |   0.464405 |
| k-d_tree_polars      |     0.532179 |       0.442114 |   0.471876 |
| Bori_Aron_solution-1 |     0.525215 |       0.602746 |   0.558389 |
| k-d_tree_pandas      |     0.529758 |       0.413671 |   0.605417 |
| k-d_tree_sklearn     |     0.539829 |       1.02414  |   1.09193  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531378 |       0.508107 |   0.479103 |
| Bori_Aron_solution-1 |     0.542936 |       0.800283 |   0.571945 |
| k-d_tree_polars      |     0.536475 |       0.57219  |   0.575678 |
| barab-szabi-1        |     0.545264 |       0.570293 |   0.579832 |
| k-d_tree_pandas      |     0.526318 |       0.507742 |   0.748091 |
| k-d_tree_sklearn     |     0.544322 |       1.32825  |   1.17462  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.54659  |       1.47979  |   0.594454 |
| barab-szabi-2        |     0.570256 |       0.78773  |   0.664376 |
| k-d_tree_polars      |     0.533178 |       0.921742 |   0.929889 |
| barab-szabi-1        |     0.537919 |       0.941581 |   0.976687 |
| k-d_tree_pandas      |     0.552407 |       0.847127 |   1.26737  |
| k-d_tree_sklearn     |     0.558351 |       2.22486  |   1.27561  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537798 |        5.53312 |   0.784965 |
| Bori_Aron_solution-1 |     0.527047 |       11.3593  |   0.856428 |
| k-d_tree_sklearn     |     0.543673 |       17.2006  |   1.31938  |
| barab-szabi-1        |     0.533761 |        5.49868 |   6.77695  |
| k-d_tree_polars      |     0.528764 |        5.41985 |   6.87584  |
| k-d_tree_pandas      |     0.528907 |        4.49227 |   7.34209  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5375   |        82.8392 |    2.82757 |
| k-d_tree_sklearn     |     0.542568 |       244.47   |    4.36899 |
| Bori_Aron_solution-1 |     0.67935  |       157.329  |   18.028   |