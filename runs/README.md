# 2025-04-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552824 |       0.411372 |   0.407725 |
| k-d_tree_polars      |     0.555421 |       0.410146 |   0.413436 |
| barab-szabi-1        |     0.561845 |       0.420668 |   0.474217 |
| solution-1           |     8.35486  |       1e-06    |   0.530524 |
| Bori_Aron_solution-1 |     0.559062 |       0.556517 |   0.559472 |
| k-d_tree_pandas      |     8.32091  |       0.447593 |   0.749072 |
| k-d_tree_sklearn     |     3.1511   |       1.08106  |   1.04058  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58827  |       0.416768 |   0.408962 |
| k-d_tree_polars      |     0.574088 |       0.417217 |   0.420747 |
| barab-szabi-1        |     0.578743 |       0.420474 |   0.434614 |
| Bori_Aron_solution-1 |     0.557675 |       0.560589 |   0.551652 |
| k-d_tree_pandas      |     0.565676 |       0.394881 |   0.570004 |
| k-d_tree_sklearn     |     0.572396 |       0.987103 |   1.04197  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565268 |       0.430602 |   0.424842 |
| barab-szabi-1        |     0.575808 |       0.435906 |   0.449847 |
| k-d_tree_polars      |     0.566567 |       0.439031 |   0.50114  |
| Bori_Aron_solution-1 |     0.560589 |       0.589432 |   0.559667 |
| k-d_tree_pandas      |     0.570881 |       0.40992  |   0.611341 |
| k-d_tree_sklearn     |     0.574727 |       1.02049  |   1.05546  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570591 |       0.488182 |   0.456145 |
| k-d_tree_polars      |     0.570036 |       0.539752 |   0.54233  |
| barab-szabi-1        |     0.574262 |       0.541202 |   0.553976 |
| Bori_Aron_solution-1 |     0.573685 |       0.754912 |   0.563936 |
| k-d_tree_pandas      |     0.570487 |       0.483709 |   0.741874 |
| k-d_tree_sklearn     |     0.574096 |       1.22934  |   1.13138  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565068 |       0.72731  |   0.484411 |
| Bori_Aron_solution-1 |     0.562163 |       1.39282  |   0.59148  |
| k-d_tree_polars      |     0.568101 |       0.863457 |   0.890959 |
| barab-szabi-1        |     0.568483 |       0.869343 |   0.931426 |
| k-d_tree_pandas      |     0.564108 |       0.743927 |   1.17715  |
| k-d_tree_sklearn     |     0.570225 |       2.07615  |   1.22718  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56702  |        5.24238 |   0.743159 |
| Bori_Aron_solution-1 |     0.57605  |       10.5779  |   0.885753 |
| k-d_tree_sklearn     |     0.570746 |       16.0808  |   1.34511  |
| barab-szabi-1        |     0.572422 |        4.93587 |   6.53724  |
| k-d_tree_polars      |     0.59228  |        4.94416 |   6.55929  |
| k-d_tree_pandas      |     0.569094 |        3.85588 |   6.94872  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.757005 |        74.7493 |    2.88383 |
| k-d_tree_sklearn     |     0.655622 |       235.517  |    4.35411 |
| Bori_Aron_solution-1 |     0.563179 |       153.524  |   17.5004  |