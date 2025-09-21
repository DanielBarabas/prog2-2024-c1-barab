# 2025-09-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.543524 |       0.409545 |   0.425887 |
| barab-szabi-2        |     8.18057  |       0.962299 |   0.430308 |
| barab-szabi-1        |     0.528723 |       0.410697 |   0.433172 |
| Bori_Aron_solution-1 |     0.535248 |       0.548624 |   0.553167 |
| k-d_tree_pandas      |     0.530266 |       0.390301 |   0.566162 |
| solution-1           |     8.55407  |       1e-06    |   0.639552 |
| k-d_tree_sklearn     |     3.1363   |       1.19969  |   1.0533   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542203 |       0.42606  |   0.422487 |
| k-d_tree_polars      |     0.545395 |       0.441027 |   0.445723 |
| barab-szabi-1        |     0.58939  |       0.443643 |   0.467802 |
| Bori_Aron_solution-1 |     0.537593 |       0.550614 |   0.549811 |
| k-d_tree_pandas      |     0.545771 |       0.427674 |   0.5698   |
| k-d_tree_sklearn     |     0.558873 |       1.05666  |   1.0695   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548494 |       0.435271 |   0.436307 |
| barab-szabi-1        |     0.54545  |       0.448792 |   0.458979 |
| k-d_tree_polars      |     0.538015 |       0.445819 |   0.459019 |
| Bori_Aron_solution-1 |     0.533231 |       0.587914 |   0.559456 |
| k-d_tree_pandas      |     0.548883 |       0.408651 |   0.603835 |
| k-d_tree_sklearn     |     0.563203 |       1.03577  |   1.09152  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540154 |       0.499695 |   0.468607 |
| k-d_tree_polars      |     0.540751 |       0.545045 |   0.553097 |
| Bori_Aron_solution-1 |     0.540991 |       0.76512  |   0.565616 |
| barab-szabi-1        |     0.541604 |       0.552382 |   0.566117 |
| k-d_tree_pandas      |     0.585891 |       0.486338 |   0.744676 |
| k-d_tree_sklearn     |     0.5463   |       1.32107  |   1.19112  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580751 |       0.743101 |   0.503147 |
| Bori_Aron_solution-1 |     0.537198 |       1.44383  |   0.614886 |
| k-d_tree_polars      |     0.54151  |       0.902983 |   0.961882 |
| barab-szabi-1        |     0.54882  |       0.889134 |   0.981597 |
| k-d_tree_pandas      |     0.545297 |       0.765024 |   1.1946   |
| k-d_tree_sklearn     |     0.567998 |       2.12298  |   1.22133  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560124 |        5.35877 |   0.749456 |
| Bori_Aron_solution-1 |     0.538464 |       10.5109  |   0.834327 |
| k-d_tree_sklearn     |     0.54775  |       17.7083  |   1.35854  |
| k-d_tree_polars      |     0.565871 |        5.08551 |   6.57749  |
| barab-szabi-1        |     0.543364 |        5.07964 |   6.60863  |
| k-d_tree_pandas      |     0.538328 |        3.96233 |   7.15963  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571571 |        72.8649 |    2.95569 |
| k-d_tree_sklearn     |     1.2184   |       228.168  |    4.12795 |
| Bori_Aron_solution-1 |     0.584392 |       145.082  |   17.6744  |