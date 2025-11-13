# 2025-11-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468522 |       0.478675 |   0.408237 |
| barab-szabi-1        |     0.488817 |       0.390003 |   0.412852 |
| k-d_tree_polars      |     0.493062 |       0.387484 |   0.416787 |
| Bori_Aron_solution-1 |     0.471611 |       0.534185 |   0.518616 |
| solution-1           |     7.12741  |       1e-06    |   0.521096 |
| k-d_tree_pandas      |     7.96237  |       0.417205 |   0.652212 |
| k-d_tree_sklearn     |     2.76458  |       1.0549   |   0.987849 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485696 |       0.406273 |   0.41233  |
| barab-szabi-1        |     0.493225 |       0.394053 |   0.412861 |
| k-d_tree_polars      |     0.483043 |       0.397291 |   0.415586 |
| Bori_Aron_solution-1 |     0.47374  |       0.522327 |   0.510148 |
| k-d_tree_pandas      |     0.482635 |       0.374487 |   0.540805 |
| k-d_tree_sklearn     |     0.488042 |       0.932213 |   1.00422  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482148 |       0.423654 |   0.420353 |
| barab-szabi-1        |     0.485001 |       0.423162 |   0.437843 |
| k-d_tree_polars      |     0.479675 |       0.411631 |   0.43959  |
| Bori_Aron_solution-1 |     0.472566 |       0.558586 |   0.520028 |
| k-d_tree_pandas      |     0.477212 |       0.383487 |   0.559467 |
| k-d_tree_sklearn     |     0.487008 |       0.949841 |   1.0085   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480616 |       0.479637 |   0.443385 |
| k-d_tree_polars      |     0.480469 |       0.540148 |   0.523861 |
| barab-szabi-1        |     0.480709 |       0.531424 |   0.529087 |
| Bori_Aron_solution-1 |     0.469112 |       0.722503 |   0.545516 |
| k-d_tree_pandas      |     0.480264 |       0.457274 |   0.675892 |
| k-d_tree_sklearn     |     0.486748 |       1.15767  |   1.04487  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486907 |       0.712249 |   0.486463 |
| Bori_Aron_solution-1 |     0.472301 |       1.31937  |   0.566067 |
| k-d_tree_polars      |     0.487019 |       0.851306 |   0.833939 |
| barab-szabi-1        |     0.477846 |       0.858021 |   0.887087 |
| k-d_tree_pandas      |     0.485636 |       0.734162 |   1.07125  |
| k-d_tree_sklearn     |     0.48153  |       1.91928  |   1.11208  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479621 |        4.97568 |   0.69811  |
| Bori_Aron_solution-1 |     0.474027 |       10.0267  |   0.911711 |
| k-d_tree_sklearn     |     0.484311 |       14.234   |   1.2724   |
| barab-szabi-1        |     0.483196 |        4.84061 |   6.15726  |
| k-d_tree_polars      |     0.478939 |        4.85056 |   6.19806  |
| k-d_tree_pandas      |     0.481722 |        3.81177 |   6.46113  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477976 |        65.6544 |    2.73308 |
| k-d_tree_sklearn     |     0.503527 |       175.144  |    4.41752 |
| Bori_Aron_solution-1 |     0.621487 |       140.593  |   15.6539  |