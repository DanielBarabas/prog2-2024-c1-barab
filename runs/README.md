# 2026-10-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476019 |       0.465531 |   0.448858 |
| solution-1           |     8.00679  |       1e-06    |   0.460577 |
| k-d_tree_polars      |     0.479924 |       0.439767 |   0.472571 |
| k-d_tree_pandas      |     0.486055 |       0.402496 |   0.570528 |
| Bori_Aron_solution-1 |     0.472219 |       0.586148 |   0.577592 |
| barab-szabi-1        |     8.96692  |       0.558985 |   0.640601 |
| k-d_tree_sklearn     |     3.43594  |       1.21545  |   1.09966  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479614 |       0.437296 |   0.440394 |
| k-d_tree_polars      |     0.491801 |       0.452662 |   0.456013 |
| barab-szabi-1        |     0.489183 |       0.445568 |   0.461134 |
| k-d_tree_pandas      |     0.48798  |       0.451931 |   0.582223 |
| Bori_Aron_solution-1 |     0.482446 |       0.60937  |   0.588558 |
| k-d_tree_sklearn     |     0.4948   |       1.03289  |   1.1098   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.489505 |       0.45096  |   0.446769 |
| k-d_tree_polars      |     0.479167 |       0.471788 |   0.484491 |
| barab-szabi-1        |     0.48306  |       0.483182 |   0.490915 |
| Bori_Aron_solution-1 |     0.469153 |       0.612093 |   0.560754 |
| k-d_tree_pandas      |     0.483319 |       0.408326 |   0.607979 |
| k-d_tree_sklearn     |     0.48388  |       1.06778  |   1.11218  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.489193 |       0.520989 |   0.476794 |
| Bori_Aron_solution-1 |     0.453628 |       0.770708 |   0.555756 |
| barab-szabi-1        |     0.477028 |       0.567695 |   0.56058  |
| k-d_tree_polars      |     0.46073  |       0.585536 |   0.581984 |
| k-d_tree_pandas      |     0.467869 |       0.501771 |   0.731433 |
| k-d_tree_sklearn     |     0.485898 |       1.29886  |   1.19599  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48636  |       0.756874 |   0.529731 |
| Bori_Aron_solution-1 |     0.483812 |       1.45029  |   0.616677 |
| k-d_tree_polars      |     0.484477 |       0.958561 |   0.938453 |
| barab-szabi-1        |     0.490648 |       0.937708 |   0.998718 |
| k-d_tree_pandas      |     0.49215  |       0.833752 |   1.22653  |
| k-d_tree_sklearn     |     0.490227 |       2.18038  |   1.23985  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484474 |        5.06564 |   0.729075 |
| Bori_Aron_solution-1 |     0.474542 |       11.0178  |   0.803926 |
| k-d_tree_sklearn     |     0.479502 |       17.1727  |   1.36739  |
| barab-szabi-1        |     0.470788 |        5.38215 |   6.56123  |
| k-d_tree_polars      |     0.481904 |        5.35162 |   6.59791  |
| k-d_tree_pandas      |     0.468174 |        4.37025 |   6.95077  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.808371 |        77.3644 |    2.86801 |
| k-d_tree_sklearn     |     0.625933 |       234.828  |    3.74338 |
| Bori_Aron_solution-1 |     0.483952 |       163.96   |   28.3845  |