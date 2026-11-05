# 2026-11-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     5.64221  |       0        |   0.240796 |
| barab-szabi-2        |     0.260746 |       0.270581 |   0.27035  |
| barab-szabi-1        |     0.257776 |       0.268524 |   0.288657 |
| k-d_tree_polars      |     6.43603  |       0.28944  |   0.299505 |
| k-d_tree_pandas      |     0.265659 |       0.235848 |   0.33312  |
| Bori_Aron_solution-1 |     0.251094 |       0.333142 |   0.341309 |
| k-d_tree_sklearn     |     2.02974  |       0.651172 |   0.676568 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.266609 |       0.276371 |   0.268159 |
| barab-szabi-1        |     0.262677 |       0.291401 |   0.27385  |
| k-d_tree_polars      |     0.279715 |       0.293233 |   0.283796 |
| k-d_tree_pandas      |     0.26525  |       0.242244 |   0.343813 |
| Bori_Aron_solution-1 |     0.26044  |       0.349926 |   0.344504 |
| k-d_tree_sklearn     |     0.271345 |       0.639637 |   0.697115 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.262667 |       0.289663 |   0.258997 |
| k-d_tree_polars      |     0.263653 |       0.285011 |   0.296175 |
| barab-szabi-1        |     0.261883 |       0.284313 |   0.302993 |
| Bori_Aron_solution-1 |     0.265495 |       0.37184  |   0.336887 |
| k-d_tree_pandas      |     0.263293 |       0.251227 |   0.365769 |
| k-d_tree_sklearn     |     0.275873 |       0.675259 |   0.681287 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.264433 |       0.350998 |   0.336559 |
| Bori_Aron_solution-1 |     0.259037 |       0.507018 |   0.354372 |
| barab-szabi-1        |     0.261645 |       0.350029 |   0.364295 |
| barab-szabi-2        |     0.260195 |       0.343467 |   0.374068 |
| k-d_tree_pandas      |     0.261981 |       0.303018 |   0.435187 |
| k-d_tree_sklearn     |     0.263769 |       0.917881 |   0.727195 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.266536 |       0.517266 |   0.34935  |
| Bori_Aron_solution-1 |     0.274776 |       0.918554 |   0.405556 |
| k-d_tree_polars      |     0.277346 |       0.619861 |   0.571129 |
| barab-szabi-1        |     0.268451 |       0.607849 |   0.607497 |
| k-d_tree_pandas      |     0.282489 |       0.463226 |   0.712876 |
| k-d_tree_sklearn     |     0.270021 |       1.31304  |   0.764585 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.258988 |        3.51635 |   0.590676 |
| Bori_Aron_solution-1 |     0.273346 |        6.63655 |   0.729668 |
| k-d_tree_sklearn     |     0.272561 |       11.426   |   0.914055 |
| barab-szabi-1        |     0.264333 |        3.33662 |   4.59495  |
| k-d_tree_polars      |     0.284337 |        3.46812 |   4.69761  |
| k-d_tree_pandas      |     0.269254 |        2.12787 |   4.73739  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.385678 |       162.258  |    2.41194 |
| barab-szabi-2        |     0.617757 |        58.8872 |    3.17252 |
| Bori_Aron_solution-1 |     0.282509 |       126.846  |   20.488   |