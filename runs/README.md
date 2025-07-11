# 2025-07-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.559482 |       0.418462 |   0.432658 |
| barab-szabi-2        |     0.565873 |       0.433039 |   0.432736 |
| solution-1           |     7.79038  |       1e-06    |   0.434281 |
| k-d_tree_polars      |     0.56747  |       0.4136   |   0.436623 |
| Bori_Aron_solution-1 |     0.555459 |       0.559438 |   0.557256 |
| k-d_tree_pandas      |     0.565257 |       0.396981 |   0.566876 |
| k-d_tree_sklearn     |    10.542    |       1.23512  |   1.06977  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.566936 |       0.421738 |   0.433691 |
| barab-szabi-2        |     0.566381 |       0.442935 |   0.436851 |
| k-d_tree_polars      |     0.564487 |       0.417662 |   0.438114 |
| Bori_Aron_solution-1 |     0.564781 |       0.567973 |   0.562712 |
| k-d_tree_pandas      |     0.557622 |       0.397088 |   0.579758 |
| k-d_tree_sklearn     |     0.572233 |       1.00931  |   1.08542  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567593 |       0.439333 |   0.445305 |
| k-d_tree_polars      |     0.56827  |       0.446596 |   0.464098 |
| barab-szabi-1        |     0.561848 |       0.449095 |   0.464361 |
| Bori_Aron_solution-1 |     0.561175 |       0.598103 |   0.560396 |
| k-d_tree_pandas      |     0.577235 |       0.416    |   0.607499 |
| k-d_tree_sklearn     |     0.566648 |       1.06264  |   1.12007  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560346 |       0.504097 |   0.479575 |
| k-d_tree_polars      |     0.562918 |       0.558228 |   0.560328 |
| barab-szabi-1        |     0.562572 |       0.550627 |   0.564903 |
| Bori_Aron_solution-1 |     0.555438 |       0.775186 |   0.573314 |
| k-d_tree_pandas      |     0.567296 |       0.494856 |   0.745604 |
| k-d_tree_sklearn     |     0.567295 |       1.27258  |   1.16405  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564494 |       0.75933  |   0.508511 |
| Bori_Aron_solution-1 |     0.56032  |       1.431    |   0.592752 |
| k-d_tree_polars      |     0.566119 |       0.888499 |   0.932451 |
| barab-szabi-1        |     0.565776 |       0.891828 |   0.973457 |
| k-d_tree_pandas      |     0.567499 |       0.775228 |   1.20899  |
| k-d_tree_sklearn     |     0.563392 |       2.14012  |   1.27806  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565078 |        5.61575 |   0.748712 |
| Bori_Aron_solution-1 |     0.558888 |       10.9913  |   0.867012 |
| k-d_tree_sklearn     |     0.563959 |       17.1736  |   1.3269   |
| k-d_tree_polars      |     0.568822 |        4.95286 |   6.97102  |
| barab-szabi-1        |     0.562299 |        5.03801 |   7.0024   |
| k-d_tree_pandas      |     0.571138 |        3.99348 |   7.35585  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571805 |        72.9236 |    2.65437 |
| k-d_tree_sklearn     |     0.567486 |       234.497  |    3.96388 |
| Bori_Aron_solution-1 |     0.568975 |       142.183  |   17.5158  |