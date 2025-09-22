# 2025-09-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.70861  |       0.973204 |   0.425583 |
| barab-szabi-1        |     0.522185 |       0.399389 |   0.42801  |
| k-d_tree_polars      |     0.529383 |       0.401263 |   0.428462 |
| Bori_Aron_solution-1 |     0.518271 |       0.542398 |   0.539855 |
| k-d_tree_pandas      |     0.537993 |       0.384359 |   0.552321 |
| solution-1           |     7.3704   |       1e-06    |   0.656707 |
| k-d_tree_sklearn     |     2.97011  |       1.34163  |   1.05228  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537606 |       0.433439 |   0.422647 |
| k-d_tree_polars      |     0.541    |       0.40924  |   0.430216 |
| barab-szabi-1        |     0.540849 |       0.406267 |   0.43122  |
| Bori_Aron_solution-1 |     0.530952 |       0.557321 |   0.543402 |
| k-d_tree_pandas      |     0.536705 |       0.392421 |   0.5504   |
| k-d_tree_sklearn     |     0.544946 |       0.96379  |   1.05421  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534641 |       0.436884 |   0.446363 |
| barab-szabi-1        |     0.54196  |       0.437992 |   0.459747 |
| k-d_tree_polars      |     0.542879 |       0.435991 |   0.464418 |
| Bori_Aron_solution-1 |     0.536876 |       0.583249 |   0.544953 |
| k-d_tree_pandas      |     0.539782 |       0.403502 |   0.602227 |
| k-d_tree_sklearn     |     0.541278 |       1.00566  |   1.08711  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554916 |       0.503685 |   0.464809 |
| k-d_tree_polars      |     0.543394 |       0.563785 |   0.552594 |
| barab-szabi-1        |     0.539098 |       0.552939 |   0.560602 |
| Bori_Aron_solution-1 |     0.530639 |       0.770416 |   0.56993  |
| k-d_tree_pandas      |     0.541298 |       0.481183 |   0.734113 |
| k-d_tree_sklearn     |     0.542645 |       1.24147  |   1.11796  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536178 |       0.747482 |   0.499999 |
| Bori_Aron_solution-1 |     0.531729 |       1.42142  |   0.587676 |
| k-d_tree_polars      |     0.538851 |       0.884913 |   0.908462 |
| barab-szabi-1        |     0.536862 |       0.894533 |   0.949172 |
| k-d_tree_pandas      |     0.539269 |       0.762956 |   1.17407  |
| k-d_tree_sklearn     |     0.542647 |       2.07086  |   1.20957  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536126 |        5.21645 |   0.750159 |
| Bori_Aron_solution-1 |     0.533428 |       10.6334  |   0.844213 |
| k-d_tree_sklearn     |     0.539173 |       16.3321  |   1.31994  |
| k-d_tree_polars      |     0.536588 |        5.04064 |   6.59822  |
| barab-szabi-1        |     0.540757 |        5.0462  |   6.61289  |
| k-d_tree_pandas      |     0.537813 |        3.93563 |   6.93621  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542489 |        72.8913 |    2.81726 |
| k-d_tree_sklearn     |     1.18292  |       234.64   |    4.14235 |
| Bori_Aron_solution-1 |     0.544734 |       140.465  |   18.0738  |