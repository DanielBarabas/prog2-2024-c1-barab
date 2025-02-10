# 2025-02-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.68775  |       0.562254 |   0.422792 |
| barab-szabi-1        |     0.619901 |       0.440948 |   0.426856 |
| k-d_tree_polars      |     0.599203 |       0.44892  |   0.435784 |
| solution-1           |     7.43201  |       1e-06    |   0.478393 |
| Bori_Aron_solution-1 |     0.61157  |       0.570803 |   0.570024 |
| k-d_tree_pandas      |     0.618095 |       0.406642 |   0.589225 |
| k-d_tree_sklearn     |     3.16075  |       1.1329   |   1.16497  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.632037 |       0.429121 |   0.425083 |
| k-d_tree_polars      |     0.605438 |       0.421596 |   0.428178 |
| barab-szabi-2        |     0.616856 |       0.431688 |   0.431682 |
| k-d_tree_pandas      |     0.608868 |       0.405481 |   0.561802 |
| Bori_Aron_solution-1 |     0.616421 |       0.585678 |   0.604868 |
| k-d_tree_sklearn     |     0.62938  |       1.0153   |   1.15348  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611964 |       0.44837  |   0.450416 |
| k-d_tree_polars      |     0.62562  |       0.476174 |   0.466186 |
| barab-szabi-1        |     0.647339 |       0.4664   |   0.476107 |
| Bori_Aron_solution-1 |     0.611205 |       0.615593 |   0.58153  |
| k-d_tree_pandas      |     0.629552 |       0.438878 |   0.647902 |
| k-d_tree_sklearn     |     0.629364 |       1.11055  |   1.13671  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62244  |       0.514838 |   0.49018  |
| barab-szabi-1        |     0.600744 |       0.559484 |   0.562151 |
| k-d_tree_polars      |     0.625393 |       0.56472  |   0.565017 |
| Bori_Aron_solution-1 |     0.595917 |       0.773503 |   0.565756 |
| k-d_tree_pandas      |     0.607192 |       0.51259  |   0.743587 |
| k-d_tree_sklearn     |     0.61075  |       1.24564  |   1.13543  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605788 |       0.769155 |   0.564819 |
| Bori_Aron_solution-1 |     0.610113 |       1.41762  |   0.608321 |
| k-d_tree_polars      |     0.60879  |       0.898837 |   0.945828 |
| barab-szabi-1        |     0.607663 |       0.899635 |   0.977458 |
| k-d_tree_pandas      |     0.604745 |       0.758085 |   1.22414  |
| k-d_tree_sklearn     |     0.621506 |       2.15583  |   1.26399  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.635416 |        5.62644 |   0.757316 |
| Bori_Aron_solution-1 |     0.59799  |       10.8486  |   0.880191 |
| k-d_tree_sklearn     |     0.609038 |       16.7929  |   1.33418  |
| barab-szabi-1        |     0.595986 |        4.96927 |   6.81823  |
| k-d_tree_polars      |     0.602711 |        4.93815 |   6.90233  |
| k-d_tree_pandas      |     0.599975 |        3.8673  |   7.17188  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596732 |        77.4674 |    3.08473 |
| k-d_tree_sklearn     |     0.645247 |       235.487  |    4.53419 |
| Bori_Aron_solution-1 |     0.691149 |       150.867  |   19.1045  |