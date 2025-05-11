# 2025-05-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.66404  |       1e-06    |   0.379941 |
| k-d_tree_polars      |     4.12861  |       0.423976 |   0.430346 |
| barab-szabi-2        |     0.548362 |       0.461246 |   0.444567 |
| barab-szabi-1        |     0.529646 |       0.438037 |   0.444861 |
| Bori_Aron_solution-1 |     4.47318  |       0.784577 |   0.523468 |
| k-d_tree_pandas      |     0.530157 |       0.435983 |   0.59711  |
| k-d_tree_sklearn     |     3.01786  |       1.19611  |   1.10965  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544725 |       0.444278 |   0.432229 |
| k-d_tree_polars      |     0.548501 |       0.434106 |   0.459831 |
| barab-szabi-1        |     0.543782 |       0.438685 |   0.481712 |
| k-d_tree_pandas      |     0.546051 |       0.399502 |   0.580364 |
| Bori_Aron_solution-1 |     0.542469 |       0.629694 |   0.586111 |
| k-d_tree_sklearn     |     0.559937 |       1.06495  |   1.11595  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55906  |       0.435514 |   0.443957 |
| k-d_tree_polars      |     0.535577 |       0.462189 |   0.467406 |
| barab-szabi-1        |     0.572806 |       0.470679 |   0.470886 |
| Bori_Aron_solution-1 |     0.552635 |       0.626376 |   0.595706 |
| k-d_tree_pandas      |     0.554585 |       0.441371 |   0.627002 |
| k-d_tree_sklearn     |     0.555813 |       1.10531  |   1.18187  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548025 |       0.506989 |   0.480727 |
| k-d_tree_polars      |     0.572382 |       0.588165 |   0.571428 |
| barab-szabi-1        |     0.566962 |       0.581082 |   0.578631 |
| Bori_Aron_solution-1 |     0.542032 |       0.807812 |   0.600856 |
| k-d_tree_pandas      |     0.556037 |       0.522208 |   0.782379 |
| k-d_tree_sklearn     |     0.56707  |       1.33176  |   1.19822  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547398 |       0.77149  |   0.536608 |
| Bori_Aron_solution-1 |     0.544803 |       1.46149  |   0.618109 |
| k-d_tree_polars      |     0.55583  |       0.916649 |   0.955462 |
| barab-szabi-1        |     0.569749 |       0.913692 |   0.985202 |
| k-d_tree_pandas      |     0.546508 |       0.792945 |   1.23042  |
| k-d_tree_sklearn     |     0.552545 |       2.21951  |   1.35482  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578058 |        6.00559 |   0.803344 |
| Bori_Aron_solution-1 |     0.528877 |       11.2526  |   0.918583 |
| k-d_tree_sklearn     |     0.545375 |       18.3923  |   1.40691  |
| barab-szabi-1        |     0.556106 |        5.06381 |   7.10474  |
| k-d_tree_polars      |     0.549114 |        5.0917  |   7.35905  |
| k-d_tree_pandas      |     0.533919 |        3.94777 |   7.75282  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.651816 |        77.7565 |    2.98954 |
| k-d_tree_sklearn     |     0.791004 |       247.436  |    4.62139 |
| Bori_Aron_solution-1 |     0.556863 |       161.399  |   16.0106  |