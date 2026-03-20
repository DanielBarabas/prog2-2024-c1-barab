# 2026-03-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492612 |       0.447483 |   0.447467 |
| k-d_tree_polars      |     0.493072 |       0.4218   |   0.449625 |
| solution-1           |     9.03578  |       1e-06    |   0.455047 |
| Bori_Aron_solution-1 |     0.499253 |       0.556933 |   0.561896 |
| k-d_tree_pandas      |     0.520861 |       0.398271 |   0.565305 |
| barab-szabi-1        |     9.95916  |       0.458569 |   0.590909 |
| k-d_tree_sklearn     |     3.32556  |       1.10325  |   1.24424  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500275 |       0.450686 |   0.444098 |
| barab-szabi-1        |     0.505347 |       0.421721 |   0.449131 |
| k-d_tree_polars      |     0.501634 |       0.42336  |   0.451084 |
| Bori_Aron_solution-1 |     0.493539 |       0.565903 |   0.560126 |
| k-d_tree_pandas      |     0.50738  |       0.402042 |   0.572243 |
| k-d_tree_sklearn     |     0.505383 |       1.00353  |   1.09924  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.493583 |       0.44999  |   0.446166 |
| k-d_tree_polars      |     0.494433 |       0.442842 |   0.466296 |
| barab-szabi-1        |     0.491896 |       0.449794 |   0.473592 |
| Bori_Aron_solution-1 |     0.486688 |       0.604462 |   0.550811 |
| k-d_tree_pandas      |     0.513486 |       0.416565 |   0.606406 |
| k-d_tree_sklearn     |     0.499281 |       1.03189  |   1.0928   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496779 |       0.51492  |   0.476156 |
| k-d_tree_polars      |     0.495836 |       0.575127 |   0.568207 |
| Bori_Aron_solution-1 |     0.483713 |       0.793159 |   0.573071 |
| barab-szabi-1        |     0.494857 |       0.570572 |   0.580024 |
| k-d_tree_pandas      |     0.496079 |       0.519587 |   0.754477 |
| k-d_tree_sklearn     |     0.503623 |       1.28716  |   1.19227  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496943 |       0.746237 |   0.519533 |
| Bori_Aron_solution-1 |     0.487099 |       1.48403  |   0.594365 |
| k-d_tree_polars      |     0.497604 |       0.945349 |   0.935289 |
| barab-szabi-1        |     0.511266 |       0.95519  |   0.972791 |
| k-d_tree_pandas      |     0.493269 |       0.830905 |   1.18872  |
| k-d_tree_sklearn     |     0.499759 |       2.14835  |   1.22318  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521528 |        5.33788 |   0.776201 |
| Bori_Aron_solution-1 |     0.499829 |       11.7319  |   0.866891 |
| k-d_tree_sklearn     |     0.528607 |       18.3873  |   1.47397  |
| barab-szabi-1        |     0.492879 |        5.68802 |   7.12082  |
| k-d_tree_polars      |     0.525605 |        5.7662  |   7.19277  |
| k-d_tree_pandas      |     0.507524 |        4.64674 |   7.56888  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.520775 |        72.5407 |    2.70126 |
| k-d_tree_sklearn     |     0.815914 |       247.331  |    3.95961 |
| Bori_Aron_solution-1 |     0.496847 |       153.375  |   20.3786  |