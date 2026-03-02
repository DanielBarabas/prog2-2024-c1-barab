# 2026-03-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485616 |       0.435547 |   0.438756 |
| k-d_tree_polars      |     0.489261 |       0.420705 |   0.448929 |
| solution-1           |     8.4413   |       1e-06    |   0.48939  |
| k-d_tree_pandas      |     0.527286 |       0.440949 |   0.571663 |
| Bori_Aron_solution-1 |     0.48945  |       0.55947  |   0.576423 |
| barab-szabi-1        |     9.76037  |       0.485504 |   0.620297 |
| k-d_tree_sklearn     |     3.49632  |       1.16475  |   1.09406  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.508013 |       0.433798 |   0.451024 |
| k-d_tree_polars      |     0.507826 |       0.431147 |   0.454067 |
| barab-szabi-2        |     0.513343 |       0.450252 |   0.454835 |
| Bori_Aron_solution-1 |     0.499017 |       0.588306 |   0.572978 |
| k-d_tree_pandas      |     0.503909 |       0.409063 |   0.587438 |
| k-d_tree_sklearn     |     0.510442 |       1.02431  |   1.10953  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.505824 |       0.460852 |   0.459582 |
| barab-szabi-1        |     0.507536 |       0.450909 |   0.480494 |
| k-d_tree_polars      |     0.513832 |       0.46228  |   0.48925  |
| Bori_Aron_solution-1 |     0.499127 |       0.62158  |   0.577842 |
| k-d_tree_pandas      |     0.519889 |       0.425875 |   0.633095 |
| k-d_tree_sklearn     |     0.517606 |       1.08305  |   1.13806  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.50704  |       0.518638 |   0.491353 |
| k-d_tree_polars      |     0.509684 |       0.578197 |   0.573668 |
| Bori_Aron_solution-1 |     0.489854 |       0.80511  |   0.597388 |
| barab-szabi-1        |     0.507409 |       0.580552 |   0.604605 |
| k-d_tree_pandas      |     0.508251 |       0.524995 |   0.765656 |
| k-d_tree_sklearn     |     0.515247 |       1.30831  |   1.19867  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.503549 |       0.757704 |   0.526572 |
| Bori_Aron_solution-1 |     0.496946 |       1.49035  |   0.601063 |
| k-d_tree_polars      |     0.516683 |       0.946334 |   0.943679 |
| barab-szabi-1        |     0.512548 |       0.932037 |   0.967484 |
| k-d_tree_pandas      |     0.504444 |       0.827452 |   1.2121   |
| k-d_tree_sklearn     |     0.515591 |       2.25192  |   1.25458  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518915 |        5.51868 |   0.770097 |
| Bori_Aron_solution-1 |     0.509233 |       11.4955  |   0.852088 |
| k-d_tree_sklearn     |     0.516353 |       18.0428  |   1.36727  |
| barab-szabi-1        |     0.503765 |        5.57243 |   6.93037  |
| k-d_tree_polars      |     0.518208 |        5.55685 |   7.0156   |
| k-d_tree_pandas      |     0.525676 |        4.47417 |   7.40957  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518392 |        75.0248 |    2.64536 |
| k-d_tree_sklearn     |     0.78728  |       239.953  |    3.94561 |
| Bori_Aron_solution-1 |     0.504395 |       152.766  |   20.1448  |