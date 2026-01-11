# 2026-01-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.12759  |       1e-06    |   0.444    |
| barab-szabi-2        |     0.524749 |       0.485524 |   0.446244 |
| k-d_tree_polars      |     0.538111 |       0.424574 |   0.447245 |
| barab-szabi-1        |     0.551288 |       0.430281 |   0.479392 |
| Bori_Aron_solution-1 |     0.535218 |       0.55248  |   0.555261 |
| k-d_tree_pandas      |     8.95584  |       0.41791  |   0.686407 |
| k-d_tree_sklearn     |     3.4356   |       1.08581  |   1.11877  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547179 |       0.44901  |   0.438839 |
| k-d_tree_polars      |     0.548808 |       0.420339 |   0.440402 |
| barab-szabi-1        |     0.536333 |       0.423225 |   0.490582 |
| Bori_Aron_solution-1 |     0.531763 |       0.577672 |   0.553246 |
| k-d_tree_pandas      |     0.532886 |       0.413849 |   0.567276 |
| k-d_tree_sklearn     |     0.537724 |       1.0109   |   1.0987   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551338 |       0.450094 |   0.452586 |
| k-d_tree_polars      |     0.537352 |       0.438657 |   0.467166 |
| barab-szabi-1        |     0.536799 |       0.458124 |   0.470546 |
| Bori_Aron_solution-1 |     0.532321 |       0.603778 |   0.576619 |
| k-d_tree_pandas      |     0.538777 |       0.42502  |   0.622046 |
| k-d_tree_sklearn     |     0.537912 |       1.02678  |   1.12012  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552503 |       0.525205 |   0.503966 |
| k-d_tree_polars      |     0.542491 |       0.571522 |   0.567202 |
| barab-szabi-1        |     0.535412 |       0.567339 |   0.574007 |
| Bori_Aron_solution-1 |     0.523476 |       0.800849 |   0.586444 |
| k-d_tree_pandas      |     0.535515 |       0.519823 |   0.761402 |
| k-d_tree_sklearn     |     0.557091 |       1.27928  |   1.16164  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53343  |       0.75564  |   0.525601 |
| Bori_Aron_solution-1 |     0.543053 |       1.47966  |   0.594783 |
| k-d_tree_polars      |     0.530284 |       0.945072 |   0.952431 |
| barab-szabi-1        |     0.544538 |       0.929368 |   0.967654 |
| k-d_tree_pandas      |     0.532628 |       0.817521 |   1.20056  |
| k-d_tree_sklearn     |     0.545093 |       2.15692  |   1.24529  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536275 |        5.59666 |   0.768789 |
| Bori_Aron_solution-1 |     0.533861 |       11.4172  |   0.855591 |
| k-d_tree_sklearn     |     0.547944 |       17.7497  |   1.3744   |
| barab-szabi-1        |     0.556914 |        5.4052  |   6.97613  |
| k-d_tree_polars      |     0.54087  |        5.50245 |   7.10253  |
| k-d_tree_pandas      |     0.532547 |        4.51599 |   7.38776  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531504 |        81.4359 |    2.83956 |
| k-d_tree_sklearn     |     0.552306 |       243.79   |    4.09005 |
| Bori_Aron_solution-1 |     0.665307 |       153.334  |   18.1701  |