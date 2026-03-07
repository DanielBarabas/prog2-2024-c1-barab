# 2026-03-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.563546 |       0.447998 |   0.474531 |
| barab-szabi-2        |     0.968724 |       0.473623 |   0.481488 |
| k-d_tree_pandas      |     0.535926 |       0.418026 |   0.592657 |
| Bori_Aron_solution-1 |     0.974944 |       0.587015 |   0.600557 |
| barab-szabi-1        |     8.91155  |       0.485221 |   0.682189 |
| solution-1           |     8.39391  |       1e-06    |   0.776736 |
| k-d_tree_sklearn     |     3.29167  |       1.25701  |   1.15241  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.514657 |       0.434325 |   0.460571 |
| barab-szabi-2        |     0.52343  |       0.457564 |   0.462701 |
| barab-szabi-1        |     0.51692  |       0.444274 |   0.464299 |
| Bori_Aron_solution-1 |     0.540506 |       0.592259 |   0.580482 |
| k-d_tree_pandas      |     0.511657 |       0.420721 |   0.60738  |
| k-d_tree_sklearn     |     0.519286 |       1.0621   |   1.16261  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519141 |       0.46642  |   0.467855 |
| barab-szabi-1        |     0.515373 |       0.465479 |   0.491566 |
| k-d_tree_polars      |     0.532942 |       0.482204 |   0.502333 |
| Bori_Aron_solution-1 |     0.559957 |       0.626114 |   0.58644  |
| k-d_tree_pandas      |     0.515388 |       0.443104 |   0.650264 |
| k-d_tree_sklearn     |     0.526523 |       1.08181  |   1.17405  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531252 |       0.53271  |   0.493782 |
| k-d_tree_polars      |     0.518478 |       0.593511 |   0.583844 |
| barab-szabi-1        |     0.523662 |       0.600107 |   0.598509 |
| Bori_Aron_solution-1 |     0.505021 |       0.844872 |   0.605316 |
| k-d_tree_pandas      |     0.515615 |       0.524682 |   0.767852 |
| k-d_tree_sklearn     |     0.519545 |       1.35069  |   1.23881  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51648  |       0.765941 |   0.541391 |
| Bori_Aron_solution-1 |     0.506882 |       1.50697  |   0.616361 |
| k-d_tree_polars      |     0.521222 |       0.972124 |   0.972335 |
| barab-szabi-1        |     0.520851 |       0.955026 |   1.00619  |
| k-d_tree_pandas      |     0.524184 |       0.841131 |   1.22728  |
| k-d_tree_sklearn     |     0.519511 |       2.2766   |   1.29305  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51623  |        5.43888 |   0.772115 |
| Bori_Aron_solution-1 |     0.521912 |       11.6418  |   0.871792 |
| k-d_tree_sklearn     |     0.522972 |       18.373   |   1.39317  |
| barab-szabi-1        |     0.515027 |        5.64961 |   7.0773   |
| k-d_tree_polars      |     0.522201 |        5.69468 |   7.11797  |
| k-d_tree_pandas      |     0.523584 |        4.48147 |   7.54422  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519027 |        75.7394 |    2.80529 |
| k-d_tree_sklearn     |     0.954992 |       251.952  |    4.16111 |
| Bori_Aron_solution-1 |     0.533389 |       157.105  |   21.2995  |