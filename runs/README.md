# 2026-03-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48591  |       0.433393 |   0.43285  |
| k-d_tree_polars      |     0.483893 |       0.40619  |   0.44793  |
| Bori_Aron_solution-1 |     0.477939 |       0.550665 |   0.558477 |
| k-d_tree_pandas      |     0.489168 |       0.381492 |   0.560554 |
| solution-1           |     7.56881  |       2e-06    |   0.805323 |
| barab-szabi-1        |     8.0829   |       0.548336 |   0.829247 |
| k-d_tree_sklearn     |     3.0172   |       1.44283  |   1.06202  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488237 |       0.44081  |   0.436156 |
| k-d_tree_polars      |     0.491885 |       0.408725 |   0.439262 |
| barab-szabi-1        |     0.490357 |       0.408572 |   0.45139  |
| Bori_Aron_solution-1 |     0.484333 |       0.559984 |   0.549428 |
| k-d_tree_pandas      |     0.489387 |       0.394075 |   0.557119 |
| k-d_tree_sklearn     |     0.497673 |       0.983903 |   1.07409  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487163 |       0.455843 |   0.450425 |
| k-d_tree_polars      |     0.489478 |       0.440031 |   0.469577 |
| barab-szabi-1        |     0.490757 |       0.458478 |   0.478056 |
| Bori_Aron_solution-1 |     0.484287 |       0.603288 |   0.55126  |
| k-d_tree_pandas      |     0.490481 |       0.410768 |   0.595821 |
| k-d_tree_sklearn     |     0.493467 |       1.02105  |   1.08764  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488664 |       0.508194 |   0.480516 |
| k-d_tree_polars      |     0.489851 |       0.564156 |   0.557836 |
| Bori_Aron_solution-1 |     0.483594 |       0.782677 |   0.571363 |
| barab-szabi-1        |     0.490455 |       0.565706 |   0.597335 |
| k-d_tree_pandas      |     0.491223 |       0.504448 |   0.739136 |
| k-d_tree_sklearn     |     0.492871 |       1.26608  |   1.14793  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486934 |       0.72776  |   0.510571 |
| Bori_Aron_solution-1 |     0.483807 |       1.47298  |   0.590509 |
| k-d_tree_polars      |     0.489552 |       0.931617 |   0.911162 |
| barab-szabi-1        |     0.49176  |       0.945124 |   0.946747 |
| k-d_tree_pandas      |     0.490834 |       0.830013 |   1.16959  |
| k-d_tree_sklearn     |     0.489983 |       2.12061  |   1.21369  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490376 |        4.94871 |   0.76497  |
| Bori_Aron_solution-1 |     0.479794 |       11.1036  |   0.826292 |
| k-d_tree_sklearn     |     0.511072 |       16.7623  |   1.30532  |
| k-d_tree_polars      |     0.490953 |        5.55307 |   6.43975  |
| barab-szabi-1        |     0.48915  |        5.66507 |   6.47159  |
| k-d_tree_pandas      |     0.488165 |        4.62556 |   7.07831  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487777 |        71.7318 |    2.80239 |
| k-d_tree_sklearn     |     0.744918 |       240.511  |    3.79439 |
| Bori_Aron_solution-1 |     0.492624 |       153.953  |   16.2705  |