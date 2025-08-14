# 2025-08-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530674 |       0.417479 |   0.4252   |
| k-d_tree_polars      |     0.542881 |       0.414085 |   0.429038 |
| barab-szabi-1        |     0.741394 |       0.449123 |   0.49455  |
| Bori_Aron_solution-1 |     0.538895 |       0.544096 |   0.564303 |
| solution-1           |     8.10582  |       1e-06    |   0.627289 |
| k-d_tree_pandas      |     8.49743  |       0.436071 |   0.838815 |
| k-d_tree_sklearn     |     3.09802  |       1.2387   |   1.06434  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545791 |       0.427847 |   0.431019 |
| k-d_tree_polars      |     0.536158 |       0.407578 |   0.431815 |
| barab-szabi-1        |     0.572995 |       0.431083 |   0.444537 |
| Bori_Aron_solution-1 |     0.533399 |       0.555474 |   0.540423 |
| k-d_tree_pandas      |     0.552717 |       0.394127 |   0.560427 |
| k-d_tree_sklearn     |     0.548309 |       0.98407  |   1.05848  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535903 |       0.434    |   0.437864 |
| k-d_tree_polars      |     0.541363 |       0.43475  |   0.453357 |
| barab-szabi-1        |     0.534561 |       0.435591 |   0.459251 |
| Bori_Aron_solution-1 |     0.539672 |       0.591898 |   0.547977 |
| k-d_tree_pandas      |     0.536409 |       0.408373 |   0.596959 |
| k-d_tree_sklearn     |     0.542722 |       1.03497  |   1.09144  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537711 |       0.500013 |   0.464905 |
| k-d_tree_polars      |     0.542397 |       0.55578  |   0.558572 |
| barab-szabi-1        |     0.538512 |       0.544532 |   0.559359 |
| Bori_Aron_solution-1 |     0.533049 |       0.767637 |   0.563585 |
| k-d_tree_pandas      |     0.532421 |       0.487902 |   0.72738  |
| k-d_tree_sklearn     |     0.53889  |       1.22934  |   1.13986  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547537 |       0.734471 |   0.493076 |
| Bori_Aron_solution-1 |     0.52932  |       1.40434  |   0.593464 |
| k-d_tree_polars      |     0.535055 |       0.890901 |   0.900414 |
| barab-szabi-1        |     0.54321  |       0.892774 |   0.9472   |
| k-d_tree_pandas      |     0.536404 |       0.762356 |   1.17415  |
| k-d_tree_sklearn     |     0.536327 |       2.05574  |   1.203    |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53623  |        5.34457 |   0.764084 |
| Bori_Aron_solution-1 |     0.536711 |       10.5467  |   0.845198 |
| k-d_tree_sklearn     |     0.547029 |       16.2165  |   1.30663  |
| barab-szabi-1        |     0.537317 |        5.0604  |   6.48986  |
| k-d_tree_polars      |     0.537849 |        5.01352 |   6.53474  |
| k-d_tree_pandas      |     0.535942 |        3.88866 |   6.87434  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541002 |        78.0433 |    2.83894 |
| k-d_tree_sklearn     |     0.555626 |       244.053  |    4.27801 |
| Bori_Aron_solution-1 |     0.646696 |       151.377  |   16.008   |