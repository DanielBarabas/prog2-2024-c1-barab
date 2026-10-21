# 2026-10-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     4.8479   |       0        |   0.277808 |
| barab-szabi-2        |     0.284925 |       0.320925 |   0.361379 |
| barab-szabi-1        |     7.09722  |       0.357113 |   0.364678 |
| k-d_tree_polars      |     0.294387 |       0.357375 |   0.37518  |
| k-d_tree_pandas      |     0.298471 |       0.267201 |   0.380692 |
| Bori_Aron_solution-1 |     0.296867 |       0.378457 |   0.3871   |
| k-d_tree_sklearn     |     3.27305  |       0.903645 |   0.711031 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.292079 |       0.302818 |   0.287025 |
| k-d_tree_polars      |     0.292606 |       0.283215 |   0.295292 |
| barab-szabi-1        |     0.293043 |       0.370788 |   0.302031 |
| Bori_Aron_solution-1 |     0.287792 |       0.369334 |   0.357292 |
| k-d_tree_pandas      |     0.295028 |       0.255962 |   0.366938 |
| k-d_tree_sklearn     |     0.296486 |       0.659223 |   0.670182 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.287051 |       0.303902 |   0.281337 |
| barab-szabi-1        |     0.279558 |       0.30191  |   0.302807 |
| k-d_tree_polars      |     0.290673 |       0.306384 |   0.319088 |
| Bori_Aron_solution-1 |     0.263503 |       0.360854 |   0.340874 |
| k-d_tree_pandas      |     0.272019 |       0.248561 |   0.359496 |
| k-d_tree_sklearn     |     0.292538 |       0.690048 |   0.714147 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.295187 |       0.340731 |   0.309646 |
| k-d_tree_polars      |     0.290164 |       0.37079  |   0.359912 |
| barab-szabi-1        |     0.290807 |       0.369326 |   0.378366 |
| Bori_Aron_solution-1 |     0.287665 |       0.525677 |   0.395345 |
| k-d_tree_pandas      |     0.294317 |       0.316429 |   0.453322 |
| k-d_tree_sklearn     |     0.297093 |       0.828825 |   0.742296 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.291326 |       0.484761 |   0.329651 |
| Bori_Aron_solution-1 |     0.300942 |       0.862699 |   0.379217 |
| k-d_tree_polars      |     0.292265 |       0.551041 |   0.57565  |
| barab-szabi-1        |     0.297451 |       0.549268 |   0.616732 |
| k-d_tree_pandas      |     0.302711 |       0.510102 |   0.738721 |
| k-d_tree_sklearn     |     0.320932 |       1.37535  |   0.763788 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.310457 |        3.91281 |   0.552681 |
| Bori_Aron_solution-1 |     0.282426 |        6.6644  |   0.590505 |
| k-d_tree_sklearn     |     0.315172 |       12.9751  |   0.985854 |
| k-d_tree_pandas      |     0.323712 |        2.17151 |   4.90337  |
| barab-szabi-1        |     0.278978 |        3.69703 |   4.92065  |
| k-d_tree_polars      |     0.300283 |        3.52007 |   4.95245  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.415588 |       148.442  |    2.12896 |
| barab-szabi-2        |     0.47322  |        59.0597 |    2.17452 |
| Bori_Aron_solution-1 |     0.335357 |       122.097  |   21.6476  |