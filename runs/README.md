# 2024-12-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.98671  |       1e-06    |   0.372696 |
| barab-szabi-2        |     0.63095  |       0.40626  |   0.406663 |
| barab-szabi-1        |     0.642926 |       0.417158 |   0.407961 |
| k-d_tree_polars      |     0.640121 |       0.430614 |   0.416766 |
| Bori_Aron_solution-1 |     0.62898  |       0.532504 |   0.536232 |
| k-d_tree_pandas      |     0.649271 |       0.396802 |   0.548115 |
| k-d_tree_sklearn     |    10.8102   |       1.02857  |   1.04196  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.636535 |       0.423012 |   0.411874 |
| barab-szabi-1        |     0.637328 |       0.424814 |   0.420596 |
| barab-szabi-2        |     0.639359 |       0.411618 |   0.451851 |
| Bori_Aron_solution-1 |     0.629261 |       0.552701 |   0.539272 |
| k-d_tree_pandas      |     0.636246 |       0.40956  |   0.560743 |
| k-d_tree_sklearn     |     0.689611 |       0.978265 |   1.01591  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631516 |       0.426949 |   0.424312 |
| k-d_tree_polars      |     0.636669 |       0.444904 |   0.432984 |
| barab-szabi-1        |     0.637027 |       0.446607 |   0.437928 |
| Bori_Aron_solution-1 |     0.63241  |       0.592178 |   0.555861 |
| k-d_tree_pandas      |     0.644845 |       0.425685 |   0.597987 |
| k-d_tree_sklearn     |     0.62855  |       0.98899  |   1.0529   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.652016 |       0.49636  |   0.469138 |
| k-d_tree_polars      |     0.650074 |       0.553028 |   0.535459 |
| barab-szabi-1        |     0.658293 |       0.576642 |   0.556664 |
| Bori_Aron_solution-1 |     0.648154 |       0.775832 |   0.567426 |
| k-d_tree_pandas      |     0.654979 |       0.510815 |   0.760892 |
| k-d_tree_sklearn     |     0.633075 |       1.2479   |   1.11891  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.656054 |       0.760478 |   0.523459 |
| Bori_Aron_solution-1 |     0.674196 |       1.43758  |   0.597545 |
| k-d_tree_polars      |     0.661912 |       0.89452  |   0.912288 |
| barab-szabi-1        |     0.652651 |       0.90795  |   0.972061 |
| k-d_tree_pandas      |     0.649334 |       0.776184 |   1.19601  |
| k-d_tree_sklearn     |     0.65225  |       2.17348  |   1.22383  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.640738 |        5.62756 |   0.767351 |
| Bori_Aron_solution-1 |     0.629125 |       11.1441  |   0.844432 |
| k-d_tree_sklearn     |     0.648979 |       17.5493  |   1.35646  |
| k-d_tree_polars      |     0.642275 |        4.95293 |   6.80633  |
| barab-szabi-1        |     0.659646 |        4.92185 |   6.83469  |
| k-d_tree_pandas      |     0.64673  |        3.8464  |   7.28613  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.671736 |         76.413 |    3.03035 |
| k-d_tree_sklearn     |     0.708849 |        245.684 |    4.31034 |
| Bori_Aron_solution-1 |     0.682012 |        154.222 |   18.3492  |