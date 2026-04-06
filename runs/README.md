# 2026-04-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.463995 |       0.412418 |   0.434485 |
| barab-szabi-2        |     0.468044 |       0.461704 |   0.45547  |
| solution-1           |     7.99883  |       1e-06    |   0.492621 |
| k-d_tree_pandas      |     0.470917 |       0.391488 |   0.553126 |
| Bori_Aron_solution-1 |     0.45942  |       0.552853 |   0.554172 |
| barab-szabi-1        |     8.93376  |       0.45179  |   0.577032 |
| k-d_tree_sklearn     |     2.9625   |       1.17417  |   1.09512  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.469291 |       0.417023 |   0.437814 |
| barab-szabi-2        |     0.48934  |       0.446666 |   0.449155 |
| barab-szabi-1        |     0.478488 |       0.423735 |   0.458591 |
| k-d_tree_pandas      |     0.475139 |       0.3976   |   0.577419 |
| Bori_Aron_solution-1 |     0.461367 |       0.570801 |   0.595139 |
| k-d_tree_sklearn     |     0.473276 |       1.01987  |   1.10133  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462554 |       0.454774 |   0.460261 |
| k-d_tree_polars      |     0.475541 |       0.440142 |   0.471965 |
| barab-szabi-1        |     0.466242 |       0.442085 |   0.47332  |
| Bori_Aron_solution-1 |     0.458981 |       0.608055 |   0.574778 |
| k-d_tree_pandas      |     0.466905 |       0.419726 |   0.610876 |
| k-d_tree_sklearn     |     0.475487 |       1.05053  |   1.13042  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475915 |       0.517542 |   0.479788 |
| Bori_Aron_solution-1 |     0.456409 |       0.795571 |   0.57309  |
| k-d_tree_polars      |     0.475595 |       0.584519 |   0.584886 |
| barab-szabi-1        |     0.473688 |       0.587784 |   0.596835 |
| k-d_tree_pandas      |     0.466942 |       0.515865 |   0.749712 |
| k-d_tree_sklearn     |     0.501722 |       1.3356   |   1.22179  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466487 |       0.735364 |   0.570888 |
| Bori_Aron_solution-1 |     0.471016 |       1.47704  |   0.589422 |
| k-d_tree_polars      |     0.477687 |       0.955756 |   0.950876 |
| barab-szabi-1        |     0.463093 |       0.954098 |   0.970531 |
| k-d_tree_pandas      |     0.473085 |       0.829934 |   1.19784  |
| k-d_tree_sklearn     |     0.474362 |       2.20802  |   1.30817  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463431 |        5.29591 |   0.799951 |
| Bori_Aron_solution-1 |     0.468425 |       11.1562  |   0.82963  |
| k-d_tree_sklearn     |     0.470669 |       17.6598  |   1.36304  |
| barab-szabi-1        |     0.463194 |        5.48898 |   6.68563  |
| k-d_tree_polars      |     0.479748 |        5.68792 |   6.76587  |
| k-d_tree_pandas      |     0.483044 |        4.41679 |   7.21623  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.77427  |        75.4062 |    2.89339 |
| k-d_tree_sklearn     |     0.476256 |       250.55   |    3.88229 |
| Bori_Aron_solution-1 |     0.466725 |       155.212  |   18.9115  |