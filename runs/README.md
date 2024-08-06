# 2024-08-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.619459 |       0.430094 |   0.391256 |
| barab-szabi-2        |     0.622846 |       0.389711 |   0.392863 |
| k-d_tree_polars      |     0.626723 |       0.405729 |   0.399984 |
| solution-1           |     8.02797  |       1e-06    |   0.510679 |
| Bori_Aron_solution-1 |     0.613567 |       0.544264 |   0.550137 |
| k-d_tree_pandas      |     8.23237  |       0.420958 |   0.683228 |
| k-d_tree_sklearn     |     3.10997  |       1.10606  |   0.717361 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60319  |       0.389158 |   0.38818  |
| k-d_tree_polars      |     0.604499 |       0.398179 |   0.398393 |
| barab-szabi-1        |     0.61281  |       0.416182 |   0.418863 |
| Bori_Aron_solution-1 |     0.609166 |       0.537582 |   0.510336 |
| k-d_tree_pandas      |     0.624976 |       0.394762 |   0.545204 |
| k-d_tree_sklearn     |     0.616461 |       0.929229 |   0.724673 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626867 |       0.428183 |   0.406443 |
| k-d_tree_polars      |     0.608163 |       0.422788 |   0.419444 |
| barab-szabi-1        |     0.645665 |       0.457973 |   0.442301 |
| Bori_Aron_solution-1 |     0.621236 |       0.565147 |   0.533158 |
| k-d_tree_pandas      |     0.615673 |       0.394871 |   0.567877 |
| k-d_tree_sklearn     |     0.617156 |       0.933259 |   0.723594 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.647205 |       0.466463 |   0.427016 |
| barab-szabi-1        |     0.624135 |       0.528772 |   0.522943 |
| Bori_Aron_solution-1 |     0.615871 |       0.744156 |   0.54726  |
| k-d_tree_polars      |     0.622667 |       0.544668 |   0.548189 |
| k-d_tree_pandas      |     0.644712 |       0.504684 |   0.732754 |
| k-d_tree_sklearn     |     0.629775 |       1.17334  |   0.794389 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617746 |       0.718847 |   0.467172 |
| Bori_Aron_solution-1 |     0.618927 |       1.38664  |   0.560772 |
| k-d_tree_polars      |     0.610264 |       0.852482 |   0.86537  |
| barab-szabi-1        |     0.622764 |       0.864279 |   0.892925 |
| k-d_tree_sklearn     |     0.61052  |       2.03675  |   0.894152 |
| k-d_tree_pandas      |     0.607196 |       0.740209 |   1.1477   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621559 |        5.34359 |   0.725692 |
| Bori_Aron_solution-1 |     0.637419 |       10.6085  |   0.857681 |
| k-d_tree_sklearn     |     0.649054 |       16.0214  |   0.988062 |
| k-d_tree_polars      |     0.619556 |        4.8261  |   6.55139  |
| barab-szabi-1        |     0.620406 |        4.84726 |   6.61071  |
| k-d_tree_pandas      |     0.610705 |        3.88649 |   7.19022  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.814018 |        73.4831 |    3.2396  |
| k-d_tree_sklearn     |     0.610695 |       235.505  |    3.73454 |
| Bori_Aron_solution-1 |     0.617514 |       147.982  |   18.029   |