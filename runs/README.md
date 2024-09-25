# 2024-09-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61161  |       0.382057 |   0.386876 |
| barab-szabi-1        |     0.612853 |       0.393907 |   0.387919 |
| Bori_Aron_solution-1 |     4.36456  |       0.671982 |   0.4537   |
| k-d_tree_polars      |     0.613003 |       0.409013 |   0.472179 |
| solution-1           |     7.652    |       1e-06    |   0.520274 |
| k-d_tree_pandas      |     4.02984  |       0.435347 |   0.523465 |
| k-d_tree_sklearn     |     2.94002  |       1.04068  |   0.971417 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617564 |       0.387507 |   0.379834 |
| k-d_tree_polars      |     0.630965 |       0.442524 |   0.391239 |
| barab-szabi-1        |     0.62177  |       0.405444 |   0.393589 |
| Bori_Aron_solution-1 |     0.604953 |       0.540762 |   0.524381 |
| k-d_tree_pandas      |     0.613997 |       0.391138 |   0.533009 |
| k-d_tree_sklearn     |     0.614941 |       0.884974 |   0.961971 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617074 |       0.400941 |   0.405685 |
| k-d_tree_polars      |     0.630553 |       0.428763 |   0.420531 |
| barab-szabi-1        |     0.616209 |       0.425718 |   0.422486 |
| Bori_Aron_solution-1 |     0.601707 |       0.563738 |   0.527201 |
| k-d_tree_pandas      |     0.615127 |       0.400423 |   0.58046  |
| k-d_tree_sklearn     |     0.622326 |       0.937813 |   1.02714  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612205 |       0.458146 |   0.425783 |
| k-d_tree_polars      |     0.609643 |       0.52693  |   0.516501 |
| barab-szabi-1        |     0.614032 |       0.532331 |   0.522533 |
| Bori_Aron_solution-1 |     0.614383 |       0.733411 |   0.545017 |
| k-d_tree_pandas      |     0.613102 |       0.472356 |   0.711943 |
| k-d_tree_sklearn     |     0.614407 |       1.15058  |   1.05123  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609018 |       0.715487 |   0.466302 |
| Bori_Aron_solution-1 |     0.609363 |       1.37461  |   0.560719 |
| k-d_tree_polars      |     0.611295 |       0.84673  |   0.87194  |
| barab-szabi-1        |     0.618031 |       0.85021  |   0.906556 |
| k-d_tree_sklearn     |     0.617499 |       1.96384  |   1.13468  |
| k-d_tree_pandas      |     0.61476  |       0.737078 |   1.15506  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613817 |        5.41875 |   0.750025 |
| Bori_Aron_solution-1 |     0.609579 |       10.5915  |   0.818384 |
| k-d_tree_sklearn     |     0.611703 |       15.9889  |   1.25313  |
| barab-szabi-1        |     0.610879 |        4.7559  |   6.58881  |
| k-d_tree_polars      |     0.618347 |        4.90983 |   6.59486  |
| k-d_tree_pandas      |     0.615387 |        3.85957 |   7.05622  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.684007 |        72.7414 |    3.29098 |
| k-d_tree_sklearn     |     0.827046 |       228.519  |    4.24782 |
| Bori_Aron_solution-1 |     0.617996 |       149.019  |   16.8838  |