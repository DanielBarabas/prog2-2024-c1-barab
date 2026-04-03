# 2026-04-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48249  |       0.439214 |   0.434224 |
| solution-1           |     9.62984  |       1e-06    |   0.452549 |
| k-d_tree_polars      |     0.480545 |       0.430871 |   0.454577 |
| k-d_tree_pandas      |     0.472264 |       0.393854 |   0.549731 |
| Bori_Aron_solution-1 |     0.476824 |       0.568952 |   0.558594 |
| barab-szabi-1        |     9.19     |       0.553137 |   0.636315 |
| k-d_tree_sklearn     |     3.73861  |       1.23591  |   1.08345  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464817 |       0.522301 |   0.437371 |
| barab-szabi-1        |     0.47365  |       0.428886 |   0.443418 |
| k-d_tree_polars      |     0.475272 |       0.434365 |   0.450547 |
| k-d_tree_pandas      |     0.463816 |       0.399863 |   0.564842 |
| Bori_Aron_solution-1 |     0.464631 |       0.566037 |   0.565138 |
| k-d_tree_sklearn     |     0.465809 |       1.00506  |   1.09827  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.4639   |       0.45038  |   0.45136  |
| k-d_tree_polars      |     0.47142  |       0.434472 |   0.47372  |
| barab-szabi-1        |     0.4677   |       0.440948 |   0.477259 |
| Bori_Aron_solution-1 |     0.462538 |       0.604937 |   0.560605 |
| k-d_tree_pandas      |     0.463579 |       0.410427 |   0.609739 |
| k-d_tree_sklearn     |     0.478226 |       1.06144  |   1.08874  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464717 |       0.511165 |   0.479789 |
| k-d_tree_polars      |     0.46883  |       0.56138  |   0.567462 |
| Bori_Aron_solution-1 |     0.462404 |       0.797231 |   0.570295 |
| barab-szabi-1        |     0.470808 |       0.570059 |   0.580821 |
| k-d_tree_pandas      |     0.473914 |       0.51214  |   0.755263 |
| k-d_tree_sklearn     |     0.481341 |       1.30734  |   1.16205  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466307 |       0.736362 |   0.524135 |
| Bori_Aron_solution-1 |     0.460069 |       1.47213  |   0.603773 |
| k-d_tree_polars      |     0.471697 |       0.935558 |   0.935413 |
| barab-szabi-1        |     0.464443 |       0.928482 |   0.962622 |
| k-d_tree_pandas      |     0.471249 |       0.816468 |   1.2056   |
| k-d_tree_sklearn     |     0.468456 |       2.20879  |   1.21721  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469561 |        5.25104 |   0.756135 |
| Bori_Aron_solution-1 |     0.459285 |       11.3647  |   0.822678 |
| k-d_tree_sklearn     |     0.471846 |       17.5613  |   1.34539  |
| barab-szabi-1        |     0.471457 |        5.67877 |   6.92027  |
| k-d_tree_polars      |     0.476442 |        5.58252 |   6.93922  |
| k-d_tree_pandas      |     0.466585 |        4.49097 |   7.3008   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.749929 |        72.2974 |    2.75663 |
| k-d_tree_sklearn     |     0.465632 |       240.418  |    3.97703 |
| Bori_Aron_solution-1 |     0.463472 |       155.453  |   17.5297  |