# 2025-04-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.52568  |       1e-06    |   0.352649 |
| barab-szabi-2        |     0.546872 |       0.404047 |   0.410241 |
| barab-szabi-1        |     0.546204 |       0.394954 |   0.411798 |
| k-d_tree_polars      |     7.91327  |       0.464327 |   0.49417  |
| Bori_Aron_solution-1 |     0.539754 |       0.531859 |   0.532376 |
| k-d_tree_pandas      |     0.549263 |       0.374586 |   0.536422 |
| k-d_tree_sklearn     |     3.1052   |       0.973495 |   1.01195  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.560597 |       0.400404 |   0.412906 |
| barab-szabi-1        |     0.558992 |       0.3989   |   0.412961 |
| barab-szabi-2        |     0.557278 |       0.407107 |   0.451658 |
| Bori_Aron_solution-1 |     0.552533 |       0.54547  |   0.525346 |
| k-d_tree_pandas      |     0.563152 |       0.378425 |   0.547166 |
| k-d_tree_sklearn     |     0.562213 |       0.927326 |   1.04417  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555815 |       0.425907 |   0.430467 |
| k-d_tree_polars      |     0.559315 |       0.431864 |   0.440725 |
| barab-szabi-1        |     0.563936 |       0.432922 |   0.442454 |
| Bori_Aron_solution-1 |     0.5533   |       0.577618 |   0.539929 |
| k-d_tree_pandas      |     0.560438 |       0.395669 |   0.585873 |
| k-d_tree_sklearn     |     0.559382 |       0.998947 |   1.03231  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566941 |       0.483531 |   0.44778  |
| k-d_tree_polars      |     0.5575   |       0.539991 |   0.537837 |
| Bori_Aron_solution-1 |     0.553148 |       0.750925 |   0.54881  |
| barab-szabi-1        |     0.557543 |       0.535682 |   0.54944  |
| k-d_tree_pandas      |     0.558379 |       0.481194 |   0.721035 |
| k-d_tree_sklearn     |     0.565977 |       1.21119  |   1.09063  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556257 |       0.72174  |   0.480072 |
| Bori_Aron_solution-1 |     0.556773 |       1.39075  |   0.57541  |
| k-d_tree_polars      |     0.561534 |       0.876467 |   0.879103 |
| barab-szabi-1        |     0.56123  |       0.871568 |   0.921857 |
| k-d_tree_pandas      |     0.558227 |       0.754191 |   1.16116  |
| k-d_tree_sklearn     |     0.560122 |       2.02212  |   1.18992  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559631 |        5.09677 |   0.704553 |
| Bori_Aron_solution-1 |     0.555354 |       10.3991  |   0.867805 |
| k-d_tree_sklearn     |     0.568576 |       15.5794  |   1.28857  |
| barab-szabi-1        |     0.557972 |        5.02051 |   6.34431  |
| k-d_tree_polars      |     0.563638 |        5.00584 |   6.37169  |
| k-d_tree_pandas      |     0.561092 |        3.92033 |   6.78109  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563743 |        72.4096 |    2.58552 |
| k-d_tree_sklearn     |     0.763208 |       223.894  |    4.4187  |
| Bori_Aron_solution-1 |     0.557334 |       156.808  |   13.4842  |