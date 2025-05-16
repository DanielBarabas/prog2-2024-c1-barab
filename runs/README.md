# 2025-05-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.507159 |       0.408667 |   0.411618 |
| barab-szabi-1        |     0.513397 |       0.40099  |   0.418674 |
| solution-1           |     7.36988  |       1e-06    |   0.443691 |
| k-d_tree_polars      |     7.62324  |       0.447182 |   0.543452 |
| k-d_tree_pandas      |     0.509784 |       0.3834   |   0.551045 |
| Bori_Aron_solution-1 |     0.506134 |       0.541334 |   0.568609 |
| k-d_tree_sklearn     |     3.01287  |       1.26016  |   1.04049  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521036 |       0.418153 |   0.414974 |
| barab-szabi-1        |     0.525644 |       0.420406 |   0.418014 |
| k-d_tree_polars      |     0.528127 |       0.418936 |   0.425012 |
| Bori_Aron_solution-1 |     0.518617 |       0.560594 |   0.544025 |
| k-d_tree_pandas      |     0.526595 |       0.401479 |   0.587562 |
| k-d_tree_sklearn     |     0.527076 |       0.975102 |   1.05007  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523246 |       0.424859 |   0.424349 |
| k-d_tree_polars      |     0.524785 |       0.438797 |   0.447501 |
| barab-szabi-1        |     0.520503 |       0.443996 |   0.458408 |
| Bori_Aron_solution-1 |     0.516116 |       0.59383  |   0.549709 |
| k-d_tree_pandas      |     0.524961 |       0.413346 |   0.601362 |
| k-d_tree_sklearn     |     0.528994 |       1.01035  |   1.05634  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522969 |       0.488427 |   0.454242 |
| k-d_tree_polars      |     0.519525 |       0.549639 |   0.539977 |
| barab-szabi-1        |     0.523888 |       0.54367  |   0.558584 |
| Bori_Aron_solution-1 |     0.524196 |       0.771144 |   0.565477 |
| k-d_tree_pandas      |     0.520764 |       0.489456 |   0.749607 |
| k-d_tree_sklearn     |     0.525934 |       1.24185  |   1.13999  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519825 |       0.731405 |   0.488922 |
| Bori_Aron_solution-1 |     0.515535 |       1.41326  |   0.590019 |
| k-d_tree_polars      |     0.517767 |       0.900336 |   0.903749 |
| barab-szabi-1        |     0.523556 |       0.875041 |   0.943661 |
| k-d_tree_pandas      |     0.531611 |       0.77019  |   1.18971  |
| k-d_tree_sklearn     |     0.52857  |       2.11666  |   1.22345  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525074 |        5.4265  |   0.732107 |
| Bori_Aron_solution-1 |     0.512037 |       10.8397  |   0.889746 |
| k-d_tree_sklearn     |     0.521593 |       16.5491  |   1.33333  |
| k-d_tree_polars      |     0.533062 |        5.04047 |   6.67661  |
| barab-szabi-1        |     0.526459 |        5.00795 |   6.72597  |
| k-d_tree_pandas      |     0.524839 |        3.95494 |   7.06595  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521327 |        73.7325 |    2.78429 |
| k-d_tree_sklearn     |     0.746657 |       234.069  |    4.34542 |
| Bori_Aron_solution-1 |     0.521101 |       150.389  |   16.8857  |