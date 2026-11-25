# 2026-11-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     9.08937  |       1e-06    |   0.353487 |
| barab-szabi-2        |     0.45142  |       0.431122 |   0.416224 |
| k-d_tree_polars      |     0.44441  |       0.422277 |   0.433501 |
| barab-szabi-1        |     0.453013 |       0.41639  |   0.447236 |
| Bori_Aron_solution-1 |     5.09911  |       0.520129 |   0.480685 |
| k-d_tree_pandas      |     0.448733 |       0.377832 |   0.542194 |
| k-d_tree_sklearn     |    10.6856   |       1.01084  |   1.05896  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.448065 |       0.425987 |   0.435825 |
| barab-szabi-2        |     0.447706 |       0.437631 |   0.438869 |
| barab-szabi-1        |     0.454209 |       0.416453 |   0.458236 |
| Bori_Aron_solution-1 |     0.449802 |       0.54151  |   0.538176 |
| k-d_tree_pandas      |     0.456386 |       0.385603 |   0.55545  |
| k-d_tree_sklearn     |     0.457405 |       0.993585 |   1.06469  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.449162 |       0.45102  |   0.462939 |
| k-d_tree_polars      |     0.452325 |       0.449234 |   0.469066 |
| barab-szabi-1        |     0.450564 |       0.447299 |   0.488046 |
| Bori_Aron_solution-1 |     0.472935 |       0.629804 |   0.535592 |
| k-d_tree_pandas      |     0.451257 |       0.405367 |   0.589079 |
| k-d_tree_sklearn     |     0.452094 |       1.04143  |   1.08444  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460577 |       0.531206 |   0.476442 |
| Bori_Aron_solution-1 |     0.474648 |       0.78033  |   0.558885 |
| k-d_tree_polars      |     0.446886 |       0.571513 |   0.567171 |
| barab-szabi-1        |     0.45334  |       0.57301  |   0.576056 |
| k-d_tree_pandas      |     0.447755 |       0.509126 |   0.729514 |
| k-d_tree_sklearn     |     0.454969 |       1.26878  |   1.2618   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.455158 |       0.772291 |   0.548151 |
| Bori_Aron_solution-1 |     0.442274 |       1.46806  |   0.60429  |
| k-d_tree_polars      |     0.464264 |       0.926447 |   0.932381 |
| barab-szabi-1        |     0.447405 |       0.918239 |   0.975626 |
| k-d_tree_pandas      |     0.451641 |       0.808485 |   1.18379  |
| k-d_tree_sklearn     |     0.458389 |       2.11321  |   1.27441  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.446368 |        5.42664 |   0.942259 |
| Bori_Aron_solution-1 |     0.439714 |       11.3355  |   1.1371   |
| k-d_tree_sklearn     |     0.461269 |       16.6399  |   1.37373  |
| barab-szabi-1        |     0.448254 |        5.28625 |   6.80858  |
| k-d_tree_polars      |     0.443079 |        5.26024 |   6.82915  |
| k-d_tree_pandas      |     0.448026 |        4.34206 |   7.00798  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.75167  |       238.779  |    4.41992 |
| barab-szabi-2        |     0.526944 |        76.6271 |    4.54087 |
| Bori_Aron_solution-1 |     0.439284 |       153.977  |   22.4232  |