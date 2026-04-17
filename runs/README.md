# 2026-04-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466314 |       0.442733 |   0.433081 |
| barab-szabi-1        |     0.462602 |       0.403872 |   0.435334 |
| k-d_tree_polars      |     0.828828 |       0.402049 |   0.437534 |
| k-d_tree_pandas      |     0.465437 |       0.381946 |   0.545942 |
| Bori_Aron_solution-1 |     0.946191 |       0.5493   |   0.549561 |
| solution-1           |     9.0652   |       1e-06    |   0.633485 |
| k-d_tree_sklearn     |    11.2772   |       1.55466  |   1.1032   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465971 |       0.444453 |   0.436155 |
| barab-szabi-1        |     0.468843 |       0.409034 |   0.439884 |
| k-d_tree_polars      |     0.465446 |       0.40644  |   0.443466 |
| Bori_Aron_solution-1 |     0.457585 |       0.553152 |   0.541724 |
| k-d_tree_pandas      |     0.469819 |       0.399992 |   0.568724 |
| k-d_tree_sklearn     |     0.47004  |       0.981495 |   1.06292  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484677 |       0.453111 |   0.452771 |
| k-d_tree_polars      |     0.474547 |       0.440104 |   0.471116 |
| barab-szabi-1        |     0.466372 |       0.441679 |   0.47468  |
| Bori_Aron_solution-1 |     0.470935 |       0.59283  |   0.561954 |
| k-d_tree_pandas      |     0.464508 |       0.417114 |   0.608235 |
| k-d_tree_sklearn     |     0.468707 |       1.05095  |   1.11291  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472012 |       0.512285 |   0.487002 |
| Bori_Aron_solution-1 |     0.456657 |       0.795709 |   0.56696  |
| k-d_tree_polars      |     0.461398 |       0.56886  |   0.567763 |
| barab-szabi-1        |     0.461971 |       0.558722 |   0.575066 |
| k-d_tree_pandas      |     0.472568 |       0.50454  |   0.745785 |
| k-d_tree_sklearn     |     0.483756 |       1.32197  |   1.17384  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461766 |       0.725346 |   0.510589 |
| Bori_Aron_solution-1 |     0.460554 |       1.48476  |   0.589122 |
| k-d_tree_polars      |     0.46465  |       0.931072 |   0.919628 |
| barab-szabi-1        |     0.46103  |       0.929352 |   0.976993 |
| k-d_tree_pandas      |     0.463603 |       0.819846 |   1.18019  |
| k-d_tree_sklearn     |     0.4756   |       2.10433  |   1.21522  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467804 |        5.08375 |   0.760654 |
| Bori_Aron_solution-1 |     0.457378 |       11.0354  |   0.812119 |
| k-d_tree_sklearn     |     0.466698 |       16.7851  |   1.30404  |
| barab-szabi-1        |     0.460981 |        5.6772  |   6.58175  |
| k-d_tree_polars      |     0.464868 |        5.56125 |   6.66662  |
| k-d_tree_pandas      |     0.460198 |        4.48797 |   6.94362  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.745669 |        69.7223 |    2.62284 |
| k-d_tree_sklearn     |     0.46989  |       243.754  |    4.06686 |
| Bori_Aron_solution-1 |     0.468827 |       145.423  |   24.2665  |