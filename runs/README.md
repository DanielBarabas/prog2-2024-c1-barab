# 2026-04-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.78468  |       1e-06    |   0.372086 |
| barab-szabi-2        |     0.463517 |       0.432687 |   0.431934 |
| k-d_tree_polars      |     0.481317 |       0.410132 |   0.442086 |
| barab-szabi-1        |     9.56774  |       0.424815 |   0.477965 |
| k-d_tree_pandas      |     0.459243 |       0.381153 |   0.540631 |
| Bori_Aron_solution-1 |     0.468125 |       0.544993 |   0.543759 |
| k-d_tree_sklearn     |     3.21165  |       1.08139  |   1.093    |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463063 |       0.438919 |   0.437809 |
| barab-szabi-1        |     0.466585 |       0.409511 |   0.438506 |
| k-d_tree_polars      |     0.463806 |       0.412417 |   0.448478 |
| Bori_Aron_solution-1 |     0.452286 |       0.561964 |   0.545525 |
| k-d_tree_pandas      |     0.461738 |       0.390442 |   0.555402 |
| k-d_tree_sklearn     |     0.461796 |       0.970522 |   1.05585  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473041 |       0.468767 |   0.468453 |
| k-d_tree_polars      |     0.465899 |       0.436472 |   0.469538 |
| barab-szabi-1        |     0.462862 |       0.435951 |   0.474181 |
| Bori_Aron_solution-1 |     0.461964 |       0.602817 |   0.55159  |
| k-d_tree_pandas      |     0.479928 |       0.437903 |   0.625199 |
| k-d_tree_sklearn     |     0.466066 |       1.05655  |   1.08974  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461823 |       0.502258 |   0.476121 |
| k-d_tree_polars      |     0.464576 |       0.55519  |   0.554722 |
| Bori_Aron_solution-1 |     0.461351 |       0.803392 |   0.557431 |
| barab-szabi-1        |     0.46694  |       0.560137 |   0.579253 |
| k-d_tree_pandas      |     0.468062 |       0.498461 |   0.735109 |
| k-d_tree_sklearn     |     0.467697 |       1.26159  |   1.13836  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46089  |       0.760873 |   0.519496 |
| Bori_Aron_solution-1 |     0.456812 |       1.47194  |   0.589747 |
| barab-szabi-1        |     0.472109 |       0.924532 |   0.946822 |
| k-d_tree_polars      |     0.465121 |       0.946657 |   0.949348 |
| k-d_tree_pandas      |     0.465057 |       0.811876 |   1.20359  |
| k-d_tree_sklearn     |     0.467923 |       2.15835  |   1.23031  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462968 |        5.27743 |   0.749179 |
| Bori_Aron_solution-1 |     0.451987 |       11.2216  |   0.811486 |
| k-d_tree_sklearn     |     0.479208 |       17.1211  |   1.29244  |
| barab-szabi-1        |     0.464493 |        5.57027 |   6.76342  |
| k-d_tree_polars      |     0.461804 |        5.5892  |   6.80492  |
| k-d_tree_pandas      |     0.464182 |        4.50101 |   7.11459  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.749265 |        69.9177 |    2.68288 |
| k-d_tree_sklearn     |     0.462737 |       236.045  |    3.91167 |
| Bori_Aron_solution-1 |     0.458908 |       153.363  |   17.6768  |