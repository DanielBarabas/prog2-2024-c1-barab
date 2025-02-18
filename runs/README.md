# 2025-02-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.592839 |       0.399281 |   0.410183 |
| barab-szabi-2        |     4.13203  |       0.45387  |   0.411041 |
| barab-szabi-1        |     0.59168  |       0.406477 |   0.415721 |
| Bori_Aron_solution-1 |     4.97708  |       0.645949 |   0.482432 |
| solution-1           |     8.06637  |       1e-06    |   0.498001 |
| k-d_tree_pandas      |     0.634734 |       0.385932 |   0.548292 |
| k-d_tree_sklearn     |     3.27974  |       1.08538  |   1.02551  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.599085 |       0.418456 |   0.408147 |
| k-d_tree_polars      |     0.59372  |       0.408604 |   0.414372 |
| barab-szabi-1        |     0.607694 |       0.427741 |   0.432612 |
| Bori_Aron_solution-1 |     0.600985 |       0.558269 |   0.557911 |
| k-d_tree_pandas      |     0.60759  |       0.408401 |   0.584094 |
| k-d_tree_sklearn     |     0.594753 |       1.0012   |   1.01992  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586727 |       0.421893 |   0.419134 |
| barab-szabi-1        |     0.593047 |       0.438346 |   0.443966 |
| k-d_tree_polars      |     0.590873 |       0.435027 |   0.447904 |
| Bori_Aron_solution-1 |     0.623584 |       0.6051   |   0.558345 |
| k-d_tree_pandas      |     0.617388 |       0.409766 |   0.627666 |
| k-d_tree_sklearn     |     0.598566 |       1.00478  |   1.08607  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600037 |       0.48131  |   0.450165 |
| k-d_tree_polars      |     0.609684 |       0.543501 |   0.529412 |
| barab-szabi-1        |     0.595602 |       0.547946 |   0.545491 |
| Bori_Aron_solution-1 |     0.583103 |       0.758177 |   0.57258  |
| k-d_tree_pandas      |     0.590862 |       0.490942 |   0.745569 |
| k-d_tree_sklearn     |     0.588752 |       1.22823  |   1.11375  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589614 |       0.724579 |   0.48207  |
| Bori_Aron_solution-1 |     0.587517 |       1.38898  |   0.590405 |
| k-d_tree_polars      |     0.590606 |       0.87146  |   0.882403 |
| barab-szabi-1        |     0.591808 |       0.876436 |   0.925393 |
| k-d_tree_pandas      |     0.585512 |       0.741934 |   1.17134  |
| k-d_tree_sklearn     |     0.592685 |       2.06476  |   1.23304  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591205 |        5.20696 |   0.751908 |
| Bori_Aron_solution-1 |     0.584433 |       10.5477  |   0.891478 |
| k-d_tree_sklearn     |     0.601964 |       16.321   |   1.32991  |
| k-d_tree_polars      |     0.587126 |        5.03049 |   6.51236  |
| barab-szabi-1        |     0.595411 |        4.97286 |   6.58739  |
| k-d_tree_pandas      |     0.595581 |        3.84077 |   6.97227  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.786721 |        77.5579 |    3.88192 |
| k-d_tree_sklearn     |     0.719026 |       249.515  |    4.44995 |
| Bori_Aron_solution-1 |     0.590675 |       151.931  |   16.5489  |