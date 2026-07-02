# 2026-07-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.97566  |       0.635169 |   0.433093 |
| barab-szabi-1        |     0.457384 |       0.411687 |   0.446297 |
| k-d_tree_polars      |     0.467505 |       0.40882  |   0.452233 |
| solution-1           |     7.18967  |       1e-06    |   0.480767 |
| k-d_tree_pandas      |     0.469609 |       0.383686 |   0.541037 |
| Bori_Aron_solution-1 |     0.462234 |       0.539113 |   0.547224 |
| k-d_tree_sklearn     |     2.87098  |       1.21811  |   1.0631   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466432 |       0.438257 |   0.432825 |
| barab-szabi-1        |     0.46721  |       0.421295 |   0.445204 |
| k-d_tree_polars      |     0.466611 |       0.417786 |   0.455573 |
| Bori_Aron_solution-1 |     0.46165  |       0.547477 |   0.540991 |
| k-d_tree_pandas      |     0.475996 |       0.384315 |   0.553913 |
| k-d_tree_sklearn     |     0.474316 |       0.989819 |   1.06367  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469688 |       0.454886 |   0.457958 |
| barab-szabi-1        |     0.469422 |       0.450765 |   0.473429 |
| k-d_tree_polars      |     0.474655 |       0.445338 |   0.497953 |
| Bori_Aron_solution-1 |     0.46292  |       0.586628 |   0.551027 |
| k-d_tree_pandas      |     0.469634 |       0.403594 |   0.594183 |
| k-d_tree_sklearn     |     0.468646 |       1.04017  |   1.09072  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473555 |       0.514975 |   0.480304 |
| Bori_Aron_solution-1 |     0.470373 |       0.768065 |   0.553236 |
| barab-szabi-1        |     0.469163 |       0.574788 |   0.576856 |
| k-d_tree_polars      |     0.466575 |       0.559357 |   0.578059 |
| k-d_tree_pandas      |     0.473279 |       0.498341 |   0.732898 |
| k-d_tree_sklearn     |     0.474162 |       1.30163  |   1.13942  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469417 |       0.732255 |   0.522405 |
| Bori_Aron_solution-1 |     0.4613   |       1.41171  |   0.580093 |
| k-d_tree_polars      |     0.466508 |       0.921704 |   0.918597 |
| barab-szabi-1        |     0.468144 |       0.922781 |   0.952051 |
| k-d_tree_pandas      |     0.467452 |       0.813602 |   1.16562  |
| k-d_tree_sklearn     |     0.475415 |       2.10917  |   1.22697  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468439 |        5.07021 |   0.7553   |
| Bori_Aron_solution-1 |     0.479205 |       11.383   |   0.845435 |
| k-d_tree_sklearn     |     0.489213 |       18.1309  |   1.40908  |
| barab-szabi-1        |     0.471109 |        5.45793 |   7.02178  |
| k-d_tree_polars      |     0.49518  |        5.40318 |   7.07726  |
| k-d_tree_pandas      |     0.504105 |        4.40487 |   7.52933  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.504408 |        77.9348 |    2.87025 |
| k-d_tree_sklearn     |     0.862042 |       239.892  |    3.97007 |
| Bori_Aron_solution-1 |     0.518362 |       151.597  |   25.9964  |