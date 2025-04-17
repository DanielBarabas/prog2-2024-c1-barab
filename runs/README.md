# 2025-04-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57123  |       0.425301 |   0.429823 |
| k-d_tree_polars      |     0.572766 |       0.423301 |   0.436    |
| barab-szabi-1        |     0.577168 |       0.481941 |   0.49898  |
| Bori_Aron_solution-1 |     0.565563 |       0.57678  |   0.572149 |
| solution-1           |     7.59287  |       1e-06    |   0.77241  |
| k-d_tree_pandas      |     7.7899   |       0.51747  |   0.898446 |
| k-d_tree_sklearn     |     3.07801  |       1.54627  |   1.07936  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582857 |       0.442935 |   0.428942 |
| k-d_tree_polars      |     0.590528 |       0.438629 |   0.430545 |
| barab-szabi-1        |     0.593713 |       0.438557 |   0.434621 |
| Bori_Aron_solution-1 |     0.58669  |       0.597598 |   0.576682 |
| k-d_tree_pandas      |     0.589498 |       0.414127 |   0.588253 |
| k-d_tree_sklearn     |     0.595586 |       1.02542  |   1.09522  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600711 |       0.449867 |   0.445799 |
| barab-szabi-1        |     0.606855 |       0.467014 |   0.468623 |
| k-d_tree_polars      |     0.589256 |       0.466608 |   0.50987  |
| Bori_Aron_solution-1 |     0.581014 |       0.6229   |   0.627386 |
| k-d_tree_pandas      |     0.587646 |       0.43171  |   0.664462 |
| k-d_tree_sklearn     |     0.595624 |       1.08628  |   1.14593  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589703 |       0.517954 |   0.490444 |
| barab-szabi-1        |     0.595879 |       0.571861 |   0.571821 |
| k-d_tree_polars      |     0.598908 |       0.587646 |   0.574254 |
| Bori_Aron_solution-1 |     0.58612  |       0.813761 |   0.611223 |
| k-d_tree_pandas      |     0.593318 |       0.512418 |   0.778871 |
| k-d_tree_sklearn     |     0.608897 |       1.32647  |   1.21467  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593981 |       0.768765 |   0.54307  |
| Bori_Aron_solution-1 |     0.584781 |       1.47288  |   0.632238 |
| k-d_tree_polars      |     0.595535 |       0.912065 |   0.947516 |
| barab-szabi-1        |     0.591975 |       0.911245 |   0.991608 |
| k-d_tree_pandas      |     0.594595 |       0.787454 |   1.23624  |
| k-d_tree_sklearn     |     0.587073 |       2.19696  |   1.28865  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.59518  |        5.58598 |   0.742375 |
| Bori_Aron_solution-1 |     0.584972 |       11.1365  |   0.898572 |
| k-d_tree_sklearn     |     0.599332 |       17.4429  |   1.36712  |
| k-d_tree_polars      |     0.583153 |        5.0971  |   6.90746  |
| barab-szabi-1        |     0.591854 |        5.10858 |   6.94365  |
| k-d_tree_pandas      |     0.587381 |        4.0164  |   7.35847  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.756421 |        73.2064 |    3.14691 |
| k-d_tree_sklearn     |     0.6431   |       235.133  |    4.31445 |
| Bori_Aron_solution-1 |     0.581965 |       154.327  |   12.3627  |