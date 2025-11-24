# 2025-11-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.96432  |       2e-06    |   0.382818 |
| barab-szabi-1        |     0.524405 |       0.3976   |   0.42594  |
| k-d_tree_polars      |     0.525877 |       0.401691 |   0.42793  |
| barab-szabi-2        |     0.512283 |       0.45135  |   0.430186 |
| Bori_Aron_solution-1 |     0.520403 |       0.538556 |   0.5392   |
| k-d_tree_pandas      |     8.5113   |       0.395534 |   0.580226 |
| k-d_tree_sklearn     |     3.10707  |       1.02398  |   1.04836  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527439 |       0.42299  |   0.427463 |
| k-d_tree_polars      |     0.530369 |       0.40954  |   0.42966  |
| barab-szabi-1        |     0.529132 |       0.407079 |   0.431068 |
| Bori_Aron_solution-1 |     0.517815 |       0.547558 |   0.540401 |
| k-d_tree_pandas      |     0.557419 |       0.388829 |   0.549046 |
| k-d_tree_sklearn     |     0.529433 |       0.95768  |   1.04989  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522054 |       0.437498 |   0.437553 |
| k-d_tree_polars      |     0.52953  |       0.435131 |   0.457077 |
| barab-szabi-1        |     0.525819 |       0.434976 |   0.458333 |
| Bori_Aron_solution-1 |     0.521619 |       0.588728 |   0.552359 |
| k-d_tree_pandas      |     0.526879 |       0.411806 |   0.591222 |
| k-d_tree_sklearn     |     0.527181 |       1.01094  |   1.08559  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528695 |       0.499313 |   0.476828 |
| k-d_tree_polars      |     0.524552 |       0.554211 |   0.554096 |
| Bori_Aron_solution-1 |     0.522588 |       0.776037 |   0.557493 |
| barab-szabi-1        |     0.526228 |       0.556127 |   0.561444 |
| k-d_tree_pandas      |     0.52484  |       0.498141 |   0.73073  |
| k-d_tree_sklearn     |     0.531317 |       1.23792  |   1.12523  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52345  |       0.739914 |   0.497625 |
| Bori_Aron_solution-1 |     0.513898 |       1.44582  |   0.581036 |
| k-d_tree_polars      |     0.523681 |       0.91292  |   0.901136 |
| barab-szabi-1        |     0.527895 |       0.895149 |   0.939839 |
| k-d_tree_pandas      |     0.527463 |       0.804627 |   1.16969  |
| k-d_tree_sklearn     |     0.525336 |       2.09776  |   1.20168  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52401  |        5.32553 |   0.72989  |
| Bori_Aron_solution-1 |     0.517507 |       11.2173  |   0.845527 |
| k-d_tree_sklearn     |     0.531432 |       16.4439  |   1.3084   |
| k-d_tree_polars      |     0.524494 |        5.38472 |   6.65455  |
| barab-szabi-1        |     0.525774 |        5.41912 |   6.68142  |
| k-d_tree_pandas      |     0.52803  |        4.37154 |   7.02522  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527978 |        77.0203 |    2.65813 |
| k-d_tree_sklearn     |     0.539683 |       234.74   |    4.32901 |
| Bori_Aron_solution-1 |     0.664423 |       152.085  |   16.3875  |