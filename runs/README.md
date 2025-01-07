# 2025-01-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.587927 |       0.400136 |   0.40148  |
| barab-szabi-1        |     0.579904 |       0.397647 |   0.40217  |
| barab-szabi-2        |     0.571725 |       0.506259 |   0.443603 |
| Bori_Aron_solution-1 |     0.583247 |       0.538882 |   0.526667 |
| solution-1           |     8.13373  |       1e-06    |   0.576952 |
| k-d_tree_pandas      |     7.84625  |       0.458004 |   0.775756 |
| k-d_tree_sklearn     |     3.02866  |       1.08913  |   1.05332  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588782 |       0.411238 |   0.402067 |
| k-d_tree_polars      |     0.586734 |       0.405022 |   0.404292 |
| barab-szabi-1        |     0.620172 |       0.423145 |   0.412194 |
| k-d_tree_pandas      |     0.593986 |       0.38557  |   0.542002 |
| Bori_Aron_solution-1 |     0.593091 |       0.558425 |   0.553001 |
| k-d_tree_sklearn     |     0.600483 |       0.940974 |   1.03922  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.58935  |       0.430114 |   0.429262 |
| barab-szabi-1        |     0.586076 |       0.42968  |   0.439924 |
| barab-szabi-2        |     0.595922 |       0.415482 |   0.447518 |
| Bori_Aron_solution-1 |     0.582431 |       0.572842 |   0.530432 |
| k-d_tree_pandas      |     0.592806 |       0.405896 |   0.57854  |
| k-d_tree_sklearn     |     0.594857 |       0.990321 |   1.04412  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593501 |       0.479234 |   0.440763 |
| k-d_tree_polars      |     0.59344  |       0.529068 |   0.524062 |
| barab-szabi-1        |     0.585115 |       0.536002 |   0.542271 |
| Bori_Aron_solution-1 |     0.58232  |       0.747252 |   0.550927 |
| k-d_tree_pandas      |     0.591721 |       0.478815 |   0.744099 |
| k-d_tree_sklearn     |     0.595196 |       1.20981  |   1.09281  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583206 |       0.71917  |   0.498693 |
| Bori_Aron_solution-1 |     0.586927 |       1.37288  |   0.566174 |
| k-d_tree_polars      |     0.583808 |       0.854614 |   0.872096 |
| barab-szabi-1        |     0.598532 |       0.852327 |   0.93615  |
| k-d_tree_pandas      |     0.592545 |       0.749999 |   1.16141  |
| k-d_tree_sklearn     |     0.608659 |       2.02096  |   1.18031  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589125 |        5.54162 |   0.761988 |
| Bori_Aron_solution-1 |     0.607575 |       10.804   |   0.833317 |
| k-d_tree_sklearn     |     0.590146 |       16.6156  |   1.31113  |
| barab-szabi-1        |     0.595235 |        4.80578 |   6.81429  |
| k-d_tree_polars      |     0.584265 |        4.854   |   6.888    |
| k-d_tree_pandas      |     0.588744 |        3.83759 |   7.252    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590822 |        74.9376 |    3.07651 |
| k-d_tree_sklearn     |     0.605858 |       227.268  |    4.3872  |
| Bori_Aron_solution-1 |     0.653218 |       148.887  |   16.8555  |