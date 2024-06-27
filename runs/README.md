# 2024-06-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.92022  |       1e-06    |   0.348417 |
| barab-szabi-2        |     0.551789 |       0.390572 |   0.378537 |
| barab-szabi-1        |     0.559482 |       0.394854 |   0.390147 |
| k-d_tree_polars      |     0.544296 |       0.439383 |   0.404819 |
| Bori_Aron_solution-1 |     0.567473 |       0.540367 |   0.531913 |
| k-d_tree_pandas      |    10.2013   |       0.396292 |   0.558897 |
| k-d_tree_sklearn     |     3.66849  |       1.0598   |   0.726399 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543455 |       0.385648 |   0.379963 |
| barab-szabi-1        |     0.547555 |       0.401495 |   0.390773 |
| k-d_tree_polars      |     0.571917 |       0.396693 |   0.390863 |
| Bori_Aron_solution-1 |     0.5388   |       0.536606 |   0.511117 |
| k-d_tree_pandas      |     0.569873 |       0.381338 |   0.52026  |
| k-d_tree_sklearn     |     0.552745 |       0.903811 |   0.720771 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555672 |       0.402542 |   0.397076 |
| k-d_tree_polars      |     0.548182 |       0.422456 |   0.423219 |
| barab-szabi-1        |     0.567719 |       0.430286 |   0.448187 |
| Bori_Aron_solution-1 |     0.558489 |       0.58015  |   0.536216 |
| k-d_tree_pandas      |     0.550596 |       0.409831 |   0.568264 |
| k-d_tree_sklearn     |     0.558183 |       0.99225  |   0.763451 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553078 |       0.462731 |   0.426805 |
| k-d_tree_polars      |     0.551164 |       0.529796 |   0.515025 |
| barab-szabi-1        |     0.545722 |       0.537658 |   0.525223 |
| Bori_Aron_solution-1 |     0.543142 |       0.736921 |   0.526971 |
| k-d_tree_pandas      |     0.572585 |       0.48638  |   0.710219 |
| k-d_tree_sklearn     |     0.547371 |       1.16409  |   0.814701 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545641 |       0.747119 |   0.46574  |
| Bori_Aron_solution-1 |     0.540308 |       1.37613  |   0.555682 |
| k-d_tree_polars      |     0.551562 |       0.848774 |   0.876117 |
| barab-szabi-1        |     0.54669  |       0.850223 |   0.901078 |
| k-d_tree_sklearn     |     0.549377 |       1.96333  |   0.904741 |
| k-d_tree_pandas      |     0.548435 |       0.739943 |   1.14159  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563058 |        5.37005 |   0.786801 |
| Bori_Aron_solution-1 |     0.540808 |       10.6892  |   0.867784 |
| k-d_tree_sklearn     |     0.551567 |       16.1753  |   1.08385  |
| k-d_tree_polars      |     0.596153 |        4.91971 |   6.66379  |
| barab-szabi-1        |     0.548193 |        4.86868 |   6.80557  |
| k-d_tree_pandas      |     0.542344 |        3.85206 |   7.18801  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.864031 |        76.3478 |    3.92274 |
| k-d_tree_sklearn     |     0.657541 |       238.693  |    4.57259 |
| Bori_Aron_solution-1 |     0.546465 |       152.297  |   17.6971  |