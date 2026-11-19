# 2026-11-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     4.77803  |       1e-06    |   0.241965 |
| barab-szabi-2        |     0.289283 |       0.293606 |   0.277862 |
| barab-szabi-1        |     0.28916  |       0.276601 |   0.302671 |
| k-d_tree_polars      |     7.05001  |       0.315379 |   0.303454 |
| Bori_Aron_solution-1 |     0.275968 |       0.352017 |   0.348416 |
| k-d_tree_pandas      |     0.287923 |       0.266078 |   0.354407 |
| k-d_tree_sklearn     |     1.94295  |       0.664177 |   0.706053 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.29023  |       0.290623 |   0.277885 |
| k-d_tree_polars      |     0.290956 |       0.290119 |   0.294928 |
| barab-szabi-1        |     0.28644  |       0.277967 |   0.298415 |
| Bori_Aron_solution-1 |     0.284256 |       0.371897 |   0.353926 |
| k-d_tree_pandas      |     0.29313  |       0.261301 |   0.360242 |
| k-d_tree_sklearn     |     0.289876 |       0.669928 |   0.722689 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.296004 |       0.427528 |   0.292173 |
| barab-szabi-1        |     0.295722 |       0.307512 |   0.320493 |
| k-d_tree_polars      |     0.298265 |       0.316216 |   0.333117 |
| k-d_tree_pandas      |     0.292807 |       0.285613 |   0.400156 |
| Bori_Aron_solution-1 |     0.286979 |       0.397729 |   0.452873 |
| k-d_tree_sklearn     |     0.297138 |       0.693019 |   0.701023 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.294068 |       0.352177 |   0.323239 |
| Bori_Aron_solution-1 |     0.2817   |       0.509628 |   0.370231 |
| k-d_tree_polars      |     0.289945 |       0.394421 |   0.385391 |
| barab-szabi-1        |     0.293002 |       0.408317 |   0.390585 |
| k-d_tree_pandas      |     0.293439 |       0.357986 |   0.498663 |
| k-d_tree_sklearn     |     0.293183 |       0.886817 |   0.755706 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.298887 |       0.569968 |   0.375328 |
| Bori_Aron_solution-1 |     0.291598 |       0.977778 |   0.426718 |
| k-d_tree_polars      |     0.295382 |       0.692722 |   0.630167 |
| barab-szabi-1        |     0.301721 |       0.687314 |   0.670612 |
| k-d_tree_sklearn     |     0.300727 |       1.47723  |   0.79804  |
| k-d_tree_pandas      |     0.292625 |       0.576249 |   0.799234 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.297023 |        3.63154 |   0.605663 |
| Bori_Aron_solution-1 |     0.294701 |        7.28385 |   0.845371 |
| k-d_tree_sklearn     |     0.300893 |       11.0756  |   0.964226 |
| k-d_tree_polars      |     0.295176 |        4.01967 |   4.60398  |
| barab-szabi-1        |     0.300006 |        3.82766 |   4.63745  |
| k-d_tree_pandas      |     0.331532 |        2.84221 |   4.94963  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.398176 |       160.755  |    3.30681 |
| barab-szabi-2        |     0.616007 |        62.6019 |    3.4164  |
| Bori_Aron_solution-1 |     0.297636 |       129.671  |   26.2758  |