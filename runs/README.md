# 2024-11-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.88299  |       1e-06    |   0.390233 |
| barab-szabi-1        |     0.649183 |       0.419425 |   0.392863 |
| k-d_tree_polars      |     0.633053 |       0.417559 |   0.398023 |
| barab-szabi-2        |     0.644772 |       0.395854 |   0.404619 |
| Bori_Aron_solution-1 |     0.629114 |       0.54558  |   0.547829 |
| k-d_tree_pandas      |     0.645545 |       0.406437 |   0.564125 |
| k-d_tree_sklearn     |    12.815    |       1.07177  |   1.01228  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633924 |       0.397843 |   0.407565 |
| k-d_tree_polars      |     0.634299 |       0.422586 |   0.410741 |
| barab-szabi-1        |     0.626064 |       0.421114 |   0.412406 |
| Bori_Aron_solution-1 |     0.642982 |       0.54672  |   0.537007 |
| k-d_tree_pandas      |     0.638928 |       0.396573 |   0.552456 |
| k-d_tree_sklearn     |     0.67314  |       0.912687 |   0.988689 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625661 |       0.417269 |   0.428596 |
| k-d_tree_polars      |     0.633254 |       0.43562  |   0.435373 |
| barab-szabi-1        |     0.643219 |       0.482258 |   0.436925 |
| Bori_Aron_solution-1 |     0.631454 |       0.602531 |   0.548743 |
| k-d_tree_pandas      |     0.640597 |       0.42902  |   0.604954 |
| k-d_tree_sklearn     |     0.649499 |       0.967565 |   1.06837  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.636668 |       0.47184  |   0.452779 |
| k-d_tree_polars      |     0.636324 |       0.557417 |   0.538168 |
| barab-szabi-1        |     0.631689 |       0.559766 |   0.543041 |
| Bori_Aron_solution-1 |     0.636276 |       0.766306 |   0.557396 |
| k-d_tree_pandas      |     0.64209  |       0.499855 |   0.726258 |
| k-d_tree_sklearn     |     0.651971 |       1.21129  |   1.07519  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.628688 |       0.732028 |   0.480285 |
| Bori_Aron_solution-1 |     0.632385 |       1.4149   |   0.575457 |
| k-d_tree_polars      |     0.640513 |       0.866561 |   0.893831 |
| barab-szabi-1        |     0.643027 |       0.873512 |   0.936426 |
| k-d_tree_pandas      |     0.624411 |       0.768942 |   1.16434  |
| k-d_tree_sklearn     |     0.628859 |       2.08582  |   1.1848   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.646615 |        5.57019 |   0.769317 |
| Bori_Aron_solution-1 |     0.649723 |       11.4422  |   0.872882 |
| k-d_tree_sklearn     |     0.642988 |       16.6072  |   1.30794  |
| k-d_tree_polars      |     0.635943 |        5.01636 |   6.88637  |
| barab-szabi-1        |     0.645621 |        4.89916 |   6.9869   |
| k-d_tree_pandas      |     0.68088  |        3.93927 |   7.45041  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.651574 |        76.5925 |     3.0975 |
| k-d_tree_sklearn     |     0.650247 |       241.471  |     4.2557 |
| Bori_Aron_solution-1 |     0.646726 |       146.32   |    18.3287 |