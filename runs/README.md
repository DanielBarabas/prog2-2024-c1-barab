# 2025-04-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.68455  |       1e-06    |   0.358926 |
| k-d_tree_polars      |     0.556744 |       0.405472 |   0.414536 |
| barab-szabi-1        |     0.55597  |       0.411119 |   0.417551 |
| barab-szabi-2        |     0.555182 |       0.463511 |   0.419937 |
| Bori_Aron_solution-1 |     0.55156  |       0.542927 |   0.549522 |
| k-d_tree_pandas      |     8.01451  |       0.411201 |   0.582367 |
| k-d_tree_sklearn     |     3.01416  |       1.02392  |   1.03413  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57012  |       0.414057 |   0.407198 |
| k-d_tree_polars      |     0.572216 |       0.450058 |   0.413585 |
| barab-szabi-1        |     0.567791 |       0.412976 |   0.415756 |
| Bori_Aron_solution-1 |     0.563078 |       0.554174 |   0.544614 |
| k-d_tree_pandas      |     0.575711 |       0.38886  |   0.566951 |
| k-d_tree_sklearn     |     0.56986  |       0.953349 |   1.0323   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575171 |       0.426226 |   0.419114 |
| k-d_tree_polars      |     0.567477 |       0.447397 |   0.438507 |
| barab-szabi-1        |     0.566759 |       0.436894 |   0.447741 |
| Bori_Aron_solution-1 |     0.563234 |       0.586807 |   0.565632 |
| k-d_tree_pandas      |     0.56754  |       0.410291 |   0.597774 |
| k-d_tree_sklearn     |     0.572301 |       1.00571  |   1.05182  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566786 |       0.486813 |   0.457713 |
| k-d_tree_polars      |     0.567335 |       0.539391 |   0.539106 |
| barab-szabi-1        |     0.573146 |       0.54222  |   0.546185 |
| Bori_Aron_solution-1 |     0.559517 |       0.76346  |   0.559522 |
| k-d_tree_pandas      |     0.578715 |       0.484163 |   0.730422 |
| k-d_tree_sklearn     |     0.568407 |       1.24041  |   1.1847   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568609 |       0.733844 |   0.484611 |
| Bori_Aron_solution-1 |     0.559522 |       1.38838  |   0.591059 |
| k-d_tree_polars      |     0.570082 |       0.866622 |   0.904099 |
| barab-szabi-1        |     0.570304 |       0.875743 |   0.933175 |
| k-d_tree_pandas      |     0.566319 |       0.753554 |   1.18147  |
| k-d_tree_sklearn     |     0.572819 |       2.06083  |   1.21656  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587339 |        5.66013 |   0.758501 |
| Bori_Aron_solution-1 |     0.56985  |       10.8364  |   0.893119 |
| k-d_tree_sklearn     |     0.598347 |       16.9728  |   1.3766   |
| barab-szabi-1        |     0.579646 |        4.94874 |   6.76072  |
| k-d_tree_polars      |     0.57595  |        5.00582 |   6.81769  |
| k-d_tree_pandas      |     0.57211  |        3.84856 |   7.11582  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.871322 |        74.0864 |    3.38573 |
| k-d_tree_sklearn     |     0.712741 |       232.621  |    4.36113 |
| Bori_Aron_solution-1 |     0.581102 |       156.47   |   16.01    |