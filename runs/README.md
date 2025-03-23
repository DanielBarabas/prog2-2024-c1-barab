# 2025-03-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.42023  |       1e-06    |   0.350895 |
| barab-szabi-2        |     0.539302 |       0.403629 |   0.400139 |
| k-d_tree_polars      |     0.544334 |       0.393098 |   0.404902 |
| barab-szabi-1        |     0.542938 |       0.397109 |   0.408163 |
| Bori_Aron_solution-1 |     0.537758 |       0.533724 |   0.535937 |
| k-d_tree_pandas      |     7.85822  |       0.393472 |   0.567544 |
| k-d_tree_sklearn     |     3.14013  |       0.958797 |   1.02605  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55575  |       0.40308  |   0.401889 |
| barab-szabi-1        |     0.555504 |       0.39893  |   0.407267 |
| k-d_tree_polars      |     0.561224 |       0.420836 |   0.409846 |
| Bori_Aron_solution-1 |     0.54773  |       0.539563 |   0.528929 |
| k-d_tree_pandas      |     0.556379 |       0.380037 |   0.543752 |
| k-d_tree_sklearn     |     0.56059  |       0.93124  |   1.0032   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566871 |       0.418006 |   0.411398 |
| k-d_tree_polars      |     0.572324 |       0.427448 |   0.432713 |
| barab-szabi-1        |     0.556891 |       0.426938 |   0.436739 |
| Bori_Aron_solution-1 |     0.552625 |       0.575316 |   0.536994 |
| k-d_tree_pandas      |     0.564115 |       0.395909 |   0.587459 |
| k-d_tree_sklearn     |     0.56887  |       0.984123 |   1.04874  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551134 |       0.47909  |   0.441606 |
| k-d_tree_polars      |     0.558382 |       0.530706 |   0.530388 |
| barab-szabi-1        |     0.562011 |       0.528756 |   0.539351 |
| Bori_Aron_solution-1 |     0.552024 |       0.747237 |   0.559354 |
| k-d_tree_pandas      |     0.560194 |       0.478287 |   0.719786 |
| k-d_tree_sklearn     |     0.560105 |       1.19206  |   1.08308  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554522 |       0.716034 |   0.476968 |
| Bori_Aron_solution-1 |     0.548387 |       1.37358  |   0.574041 |
| k-d_tree_polars      |     0.560009 |       0.854325 |   0.875092 |
| barab-szabi-1        |     0.558326 |       0.850856 |   0.916069 |
| k-d_tree_pandas      |     0.55758  |       0.739462 |   1.1548   |
| k-d_tree_sklearn     |     0.561568 |       2.00709  |   1.17474  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554874 |        5.14355 |   0.701305 |
| Bori_Aron_solution-1 |     0.550985 |       10.2701  |   0.860558 |
| k-d_tree_sklearn     |     0.56165  |       15.5398  |   1.2834   |
| k-d_tree_polars      |     0.560437 |        4.88399 |   6.37532  |
| barab-szabi-1        |     0.559787 |        4.88251 |   6.39372  |
| k-d_tree_pandas      |     0.556402 |        3.7961  |   6.79489  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.756028 |        68.6943 |    2.63927 |
| k-d_tree_sklearn     |     0.624786 |       219.072  |    4.16507 |
| Bori_Aron_solution-1 |     0.551618 |       143.917  |   15.2845  |