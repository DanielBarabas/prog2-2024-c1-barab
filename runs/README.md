# 2026-07-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481941 |       0.457614 |   0.4578   |
| k-d_tree_polars      |     0.486952 |       0.437474 |   0.469682 |
| solution-1           |     7.56526  |       1e-06    |   0.50155  |
| Bori_Aron_solution-1 |     0.474002 |       0.552553 |   0.579604 |
| k-d_tree_pandas      |     0.492098 |       0.403658 |   0.583948 |
| barab-szabi-1        |     8.03026  |       0.541858 |   0.640568 |
| k-d_tree_sklearn     |     2.9934   |       1.27703  |   1.14004  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485763 |       0.453774 |   0.452488 |
| barab-szabi-1        |     0.490883 |       0.446679 |   0.466618 |
| k-d_tree_polars      |     0.49464  |       0.452664 |   0.4871   |
| k-d_tree_pandas      |     0.482604 |       0.401181 |   0.578596 |
| Bori_Aron_solution-1 |     0.480504 |       0.581449 |   0.585089 |
| k-d_tree_sklearn     |     0.491488 |       1.03275  |   1.11791  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478609 |       0.452613 |   0.4723   |
| k-d_tree_polars      |     0.47643  |       0.448749 |   0.479074 |
| barab-szabi-1        |     0.485444 |       0.458679 |   0.486123 |
| Bori_Aron_solution-1 |     0.465871 |       0.588068 |   0.553319 |
| k-d_tree_pandas      |     0.477437 |       0.405334 |   0.608371 |
| k-d_tree_sklearn     |     0.480605 |       1.03904  |   1.12225  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470461 |       0.512223 |   0.478614 |
| Bori_Aron_solution-1 |     0.467762 |       0.798757 |   0.559402 |
| barab-szabi-1        |     0.471696 |       0.577571 |   0.580871 |
| k-d_tree_polars      |     0.481615 |       0.577686 |   0.594229 |
| k-d_tree_pandas      |     0.472165 |       0.492636 |   0.729041 |
| k-d_tree_sklearn     |     0.479044 |       1.28203  |   1.17171  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466363 |       0.726542 |   0.54065  |
| Bori_Aron_solution-1 |     0.47401  |       1.42485  |   0.597064 |
| k-d_tree_polars      |     0.469716 |       0.922036 |   0.904851 |
| barab-szabi-1        |     0.492506 |       0.927255 |   0.96731  |
| k-d_tree_pandas      |     0.466042 |       0.805308 |   1.16294  |
| k-d_tree_sklearn     |     0.479497 |       2.08515  |   1.21163  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466179 |        5.20008 |   0.749885 |
| Bori_Aron_solution-1 |     0.465037 |       11.0263  |   0.813163 |
| k-d_tree_sklearn     |     0.486992 |       17.3182  |   1.30559  |
| k-d_tree_polars      |     0.467592 |        5.3408  |   6.76254  |
| barab-szabi-1        |     0.474206 |        5.38806 |   6.81349  |
| k-d_tree_pandas      |     0.469922 |        4.29952 |   7.17036  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466117 |        71.2021 |    2.71078 |
| k-d_tree_sklearn     |     0.704238 |       252.43   |    4.27303 |
| Bori_Aron_solution-1 |     0.469132 |       144.461  |   27.0913  |