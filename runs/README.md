# 2025-10-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.685116 |       0.586197 |   0.431384 |
| k-d_tree_polars      |     0.549835 |       0.411586 |   0.434186 |
| barab-szabi-1        |     0.54694  |       0.406497 |   0.437176 |
| solution-1           |     8.45647  |       1e-06    |   0.521934 |
| Bori_Aron_solution-1 |     0.547129 |       0.558747 |   0.551733 |
| k-d_tree_pandas      |     9.19596  |       0.439339 |   0.822604 |
| k-d_tree_sklearn     |     3.06184  |       1.39611  |   1.07233  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550363 |       0.436093 |   0.430281 |
| k-d_tree_polars      |     0.545889 |       0.419183 |   0.445091 |
| barab-szabi-1        |     0.547885 |       0.414324 |   0.445841 |
| Bori_Aron_solution-1 |     0.541298 |       0.573487 |   0.552052 |
| k-d_tree_pandas      |     0.548713 |       0.393253 |   0.55937  |
| k-d_tree_sklearn     |     0.55212  |       0.994178 |   1.10994  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550144 |       0.443238 |   0.448641 |
| k-d_tree_polars      |     0.547026 |       0.45388  |   0.458029 |
| barab-szabi-1        |     0.550753 |       0.440412 |   0.472341 |
| Bori_Aron_solution-1 |     0.541042 |       0.607433 |   0.561105 |
| k-d_tree_pandas      |     0.552015 |       0.416377 |   0.6138   |
| k-d_tree_sklearn     |     0.554598 |       1.04371  |   1.12127  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546154 |       0.510228 |   0.478398 |
| k-d_tree_polars      |     0.547637 |       0.575049 |   0.560755 |
| Bori_Aron_solution-1 |     0.540774 |       0.786028 |   0.570059 |
| barab-szabi-1        |     0.544537 |       0.571385 |   0.570938 |
| k-d_tree_pandas      |     0.550246 |       0.509219 |   0.747407 |
| k-d_tree_sklearn     |     0.553117 |       1.26669  |   1.14061  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547313 |       0.763067 |   0.5051   |
| Bori_Aron_solution-1 |     0.539461 |       1.48723  |   0.588146 |
| k-d_tree_polars      |     0.547535 |       0.934946 |   0.937422 |
| barab-szabi-1        |     0.544607 |       0.955317 |   0.956755 |
| k-d_tree_pandas      |     0.554289 |       0.832851 |   1.19484  |
| k-d_tree_sklearn     |     0.550127 |       2.18287  |   1.23133  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545661 |        5.40671 |   0.78412  |
| Bori_Aron_solution-1 |     0.540997 |       11.5215  |   0.844061 |
| k-d_tree_sklearn     |     0.557034 |       17.3148  |   1.347    |
| barab-szabi-1        |     0.548711 |        5.60094 |   6.75255  |
| k-d_tree_polars      |     0.547689 |        5.64124 |   6.75407  |
| k-d_tree_pandas      |     0.548393 |        4.58835 |   7.12746  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547287 |        76.0096 |    2.9979  |
| k-d_tree_sklearn     |     0.568214 |       248.351  |    4.25108 |
| Bori_Aron_solution-1 |     0.787344 |       149.872  |   17.6743  |