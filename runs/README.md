# 2025-03-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596299 |       0.412601 |   0.411003 |
| k-d_tree_polars      |     0.577139 |       0.399184 |   0.413026 |
| barab-szabi-1        |     0.579841 |       0.403769 |   0.416164 |
| solution-1           |     7.23877  |       1e-06    |   0.50258  |
| Bori_Aron_solution-1 |     0.572542 |       0.550117 |   0.545136 |
| k-d_tree_pandas      |     7.5261   |       0.398266 |   0.587126 |
| k-d_tree_sklearn     |     3.01723  |       1.01712  |   1.03155  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.592833 |       0.410432 |   0.407315 |
| k-d_tree_polars      |     0.587602 |       0.405731 |   0.40743  |
| barab-szabi-1        |     0.599225 |       0.408643 |   0.411708 |
| k-d_tree_pandas      |     0.591358 |       0.388238 |   0.553496 |
| Bori_Aron_solution-1 |     0.582662 |       0.550272 |   0.606695 |
| k-d_tree_sklearn     |     0.589109 |       0.997016 |   1.02323  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589924 |       0.424101 |   0.418887 |
| k-d_tree_polars      |     0.583879 |       0.436286 |   0.440429 |
| barab-szabi-1        |     0.617601 |       0.432176 |   0.440766 |
| Bori_Aron_solution-1 |     0.596416 |       0.585145 |   0.549262 |
| k-d_tree_pandas      |     0.589176 |       0.406259 |   0.616398 |
| k-d_tree_sklearn     |     0.636859 |       1.01767  |   1.04957  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590449 |       0.4916   |   0.449884 |
| k-d_tree_polars      |     0.590606 |       0.540027 |   0.539775 |
| barab-szabi-1        |     0.591848 |       0.555703 |   0.541039 |
| Bori_Aron_solution-1 |     0.581608 |       0.750953 |   0.560874 |
| k-d_tree_pandas      |     0.594464 |       0.481264 |   0.733984 |
| k-d_tree_sklearn     |     0.596743 |       1.22429  |   1.12382  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590847 |       0.729227 |   0.515924 |
| Bori_Aron_solution-1 |     0.58664  |       1.38819  |   0.588176 |
| k-d_tree_polars      |     0.599127 |       0.860027 |   0.886529 |
| barab-szabi-1        |     0.592045 |       0.868465 |   0.924335 |
| k-d_tree_pandas      |     0.593684 |       0.738441 |   1.17648  |
| k-d_tree_sklearn     |     0.594463 |       2.06766  |   1.20409  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593975 |        5.31565 |   0.73615  |
| Bori_Aron_solution-1 |     0.58263  |       10.5599  |   0.882497 |
| k-d_tree_sklearn     |     0.594368 |       16.3422  |   1.31036  |
| barab-szabi-1        |     0.596713 |        4.88402 |   6.5526   |
| k-d_tree_polars      |     0.591495 |        4.94085 |   6.61661  |
| k-d_tree_pandas      |     0.592052 |        3.81486 |   6.94313  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.784793 |        72.1958 |    2.96475 |
| k-d_tree_sklearn     |     0.667694 |       228.222  |    4.28883 |
| Bori_Aron_solution-1 |     0.590447 |       152.589  |   16.3721  |