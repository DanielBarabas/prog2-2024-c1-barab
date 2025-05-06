# 2025-05-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.518234 |       0.427953 |   0.413878 |
| barab-szabi-2        |     0.516132 |       0.416931 |   0.418078 |
| k-d_tree_polars      |     7.96319  |       0.504434 |   0.508873 |
| solution-1           |     7.67055  |       1e-06    |   0.531978 |
| Bori_Aron_solution-1 |     0.514291 |       0.551228 |   0.557106 |
| k-d_tree_pandas      |     0.519298 |       0.389916 |   0.571656 |
| k-d_tree_sklearn     |     3.06588  |       1.00524  |   1.0526   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54374  |       0.417078 |   0.41789  |
| k-d_tree_polars      |     0.531948 |       0.437164 |   0.41932  |
| barab-szabi-1        |     0.533832 |       0.410398 |   0.424017 |
| Bori_Aron_solution-1 |     0.529412 |       0.568552 |   0.549299 |
| k-d_tree_pandas      |     0.538708 |       0.393694 |   0.568917 |
| k-d_tree_sklearn     |     0.53453  |       0.960493 |   1.07045  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532271 |       0.442139 |   0.434361 |
| k-d_tree_polars      |     0.547054 |       0.445944 |   0.452417 |
| barab-szabi-1        |     0.539815 |       0.452642 |   0.463121 |
| Bori_Aron_solution-1 |     0.523156 |       0.618443 |   0.568147 |
| k-d_tree_pandas      |     0.567722 |       0.413569 |   0.602073 |
| k-d_tree_sklearn     |     0.538559 |       1.02639  |   1.06989  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530676 |       0.493929 |   0.466085 |
| k-d_tree_polars      |     0.522762 |       0.552276 |   0.550375 |
| barab-szabi-1        |     0.534806 |       0.554768 |   0.558056 |
| Bori_Aron_solution-1 |     0.524428 |       0.776986 |   0.564276 |
| k-d_tree_pandas      |     0.528932 |       0.487131 |   0.733543 |
| k-d_tree_sklearn     |     0.536239 |       1.25199  |   1.13545  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523986 |       0.733181 |   0.488152 |
| Bori_Aron_solution-1 |     0.515774 |       1.4301   |   0.58871  |
| k-d_tree_polars      |     0.53051  |       0.899213 |   0.907808 |
| barab-szabi-1        |     0.522397 |       0.886242 |   0.945573 |
| k-d_tree_pandas      |     0.530562 |       0.763044 |   1.18755  |
| k-d_tree_sklearn     |     0.523975 |       2.11928  |   1.23473  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528926 |        5.40429 |   0.751348 |
| Bori_Aron_solution-1 |     0.514742 |       10.727   |   0.889423 |
| k-d_tree_sklearn     |     0.54604  |       16.7451  |   1.34107  |
| barab-szabi-1        |     0.516528 |        5.07394 |   6.65749  |
| k-d_tree_polars      |     0.521697 |        5.05444 |   6.68318  |
| k-d_tree_pandas      |     0.531482 |        3.98078 |   7.1038   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.839953 |       235.852  |    4.32283 |
| barab-szabi-2        |     0.51751  |        82.3882 |    4.82587 |
| Bori_Aron_solution-1 |     0.548104 |       148.337  |   17.5841  |