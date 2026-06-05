# 2026-06-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.57124  |       1e-06    |   0.409898 |
| barab-szabi-2        |     0.471763 |       0.442529 |   0.450187 |
| k-d_tree_polars      |     0.495552 |       0.430477 |   0.460145 |
| barab-szabi-1        |     8.62299  |       0.457036 |   0.499993 |
| k-d_tree_pandas      |     0.480858 |       0.471716 |   0.582604 |
| Bori_Aron_solution-1 |     0.460568 |       0.569611 |   0.602338 |
| k-d_tree_sklearn     |     2.97305  |       1.05014  |   1.10726  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488215 |       0.444831 |   0.448588 |
| k-d_tree_polars      |     0.481194 |       0.419595 |   0.449488 |
| barab-szabi-1        |     0.497481 |       0.424897 |   0.461712 |
| Bori_Aron_solution-1 |     0.473747 |       0.568864 |   0.557406 |
| k-d_tree_pandas      |     0.477884 |       0.39704  |   0.569835 |
| k-d_tree_sklearn     |     0.481087 |       1.01056  |   1.13868  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.487212 |       0.463983 |   0.481455 |
| barab-szabi-1        |     0.491456 |       0.460842 |   0.49577  |
| barab-szabi-2        |     0.482588 |       0.479534 |   0.497759 |
| Bori_Aron_solution-1 |     0.480294 |       0.609094 |   0.573524 |
| k-d_tree_pandas      |     0.50928  |       0.421942 |   0.621136 |
| k-d_tree_sklearn     |     0.493088 |       1.0746   |   1.15878  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494535 |       0.525192 |   0.496775 |
| Bori_Aron_solution-1 |     0.486153 |       0.792674 |   0.580579 |
| k-d_tree_polars      |     0.498491 |       0.571242 |   0.581685 |
| barab-szabi-1        |     0.478763 |       0.578843 |   0.602523 |
| k-d_tree_pandas      |     0.492741 |       0.524873 |   0.769622 |
| k-d_tree_sklearn     |     0.495971 |       1.3257   |   1.20302  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484305 |       0.765905 |   0.548064 |
| Bori_Aron_solution-1 |     0.489877 |       1.47082  |   0.606606 |
| k-d_tree_polars      |     0.501719 |       0.955314 |   0.951432 |
| barab-szabi-1        |     0.486627 |       0.947076 |   0.993299 |
| k-d_tree_pandas      |     0.486453 |       0.829389 |   1.20669  |
| k-d_tree_sklearn     |     0.501027 |       2.15203  |   1.26769  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500533 |        5.6046  |   0.804848 |
| Bori_Aron_solution-1 |     0.489542 |       11.9733  |   0.863875 |
| k-d_tree_sklearn     |     0.529254 |       19.6629  |   1.4891   |
| barab-szabi-1        |     0.473908 |        5.64494 |   7.23375  |
| k-d_tree_polars      |     0.505514 |        5.6426  |   7.41286  |
| k-d_tree_pandas      |     0.510433 |        4.49724 |   7.82565  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.516637 |        76.7065 |    3.05987 |
| k-d_tree_sklearn     |     0.920595 |       243.482  |    4.13185 |
| Bori_Aron_solution-1 |     0.522494 |       156.708  |   23.7958  |