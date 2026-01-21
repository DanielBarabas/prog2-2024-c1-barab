# 2026-01-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519661 |       0.492049 |   0.430709 |
| k-d_tree_polars      |     0.546432 |       0.413126 |   0.440112 |
| solution-1           |     7.98785  |       1e-06    |   0.464606 |
| barab-szabi-1        |     0.542495 |       0.3948   |   0.511703 |
| Bori_Aron_solution-1 |     0.543054 |       0.554776 |   0.555419 |
| k-d_tree_pandas      |     8.67373  |       0.471674 |   0.664193 |
| k-d_tree_sklearn     |     3.14591  |       1.10042  |   1.06963  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529716 |       0.43917  |   0.432058 |
| k-d_tree_polars      |     0.556983 |       0.414311 |   0.441797 |
| barab-szabi-1        |     0.533128 |       0.419241 |   0.447323 |
| k-d_tree_pandas      |     0.534582 |       0.389215 |   0.552501 |
| Bori_Aron_solution-1 |     0.537196 |       0.570801 |   0.584832 |
| k-d_tree_sklearn     |     0.541265 |       0.971698 |   1.07499  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547564 |       0.459543 |   0.457181 |
| k-d_tree_polars      |     0.553677 |       0.442775 |   0.483328 |
| barab-szabi-1        |     0.536484 |       0.512628 |   0.506151 |
| Bori_Aron_solution-1 |     0.535845 |       0.595017 |   0.573381 |
| k-d_tree_pandas      |     0.551736 |       0.435889 |   0.597584 |
| k-d_tree_sklearn     |     0.528458 |       0.999416 |   1.08125  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533095 |       0.513207 |   0.473824 |
| Bori_Aron_solution-1 |     0.521751 |       0.78347  |   0.555205 |
| k-d_tree_polars      |     0.528708 |       0.554645 |   0.558602 |
| barab-szabi-1        |     0.527598 |       0.556227 |   0.567484 |
| k-d_tree_pandas      |     0.537294 |       0.503264 |   0.734076 |
| k-d_tree_sklearn     |     0.539643 |       1.29306  |   1.13883  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531008 |       0.726013 |   0.503462 |
| Bori_Aron_solution-1 |     0.518324 |       1.42126  |   0.582871 |
| k-d_tree_polars      |     0.528285 |       0.9433   |   0.915157 |
| barab-szabi-1        |     0.527242 |       0.927893 |   0.954776 |
| k-d_tree_pandas      |     0.525572 |       0.809676 |   1.17607  |
| k-d_tree_sklearn     |     0.528445 |       2.0967   |   1.20526  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552895 |        5.4795  |   0.773339 |
| Bori_Aron_solution-1 |     0.524339 |       11.1123  |   0.82903  |
| k-d_tree_sklearn     |     0.540981 |       17.218   |   1.34189  |
| k-d_tree_polars      |     0.540103 |        5.62856 |   6.66866  |
| barab-szabi-1        |     0.54007  |        5.64014 |   6.83835  |
| k-d_tree_pandas      |     0.532012 |        4.1992  |   7.2414   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.526195 |        76.4151 |    2.78248 |
| k-d_tree_sklearn     |     0.571088 |       242.162  |    4.39533 |
| Bori_Aron_solution-1 |     0.699418 |       153.156  |   17.0329  |