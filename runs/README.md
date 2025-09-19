# 2025-09-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.532721 |       0.408055 |   0.428441 |
| k-d_tree_polars      |     0.541219 |       0.415494 |   0.440172 |
| barab-szabi-2        |     8.54518  |       0.775551 |   0.445267 |
| solution-1           |     7.56654  |       1e-06    |   0.463547 |
| Bori_Aron_solution-1 |     0.536949 |       0.554799 |   0.563185 |
| k-d_tree_pandas      |     0.53592  |       0.396732 |   0.577241 |
| k-d_tree_sklearn     |     2.98245  |       1.14469  |   1.05753  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54503  |       0.434479 |   0.428302 |
| barab-szabi-1        |     0.543943 |       0.413966 |   0.433989 |
| k-d_tree_polars      |     0.550986 |       0.413866 |   0.435152 |
| Bori_Aron_solution-1 |     0.543535 |       0.562781 |   0.555237 |
| k-d_tree_pandas      |     0.54628  |       0.416167 |   0.562994 |
| k-d_tree_sklearn     |     0.549968 |       1.00475  |   1.07387  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547259 |       0.437099 |   0.438914 |
| k-d_tree_polars      |     0.553748 |       0.44383  |   0.463105 |
| barab-szabi-1        |     0.559862 |       0.445813 |   0.468165 |
| Bori_Aron_solution-1 |     0.533589 |       0.596768 |   0.58096  |
| k-d_tree_pandas      |     0.556623 |       0.415787 |   0.619725 |
| k-d_tree_sklearn     |     0.59285  |       1.05804  |   1.15775  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550237 |       0.519657 |   0.474655 |
| k-d_tree_polars      |     0.563659 |       0.56295  |   0.575552 |
| barab-szabi-1        |     0.565414 |       0.554956 |   0.583329 |
| Bori_Aron_solution-1 |     0.552716 |       0.790803 |   0.585663 |
| k-d_tree_pandas      |     0.560542 |       0.504592 |   0.763225 |
| k-d_tree_sklearn     |     0.563809 |       1.28843  |   1.1945   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566003 |       0.79935  |   0.561402 |
| Bori_Aron_solution-1 |     0.557537 |       1.48686  |   0.619593 |
| k-d_tree_polars      |     0.562197 |       0.908733 |   0.929906 |
| barab-szabi-1        |     0.553211 |       0.889843 |   0.974662 |
| k-d_tree_pandas      |     0.55759  |       0.770206 |   1.21235  |
| k-d_tree_sklearn     |     0.558851 |       2.2027   |   1.272    |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558268 |        5.28782 |   0.746103 |
| Bori_Aron_solution-1 |     0.541258 |       10.5725  |   0.845433 |
| k-d_tree_sklearn     |     0.546955 |       16.4572  |   1.33197  |
| barab-szabi-1        |     0.548704 |        4.99574 |   6.4685   |
| k-d_tree_polars      |     0.541265 |        5.05777 |   6.69076  |
| k-d_tree_pandas      |     0.542538 |        3.93079 |   6.75953  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548182 |        71.7048 |    2.72892 |
| k-d_tree_sklearn     |     1.16651  |       228.22   |    4.14464 |
| Bori_Aron_solution-1 |     0.540658 |       138.617  |   18.2737  |