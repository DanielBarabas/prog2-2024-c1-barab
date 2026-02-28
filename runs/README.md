# 2026-02-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.26282  |       1e-06    |   0.365789 |
| barab-szabi-2        |     0.498213 |       0.431893 |   0.432092 |
| k-d_tree_polars      |     0.501724 |       0.423569 |   0.461042 |
| barab-szabi-1        |     9.05028  |       0.433297 |   0.476881 |
| Bori_Aron_solution-1 |     0.490407 |       0.557527 |   0.557832 |
| k-d_tree_pandas      |     0.498788 |       0.388879 |   0.560397 |
| k-d_tree_sklearn     |     3.1307   |       1.01137  |   1.08264  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494479 |       0.441602 |   0.441329 |
| barab-szabi-1        |     0.498714 |       0.41366  |   0.442076 |
| k-d_tree_polars      |     0.496711 |       0.417186 |   0.450384 |
| k-d_tree_pandas      |     0.497071 |       0.395089 |   0.567417 |
| Bori_Aron_solution-1 |     0.499868 |       0.568043 |   0.567878 |
| k-d_tree_sklearn     |     0.497792 |       0.985775 |   1.10373  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.493189 |       0.454484 |   0.45199  |
| barab-szabi-1        |     0.501004 |       0.444319 |   0.467269 |
| k-d_tree_polars      |     0.505779 |       0.442659 |   0.47304  |
| Bori_Aron_solution-1 |     0.501896 |       0.602039 |   0.567656 |
| k-d_tree_pandas      |     0.500559 |       0.417134 |   0.63185  |
| k-d_tree_sklearn     |     0.508366 |       1.05479  |   1.12953  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49205  |       0.515648 |   0.477956 |
| Bori_Aron_solution-1 |     0.494281 |       0.806011 |   0.567808 |
| k-d_tree_polars      |     0.491403 |       0.560061 |   0.569532 |
| barab-szabi-1        |     0.503158 |       0.563582 |   0.58011  |
| k-d_tree_pandas      |     0.49886  |       0.508749 |   0.74012  |
| k-d_tree_sklearn     |     0.517999 |       1.28173  |   1.15348  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.509435 |       0.734666 |   0.530163 |
| Bori_Aron_solution-1 |     0.502579 |       1.48219  |   0.592479 |
| k-d_tree_polars      |     0.498371 |       0.946824 |   0.909013 |
| barab-szabi-1        |     0.498816 |       0.953827 |   0.990194 |
| k-d_tree_pandas      |     0.494259 |       0.812284 |   1.18233  |
| k-d_tree_sklearn     |     0.50456  |       2.16868  |   1.22354  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496552 |        5.17229 |   0.733116 |
| Bori_Aron_solution-1 |     0.495782 |       11.0737  |   0.852911 |
| k-d_tree_sklearn     |     0.513741 |       16.9963  |   1.34747  |
| barab-szabi-1        |     0.49312  |        5.45781 |   6.59595  |
| k-d_tree_polars      |     0.505892 |        5.59292 |   6.6885   |
| k-d_tree_pandas      |     0.495471 |        4.45938 |   7.28685  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.503266 |        70.4715 |    2.63574 |
| k-d_tree_sklearn     |     0.817558 |       236.093  |    3.95    |
| Bori_Aron_solution-1 |     0.507981 |       153.674  |   14.5687  |