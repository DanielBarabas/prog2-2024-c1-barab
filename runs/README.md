# 2024-04-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73408  |       0.365059 |   0.36339  |
| k-d_tree_polars      |     0.739423 |       0.429012 |   0.367375 |
| barab-szabi-1        |    10.2375   |       0.52276  |   0.380367 |
| solution-1           |     8.59562  |       1e-06    |   0.47741  |
| k-d_tree_pandas      |     0.73604  |       0.403898 |   0.502048 |
| Bori_Aron_solution-1 |     0.7305   |       0.507989 |   0.513242 |
| k-d_tree_sklearn     |     3.61497  |       0.979732 |   0.728299 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.737197 |       0.417112 |   0.351585 |
| barab-szabi-1        |     0.776822 |       0.427487 |   0.352637 |
| barab-szabi-2        |     0.738427 |       0.350813 |   0.392609 |
| Bori_Aron_solution-1 |     0.775776 |       0.502798 |   0.472659 |
| k-d_tree_pandas      |     0.769447 |       0.392611 |   0.502388 |
| k-d_tree_sklearn     |     0.763123 |       0.875402 |   0.67547  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744719 |       0.379314 |   0.359285 |
| k-d_tree_polars      |     0.748145 |       0.435134 |   0.372708 |
| barab-szabi-1        |     0.756549 |       0.435748 |   0.393311 |
| Bori_Aron_solution-1 |     0.737266 |       0.54754  |   0.494715 |
| k-d_tree_pandas      |     0.74274  |       0.411911 |   0.54956  |
| k-d_tree_sklearn     |     0.75387  |       0.895129 |   0.680007 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.737625 |       0.432241 |   0.39833  |
| k-d_tree_polars      |     0.736882 |       0.544127 |   0.474106 |
| barab-szabi-1        |     0.742726 |       0.543418 |   0.482962 |
| Bori_Aron_solution-1 |     0.722387 |       0.708018 |   0.491531 |
| k-d_tree_pandas      |     0.736343 |       0.501476 |   0.670324 |
| k-d_tree_sklearn     |     0.747129 |       1.12352  |   0.755934 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.727799 |       0.677096 |   0.430519 |
| Bori_Aron_solution-1 |     0.7288   |       1.36219  |   0.521253 |
| k-d_tree_polars      |     0.740125 |       0.865279 |   0.829541 |
| k-d_tree_sklearn     |     0.757562 |       1.90433  |   0.853983 |
| barab-szabi-1        |     0.737765 |       0.874752 |   0.876353 |
| k-d_tree_pandas      |     0.741629 |       0.768896 |   1.13097  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744987 |        5.40214 |   0.734706 |
| Bori_Aron_solution-1 |     0.751691 |       10.7722  |   0.782814 |
| k-d_tree_sklearn     |     0.739795 |       16.038   |   1.04866  |
| k-d_tree_polars      |     0.736742 |        4.98253 |   6.87118  |
| barab-szabi-1        |     0.729278 |        4.96215 |   6.91911  |
| k-d_tree_pandas      |     0.732425 |        3.88917 |   7.11603  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.04936  |        73.1925 |    3.55611 |
| k-d_tree_sklearn     |     0.928038 |       228.534  |    4.77824 |
| Bori_Aron_solution-1 |     0.720892 |       152.449  |   17.8734  |