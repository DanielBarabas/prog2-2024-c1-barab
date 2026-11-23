# 2026-11-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.97227  |       1e-06    |   0.291508 |
| barab-szabi-2        |     0.86682  |       0.360808 |   0.356815 |
| barab-szabi-1        |     0.36741  |       0.344642 |   0.365524 |
| k-d_tree_polars      |     0.368444 |       0.362193 |   0.370725 |
| Bori_Aron_solution-1 |     4.48892  |       0.44549  |   0.413531 |
| k-d_tree_pandas      |     0.53442  |       0.321542 |   0.471338 |
| k-d_tree_sklearn     |     8.78939  |       1.06039  |   0.994952 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.368374 |       0.354559 |   0.363867 |
| barab-szabi-2        |     0.377489 |       0.378952 |   0.370565 |
| barab-szabi-1        |     0.372365 |       0.361245 |   0.390875 |
| Bori_Aron_solution-1 |     0.363036 |       0.460216 |   0.459388 |
| k-d_tree_pandas      |     0.376678 |       0.326667 |   0.459862 |
| k-d_tree_sklearn     |     0.421996 |       0.842834 |   0.915489 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.373409 |       0.379853 |   0.374745 |
| barab-szabi-1        |     0.36671  |       0.369412 |   0.384294 |
| barab-szabi-2        |     0.369839 |       0.36815  |   0.405134 |
| Bori_Aron_solution-1 |     0.374415 |       0.502243 |   0.465288 |
| k-d_tree_pandas      |     0.368439 |       0.333616 |   0.479918 |
| k-d_tree_sklearn     |     0.369076 |       0.892898 |   0.929875 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.359295 |       0.458224 |   0.430029 |
| k-d_tree_polars      |     0.368234 |       0.472929 |   0.453017 |
| barab-szabi-1        |     0.358971 |       0.472348 |   0.464044 |
| Bori_Aron_solution-1 |     0.374095 |       0.644984 |   0.487703 |
| k-d_tree_pandas      |     0.382549 |       0.426142 |   0.591727 |
| k-d_tree_sklearn     |     0.375511 |       1.10333  |   0.915069 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.353601 |       0.653734 |   0.453853 |
| Bori_Aron_solution-1 |     0.355974 |       1.19106  |   0.495447 |
| k-d_tree_polars      |     0.355474 |       0.768548 |   0.787772 |
| barab-szabi-1        |     0.363847 |       0.779197 |   0.832635 |
| k-d_tree_pandas      |     0.362893 |       0.613898 |   0.95414  |
| k-d_tree_sklearn     |     0.356372 |       1.81793  |   0.964986 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.352853 |        5.01344 |   0.740873 |
| Bori_Aron_solution-1 |     0.363327 |        9.53486 |   0.920591 |
| k-d_tree_sklearn     |     0.37117  |       15.6244  |   1.06881  |
| k-d_tree_polars      |     0.350389 |        4.39413 |   6.39878  |
| barab-szabi-1        |     0.348283 |        4.41345 |   6.49326  |
| k-d_tree_pandas      |     0.350276 |        3.20221 |   6.61756  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.628318 |       221.033  |    3.24808 |
| barab-szabi-2        |     0.440637 |        71.8477 |    3.6251  |
| Bori_Aron_solution-1 |     0.35219  |       145.81   |   24.422   |