# 2025-08-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.0387   |       0.579755 |   0.422283 |
| barab-szabi-1        |     0.529364 |       0.403905 |   0.432507 |
| k-d_tree_polars      |     0.544841 |       0.413408 |   0.432626 |
| solution-1           |     7.95409  |       1e-06    |   0.434077 |
| k-d_tree_pandas      |     0.546315 |       0.38699  |   0.544794 |
| Bori_Aron_solution-1 |     0.521497 |       0.549935 |   0.553221 |
| k-d_tree_sklearn     |     2.96003  |       1.07957  |   1.07813  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.536234 |       0.409451 |   0.426013 |
| barab-szabi-2        |     0.558376 |       0.421704 |   0.432052 |
| barab-szabi-1        |     0.54196  |       0.410788 |   0.432363 |
| Bori_Aron_solution-1 |     0.543418 |       0.568572 |   0.547809 |
| k-d_tree_pandas      |     0.550163 |       0.386503 |   0.589475 |
| k-d_tree_sklearn     |     0.551404 |       0.958073 |   1.08754  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55238  |       0.4351   |   0.439289 |
| k-d_tree_polars      |     0.540298 |       0.435121 |   0.456102 |
| barab-szabi-1        |     0.541885 |       0.437493 |   0.45797  |
| Bori_Aron_solution-1 |     0.537342 |       0.587196 |   0.542827 |
| k-d_tree_pandas      |     0.548174 |       0.412981 |   0.614034 |
| k-d_tree_sklearn     |     0.547834 |       1.01539  |   1.09142  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547695 |       0.511321 |   0.475907 |
| k-d_tree_polars      |     0.536365 |       0.549214 |   0.550384 |
| Bori_Aron_solution-1 |     0.54481  |       0.784257 |   0.560585 |
| barab-szabi-1        |     0.543462 |       0.555586 |   0.572573 |
| k-d_tree_pandas      |     0.54505  |       0.490429 |   0.737361 |
| k-d_tree_sklearn     |     0.54364  |       1.23495  |   1.13445  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543674 |       0.737811 |   0.500307 |
| Bori_Aron_solution-1 |     0.5329   |       1.38674  |   0.585915 |
| k-d_tree_polars      |     0.546677 |       0.886893 |   0.908725 |
| barab-szabi-1        |     0.538763 |       0.888214 |   0.934891 |
| k-d_tree_pandas      |     0.538902 |       0.754735 |   1.19119  |
| k-d_tree_sklearn     |     0.54035  |       2.07684  |   1.20907  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533837 |        5.1725  |   0.740015 |
| Bori_Aron_solution-1 |     0.538149 |       10.6214  |   0.853801 |
| k-d_tree_sklearn     |     0.544348 |       16.3687  |   1.34362  |
| barab-szabi-1        |     0.543687 |        4.99416 |   6.50866  |
| k-d_tree_polars      |     0.538663 |        5.03641 |   6.55105  |
| k-d_tree_pandas      |     0.542331 |        3.93467 |   6.90654  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551992 |         73.445 |    2.76164 |
| k-d_tree_sklearn     |     0.683301 |        233.268 |    3.93121 |
| Bori_Aron_solution-1 |     0.546092 |        139.934 |   18.826   |