# 2025-08-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521734 |       0.417444 |   0.417102 |
| k-d_tree_polars      |     0.543901 |       0.405964 |   0.431526 |
| barab-szabi-1        |     0.531298 |       0.407936 |   0.4532   |
| Bori_Aron_solution-1 |     0.537674 |       0.565377 |   0.591496 |
| solution-1           |     7.71486  |       1e-06    |   0.671863 |
| k-d_tree_pandas      |     7.84643  |       0.458005 |   0.780259 |
| k-d_tree_sklearn     |     2.90074  |       1.10102  |   1.06464  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540861 |       0.421168 |   0.424088 |
| barab-szabi-1        |     0.537905 |       0.406285 |   0.430094 |
| k-d_tree_polars      |     0.545106 |       0.410707 |   0.436887 |
| Bori_Aron_solution-1 |     0.539566 |       0.561655 |   0.552118 |
| k-d_tree_pandas      |     0.539657 |       0.38925  |   0.552588 |
| k-d_tree_sklearn     |     0.561327 |       0.969773 |   1.05921  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.548496 |       0.438598 |   0.455494 |
| barab-szabi-1        |     0.5481   |       0.434906 |   0.460334 |
| barab-szabi-2        |     0.544054 |       0.437212 |   0.469326 |
| Bori_Aron_solution-1 |     0.552843 |       0.585513 |   0.542841 |
| k-d_tree_pandas      |     0.541827 |       0.404857 |   0.598588 |
| k-d_tree_sklearn     |     0.549769 |       1.01195  |   1.08092  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541127 |       0.504038 |   0.463696 |
| k-d_tree_polars      |     0.542779 |       0.581124 |   0.554683 |
| barab-szabi-1        |     0.552886 |       0.543021 |   0.561463 |
| Bori_Aron_solution-1 |     0.534638 |       0.767197 |   0.574052 |
| k-d_tree_pandas      |     0.546151 |       0.485832 |   0.732688 |
| k-d_tree_sklearn     |     0.54298  |       1.23021  |   1.12661  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539891 |       0.748704 |   0.501992 |
| Bori_Aron_solution-1 |     0.537498 |       1.4067   |   0.585648 |
| k-d_tree_polars      |     0.539063 |       0.89007  |   0.907331 |
| barab-szabi-1        |     0.540914 |       0.885552 |   0.950599 |
| k-d_tree_pandas      |     0.542753 |       0.759617 |   1.1782   |
| k-d_tree_sklearn     |     0.54481  |       2.08946  |   1.217    |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548635 |        5.21919 |   0.733723 |
| Bori_Aron_solution-1 |     0.534043 |       10.5631  |   0.840333 |
| k-d_tree_sklearn     |     0.546355 |       16.185   |   1.31205  |
| barab-szabi-1        |     0.541963 |        5.00463 |   6.52947  |
| k-d_tree_polars      |     0.544008 |        4.98527 |   6.56917  |
| k-d_tree_pandas      |     0.544231 |        3.96067 |   6.94421  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543028 |        72.3267 |    2.59845 |
| k-d_tree_sklearn     |     0.54925  |       230.44   |    4.01768 |
| Bori_Aron_solution-1 |     0.609468 |       140.678  |   18.0618  |