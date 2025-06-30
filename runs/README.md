# 2025-06-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567939 |       0.43666  |   0.429592 |
| barab-szabi-1        |     0.848649 |       0.413456 |   0.435914 |
| k-d_tree_polars      |     0.564867 |       0.416068 |   0.442294 |
| solution-1           |     8.44568  |       1e-06    |   0.500248 |
| Bori_Aron_solution-1 |     0.552659 |       0.560144 |   0.554929 |
| k-d_tree_pandas      |     0.566306 |       0.392109 |   0.563439 |
| k-d_tree_sklearn     |    10.686    |       1.4211   |   1.09175  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557732 |       0.43286  |   0.434423 |
| k-d_tree_polars      |     0.570924 |       0.431606 |   0.446691 |
| barab-szabi-1        |     0.561993 |       0.41459  |   0.45519  |
| Bori_Aron_solution-1 |     0.554292 |       0.568029 |   0.556395 |
| k-d_tree_pandas      |     0.572294 |       0.395482 |   0.565058 |
| k-d_tree_sklearn     |     0.557858 |       1.0102   |   1.10255  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565835 |       0.447547 |   0.453376 |
| k-d_tree_polars      |     0.561738 |       0.440737 |   0.46072  |
| barab-szabi-1        |     0.560236 |       0.441532 |   0.467228 |
| Bori_Aron_solution-1 |     0.562476 |       0.607962 |   0.571365 |
| k-d_tree_pandas      |     0.554353 |       0.422856 |   0.608861 |
| k-d_tree_sklearn     |     0.563299 |       1.05209  |   1.10304  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552172 |       0.49784  |   0.464031 |
| k-d_tree_polars      |     0.554287 |       0.55815  |   0.550194 |
| Bori_Aron_solution-1 |     0.540118 |       0.76296  |   0.561179 |
| barab-szabi-1        |     0.56046  |       0.556342 |   0.56568  |
| k-d_tree_pandas      |     0.617183 |       0.490778 |   0.731897 |
| k-d_tree_sklearn     |     0.566586 |       1.26755  |   1.14447  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549031 |       0.730903 |   0.491303 |
| Bori_Aron_solution-1 |     0.543731 |       1.39103  |   0.590165 |
| k-d_tree_polars      |     0.550384 |       0.868603 |   0.882362 |
| barab-szabi-1        |     0.546766 |       0.878781 |   0.928163 |
| k-d_tree_pandas      |     0.551804 |       0.758053 |   1.15771  |
| k-d_tree_sklearn     |     0.556504 |       2.04148  |   1.20032  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58828  |        5.58976 |   0.779383 |
| Bori_Aron_solution-1 |     0.593469 |       10.8048  |   0.861339 |
| k-d_tree_sklearn     |     0.565125 |       16.3795  |   1.346    |
| barab-szabi-1        |     0.569404 |        4.99681 |   6.81043  |
| k-d_tree_polars      |     0.573568 |        5.05352 |   7.01206  |
| k-d_tree_pandas      |     0.582717 |        4.02335 |   7.44333  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.575508 |       232.566  |    3.93805 |
| barab-szabi-2        |     0.560915 |        81.8541 |    4.91297 |
| Bori_Aron_solution-1 |     0.592047 |       151.056  |   18.0983  |