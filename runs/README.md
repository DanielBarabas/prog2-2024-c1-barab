# 2026-06-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.62278  |       1e-06    |   0.420981 |
| barab-szabi-2        |     0.464233 |       0.449432 |   0.441562 |
| k-d_tree_polars      |     0.46423  |       0.407592 |   0.447105 |
| k-d_tree_pandas      |     0.464241 |       0.383766 |   0.548475 |
| Bori_Aron_solution-1 |     0.462317 |       0.54091  |   0.563851 |
| barab-szabi-1        |     7.99031  |       0.451804 |   0.577669 |
| k-d_tree_sklearn     |     2.91168  |       1.09375  |   1.06536  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471695 |       0.445932 |   0.441666 |
| k-d_tree_polars      |     0.473316 |       0.415061 |   0.446851 |
| barab-szabi-1        |     0.472425 |       0.411041 |   0.446867 |
| k-d_tree_pandas      |     0.475487 |       0.38986  |   0.55952  |
| Bori_Aron_solution-1 |     0.463906 |       0.554611 |   0.565338 |
| k-d_tree_sklearn     |     0.4827   |       0.978389 |   1.08048  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473904 |       0.453617 |   0.450713 |
| k-d_tree_polars      |     0.473611 |       0.439414 |   0.467935 |
| barab-szabi-1        |     0.4729   |       0.437392 |   0.473589 |
| Bori_Aron_solution-1 |     0.470838 |       0.592573 |   0.548898 |
| k-d_tree_pandas      |     0.468978 |       0.412421 |   0.600543 |
| k-d_tree_sklearn     |     0.473571 |       1.02385  |   1.09734  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473771 |       0.518286 |   0.479737 |
| Bori_Aron_solution-1 |     0.464999 |       0.776633 |   0.564734 |
| k-d_tree_polars      |     0.473882 |       0.565316 |   0.575519 |
| barab-szabi-1        |     0.472508 |       0.569428 |   0.580786 |
| k-d_tree_pandas      |     0.471869 |       0.506206 |   0.735271 |
| k-d_tree_sklearn     |     0.474243 |       1.25171  |   1.146    |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471566 |       0.73129  |   0.507849 |
| Bori_Aron_solution-1 |     0.46235  |       1.44019  |   0.58527  |
| k-d_tree_polars      |     0.470787 |       0.939034 |   0.930463 |
| barab-szabi-1        |     0.483262 |       0.936964 |   0.958488 |
| k-d_tree_pandas      |     0.473937 |       0.822116 |   1.18086  |
| k-d_tree_sklearn     |     0.47464  |       2.12136  |   1.22217  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473685 |        5.0795  |   0.767542 |
| Bori_Aron_solution-1 |     0.46805  |       11.1031  |   0.827307 |
| k-d_tree_sklearn     |     0.472559 |       16.8066  |   1.31133  |
| k-d_tree_polars      |     0.476862 |        5.58159 |   6.64952  |
| barab-szabi-1        |     0.472267 |        5.50081 |   6.6802   |
| k-d_tree_pandas      |     0.476798 |        4.44317 |   7.06791  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466849 |        71.3342 |    2.8313  |
| k-d_tree_sklearn     |     0.871351 |       239.623  |    4.05223 |
| Bori_Aron_solution-1 |     0.466453 |       152.426  |   16.6165  |