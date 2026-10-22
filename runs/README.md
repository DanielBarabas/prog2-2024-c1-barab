# 2026-10-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.409356 |       0.402778 |   0.394929 |
| k-d_tree_polars      |     0.408889 |       0.381912 |   0.403512 |
| solution-1           |     6.41354  |       1e-06    |   0.446275 |
| k-d_tree_pandas      |     0.416014 |       0.36381  |   0.503478 |
| Bori_Aron_solution-1 |     0.401022 |       0.505253 |   0.503816 |
| barab-szabi-1        |     7.99894  |       0.4869   |   0.56771  |
| k-d_tree_sklearn     |     2.61444  |       1.14709  |   0.977727 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.421927 |       0.404868 |   0.404243 |
| barab-szabi-1        |     0.425765 |       0.397056 |   0.413077 |
| k-d_tree_polars      |     0.420799 |       0.392825 |   0.416496 |
| Bori_Aron_solution-1 |     0.413568 |       0.521184 |   0.5137   |
| k-d_tree_pandas      |     0.444656 |       0.412836 |   0.520678 |
| k-d_tree_sklearn     |     0.425893 |       0.929826 |   0.994618 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.422134 |       0.446805 |   0.412627 |
| barab-szabi-1        |     0.428315 |       0.431892 |   0.440655 |
| k-d_tree_polars      |     0.431571 |       0.436854 |   0.440667 |
| Bori_Aron_solution-1 |     0.422012 |       0.558378 |   0.548952 |
| k-d_tree_pandas      |     0.424081 |       0.390939 |   0.555892 |
| k-d_tree_sklearn     |     0.429078 |       0.964096 |   0.992309 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.418274 |       0.493189 |   0.438318 |
| k-d_tree_polars      |     0.424646 |       0.528249 |   0.507818 |
| barab-szabi-1        |     0.419785 |       0.577466 |   0.515602 |
| Bori_Aron_solution-1 |     0.409898 |       0.709588 |   0.536638 |
| k-d_tree_pandas      |     0.419928 |       0.463158 |   0.661638 |
| k-d_tree_sklearn     |     0.429558 |       1.19285  |   1.02584  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.42017  |       0.710851 |   0.47471  |
| Bori_Aron_solution-1 |     0.41442  |       1.29679  |   0.554022 |
| k-d_tree_polars      |     0.41987  |       0.916887 |   0.823255 |
| barab-szabi-1        |     0.419749 |       0.930201 |   0.861447 |
| k-d_tree_pandas      |     0.423732 |       0.721097 |   1.03566  |
| k-d_tree_sklearn     |     0.424308 |       2.09164  |   1.08051  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.422562 |        4.42373 |   0.664004 |
| Bori_Aron_solution-1 |     0.443821 |        9.4687  |   0.854021 |
| k-d_tree_sklearn     |     0.424017 |       14.7514  |   1.21606  |
| barab-szabi-1        |     0.420629 |        5.3758  |   5.77347  |
| k-d_tree_polars      |     0.423028 |        5.14631 |   5.88749  |
| k-d_tree_pandas      |     0.418825 |        3.67955 |   6.10094  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570852 |        64.6986 |    2.69652 |
| k-d_tree_sklearn     |     0.528206 |       173.883  |    3.64532 |
| Bori_Aron_solution-1 |     0.416389 |       158.365  |   48.9529  |