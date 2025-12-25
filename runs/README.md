# 2025-12-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.34596  |       1e-06    |   0.424507 |
| barab-szabi-2        |     0.516942 |       0.497375 |   0.428951 |
| barab-szabi-1        |     0.529329 |       0.407663 |   0.43139  |
| k-d_tree_polars      |     0.526895 |       0.451114 |   0.436465 |
| Bori_Aron_solution-1 |     0.519795 |       0.542354 |   0.539089 |
| k-d_tree_pandas      |     9.56994  |       0.408043 |   0.627241 |
| k-d_tree_sklearn     |     3.00563  |       1.07214  |   1.056    |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529461 |       0.428515 |   0.432137 |
| barab-szabi-1        |     0.544999 |       0.413344 |   0.435122 |
| k-d_tree_polars      |     0.531154 |       0.411427 |   0.437688 |
| k-d_tree_pandas      |     0.52721  |       0.393787 |   0.551814 |
| Bori_Aron_solution-1 |     0.519395 |       0.555576 |   0.556528 |
| k-d_tree_sklearn     |     0.527461 |       0.968002 |   1.06297  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525987 |       0.444532 |   0.451123 |
| k-d_tree_polars      |     0.526213 |       0.432873 |   0.456052 |
| barab-szabi-1        |     0.528615 |       0.43913  |   0.465915 |
| Bori_Aron_solution-1 |     0.521132 |       0.59277  |   0.540004 |
| k-d_tree_pandas      |     0.530521 |       0.412627 |   0.600058 |
| k-d_tree_sklearn     |     0.533345 |       1.019    |   1.1462   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528252 |       0.500177 |   0.470671 |
| k-d_tree_polars      |     0.525071 |       0.557372 |   0.561493 |
| Bori_Aron_solution-1 |     0.520481 |       0.781047 |   0.566267 |
| barab-szabi-1        |     0.526503 |       0.557641 |   0.567867 |
| k-d_tree_pandas      |     0.534469 |       0.500195 |   0.737066 |
| k-d_tree_sklearn     |     0.533489 |       1.24119  |   1.12958  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530168 |       0.738243 |   0.506298 |
| Bori_Aron_solution-1 |     0.524835 |       1.45938  |   0.589292 |
| k-d_tree_polars      |     0.527028 |       0.923961 |   0.916617 |
| barab-szabi-1        |     0.528629 |       0.927886 |   0.9511   |
| k-d_tree_pandas      |     0.532284 |       0.817076 |   1.18442  |
| k-d_tree_sklearn     |     0.532959 |       2.12351  |   1.22654  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533264 |        5.12256 |   0.747689 |
| Bori_Aron_solution-1 |     0.524342 |       11.3098  |   0.853332 |
| k-d_tree_sklearn     |     0.531378 |       16.7575  |   1.30897  |
| k-d_tree_polars      |     0.529132 |        5.42578 |   6.6017   |
| barab-szabi-1        |     0.530236 |        5.44734 |   6.64137  |
| k-d_tree_pandas      |     0.529167 |        4.48308 |   6.97983  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529569 |        79.2742 |    2.82006 |
| k-d_tree_sklearn     |     0.538063 |       236.419  |    4.15003 |
| Bori_Aron_solution-1 |     0.674734 |       156.849  |   18.239   |