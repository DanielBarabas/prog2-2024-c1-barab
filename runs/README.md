# 2024-07-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.89344  |       1e-06    |   0.370127 |
| barab-szabi-2        |     0.541207 |       0.386965 |   0.376406 |
| barab-szabi-1        |     0.557978 |       0.393912 |   0.384629 |
| k-d_tree_polars      |     0.54055  |       0.400187 |   0.390625 |
| Bori_Aron_solution-1 |     0.542135 |       0.513874 |   0.529208 |
| k-d_tree_pandas      |     8.35734  |       0.41827  |   0.571759 |
| k-d_tree_sklearn     |     3.03745  |       0.974379 |   0.714983 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.559379 |       0.401517 |   0.384925 |
| barab-szabi-2        |     0.557886 |       0.411269 |   0.385554 |
| barab-szabi-1        |     0.553358 |       0.396853 |   0.388123 |
| Bori_Aron_solution-1 |     0.549451 |       0.519585 |   0.517716 |
| k-d_tree_pandas      |     0.572277 |       0.381943 |   0.527134 |
| k-d_tree_sklearn     |     0.560639 |       0.886694 |   0.701974 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554526 |       0.405665 |   0.396197 |
| k-d_tree_polars      |     0.560138 |       0.423884 |   0.411696 |
| barab-szabi-1        |     0.552487 |       0.429472 |   0.425712 |
| Bori_Aron_solution-1 |     0.548049 |       0.559715 |   0.518672 |
| k-d_tree_pandas      |     0.563817 |       0.409577 |   0.583144 |
| k-d_tree_sklearn     |     0.560514 |       0.938697 |   0.723669 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554319 |       0.467335 |   0.426466 |
| k-d_tree_polars      |     0.56339  |       0.535917 |   0.515166 |
| barab-szabi-1        |     0.559062 |       0.530404 |   0.525438 |
| Bori_Aron_solution-1 |     0.560533 |       0.743397 |   0.531882 |
| k-d_tree_pandas      |     0.558386 |       0.483862 |   0.713089 |
| k-d_tree_sklearn     |     0.558212 |       1.15617  |   0.782199 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553086 |       0.711965 |   0.47094  |
| Bori_Aron_solution-1 |     0.551159 |       1.37244  |   0.556299 |
| k-d_tree_polars      |     0.557715 |       0.850276 |   0.877417 |
| k-d_tree_sklearn     |     0.557812 |       1.99444  |   0.882608 |
| barab-szabi-1        |     0.55888  |       0.851686 |   0.897104 |
| k-d_tree_pandas      |     0.556375 |       0.733504 |   1.1457   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558416 |        5.36749 |   0.753598 |
| Bori_Aron_solution-1 |     0.549262 |       10.7299  |   0.853513 |
| k-d_tree_sklearn     |     0.567652 |       16.0188  |   1.04637  |
| k-d_tree_polars      |     0.564364 |        4.82542 |   6.7103   |
| barab-szabi-1        |     0.563085 |        4.88187 |   6.7165   |
| k-d_tree_pandas      |     0.55917  |        3.9063  |   7.10477  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.842556 |        73.6538 |    3.87065 |
| k-d_tree_sklearn     |     0.688427 |       228.017  |    4.35061 |
| Bori_Aron_solution-1 |     0.547498 |       148.1    |   19.2725  |