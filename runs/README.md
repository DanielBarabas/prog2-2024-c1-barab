# 2024-09-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.98703  |       1e-06    |   0.382918 |
| barab-szabi-2        |     0.650871 |       0.422525 |   0.418267 |
| barab-szabi-1        |     0.649508 |       0.431196 |   0.422307 |
| k-d_tree_polars      |     4.21145  |       0.467095 |   0.427883 |
| Bori_Aron_solution-1 |     4.66034  |       0.554918 |   0.520671 |
| k-d_tree_pandas      |     0.638811 |       0.413642 |   0.580277 |
| k-d_tree_sklearn     |     3.0843   |       1.00996  |   0.752913 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.677096 |       0.42666  |   0.422986 |
| k-d_tree_polars      |     0.662885 |       0.48748  |   0.424673 |
| barab-szabi-1        |     0.655235 |       0.455623 |   0.430384 |
| Bori_Aron_solution-1 |     0.637973 |       0.582666 |   0.580655 |
| k-d_tree_pandas      |     0.659055 |       0.424335 |   0.591484 |
| k-d_tree_sklearn     |     0.670767 |       0.999799 |   0.784165 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.659786 |       0.437609 |   0.438807 |
| k-d_tree_polars      |     0.682129 |       0.469023 |   0.456525 |
| barab-szabi-1        |     0.669194 |       0.468217 |   0.461135 |
| Bori_Aron_solution-1 |     0.656835 |       0.641366 |   0.594265 |
| k-d_tree_pandas      |     0.66884  |       0.439846 |   0.630559 |
| k-d_tree_sklearn     |     0.661578 |       1.06123  |   0.814965 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.659786 |       0.509421 |   0.485178 |
| k-d_tree_polars      |     0.664008 |       0.575642 |   0.5613   |
| barab-szabi-1        |     0.678954 |       0.599134 |   0.577552 |
| Bori_Aron_solution-1 |     0.654293 |       0.812274 |   0.591532 |
| k-d_tree_pandas      |     0.666425 |       0.514065 |   0.790013 |
| k-d_tree_sklearn     |     0.668893 |       1.28437  |   0.868349 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.66779  |       1.51278  |   0.627764 |
| barab-szabi-2        |     0.651721 |       0.776366 |   0.643225 |
| k-d_tree_sklearn     |     0.673971 |       2.20842  |   0.944192 |
| k-d_tree_polars      |     0.7084   |       0.931259 |   0.945183 |
| barab-szabi-1        |     0.656485 |       0.909538 |   1.00452  |
| k-d_tree_pandas      |     0.670344 |       0.789675 |   1.27705  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.647901 |        5.94302 |   0.773618 |
| Bori_Aron_solution-1 |     0.654094 |       11.5213  |   0.878458 |
| k-d_tree_sklearn     |     0.646674 |       17.7596  |   1.04161  |
| k-d_tree_polars      |     0.67021  |        4.999   |   7.19427  |
| barab-szabi-1        |     0.642704 |        4.97582 |   7.46068  |
| k-d_tree_pandas      |     0.6394   |        3.96055 |   7.65332  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.770597 |        75.2682 |    3.77249 |
| k-d_tree_sklearn     |     1.00515  |       240.542  |    4.05247 |
| Bori_Aron_solution-1 |     0.655113 |       154.263  |   17.469   |