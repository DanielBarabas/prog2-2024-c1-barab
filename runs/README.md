# 2026-10-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.455434 |       0.439906 |   0.428029 |
| k-d_tree_polars      |     0.465458 |       0.427885 |   0.441209 |
| k-d_tree_pandas      |     0.460534 |       0.385092 |   0.552068 |
| solution-1           |     8.10906  |       1e-06    |   0.552922 |
| Bori_Aron_solution-1 |     0.451483 |       0.559859 |   0.563853 |
| barab-szabi-1        |     8.5917   |       0.677082 |   0.758    |
| k-d_tree_sklearn     |     3.27747  |       1.81984  |   1.07639  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487174 |       0.44255  |   0.435566 |
| k-d_tree_polars      |     0.546166 |       0.423882 |   0.44803  |
| barab-szabi-1        |     0.479744 |       0.422348 |   0.451214 |
| k-d_tree_pandas      |     0.484333 |       0.397038 |   0.581236 |
| Bori_Aron_solution-1 |     0.485268 |       0.591319 |   0.58568  |
| k-d_tree_sklearn     |     0.487471 |       1.0418   |   1.12472  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476216 |       0.452261 |   0.446434 |
| k-d_tree_polars      |     0.487204 |       0.461552 |   0.467409 |
| barab-szabi-1        |     0.484085 |       0.467397 |   0.478455 |
| k-d_tree_pandas      |     0.487045 |       0.417463 |   0.608132 |
| Bori_Aron_solution-1 |     0.469488 |       0.599262 |   0.697603 |
| k-d_tree_sklearn     |     0.48401  |       1.09733  |   1.14012  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473189 |       0.524435 |   0.470626 |
| k-d_tree_polars      |     0.473288 |       0.573671 |   0.563343 |
| Bori_Aron_solution-1 |     0.475074 |       0.790874 |   0.573429 |
| barab-szabi-1        |     0.487714 |       0.571125 |   0.584686 |
| k-d_tree_pandas      |     0.481769 |       0.505174 |   0.742179 |
| k-d_tree_sklearn     |     0.489734 |       1.32937  |   1.18237  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483511 |       0.7619   |   0.52034  |
| Bori_Aron_solution-1 |     0.478045 |       1.46737  |   0.605463 |
| k-d_tree_polars      |     0.481233 |       0.952335 |   0.928889 |
| barab-szabi-1        |     0.482733 |       0.937161 |   0.981584 |
| k-d_tree_pandas      |     0.48203  |       0.816923 |   1.20398  |
| k-d_tree_sklearn     |     0.485104 |       2.17931  |   1.27177  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484628 |        5.11643 |   0.737344 |
| Bori_Aron_solution-1 |     0.482983 |       10.7369  |   0.831717 |
| k-d_tree_sklearn     |     0.474316 |       16.0674  |   1.32056  |
| barab-szabi-1        |     0.487423 |        5.14741 |   6.56622  |
| k-d_tree_polars      |     0.491892 |        5.34652 |   6.6131   |
| k-d_tree_pandas      |     0.478702 |        4.3625  |   6.9387   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.779117 |        72.2404 |    2.82499 |
| k-d_tree_sklearn     |     0.602747 |       237.297  |    3.88201 |
| Bori_Aron_solution-1 |     0.463574 |       154.087  |   22.528   |