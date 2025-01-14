# 2025-01-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574246 |       0.42718  |   0.398741 |
| k-d_tree_polars      |     0.596191 |       0.399807 |   0.400876 |
| barab-szabi-1        |     0.575982 |       0.397536 |   0.401921 |
| solution-1           |     7.70263  |       1e-06    |   0.422467 |
| Bori_Aron_solution-1 |     0.582696 |       0.539063 |   0.545324 |
| k-d_tree_pandas      |     7.95196  |       0.398485 |   0.564994 |
| k-d_tree_sklearn     |     3.24085  |       1.16216  |   1.01517  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587856 |       0.409629 |   0.401122 |
| k-d_tree_polars      |     0.598529 |       0.412573 |   0.409377 |
| barab-szabi-1        |     0.593932 |       0.409582 |   0.413882 |
| Bori_Aron_solution-1 |     0.583447 |       0.552484 |   0.533762 |
| k-d_tree_pandas      |     0.587389 |       0.392844 |   0.54928  |
| k-d_tree_sklearn     |     0.595284 |       0.956396 |   1.03087  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586444 |       0.418421 |   0.413405 |
| k-d_tree_polars      |     0.591631 |       0.436763 |   0.430249 |
| barab-szabi-1        |     0.590777 |       0.436423 |   0.443429 |
| Bori_Aron_solution-1 |     0.585767 |       0.597554 |   0.538241 |
| k-d_tree_pandas      |     0.59116  |       0.405676 |   0.589374 |
| k-d_tree_sklearn     |     0.60813  |       0.995138 |   1.06087  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591555 |       0.493707 |   0.445652 |
| k-d_tree_polars      |     0.586163 |       0.534363 |   0.532224 |
| barab-szabi-1        |     0.591708 |       0.545976 |   0.536999 |
| Bori_Aron_solution-1 |     0.58172  |       0.751392 |   0.548858 |
| k-d_tree_pandas      |     0.605616 |       0.47997  |   0.746423 |
| k-d_tree_sklearn     |     0.592524 |       1.2017   |   1.1068   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589091 |       0.711146 |   0.484353 |
| Bori_Aron_solution-1 |     0.584442 |       1.38195  |   0.58394  |
| k-d_tree_polars      |     0.591131 |       0.856596 |   0.879107 |
| barab-szabi-1        |     0.584016 |       0.85911  |   0.917558 |
| k-d_tree_pandas      |     0.586802 |       0.74384  |   1.16655  |
| k-d_tree_sklearn     |     0.595348 |       2.02768  |   1.20206  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588636 |        5.1977  |   0.73846  |
| Bori_Aron_solution-1 |     0.586446 |       10.4646  |   0.869842 |
| k-d_tree_sklearn     |     0.596418 |       15.8006  |   1.30501  |
| k-d_tree_polars      |     0.586078 |        4.77745 |   6.42959  |
| barab-szabi-1        |     0.587266 |        4.80101 |   6.44522  |
| k-d_tree_pandas      |     0.590092 |        3.84839 |   6.8866   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587097 |        73.8744 |    2.96739 |
| k-d_tree_sklearn     |     0.59948  |       228.837  |    4.3669  |
| Bori_Aron_solution-1 |     0.64839  |       147.169  |   15.8441  |