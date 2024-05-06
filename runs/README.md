# 2024-05-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.706454 |       0.343288 |   0.340487 |
| k-d_tree_polars      |     0.702521 |       0.404376 |   0.345761 |
| barab-szabi-1        |     9.89178  |       0.437352 |   0.356112 |
| solution-1           |     8.45425  |       1e-06    |   0.409642 |
| Bori_Aron_solution-1 |     0.718055 |       0.481511 |   0.476506 |
| k-d_tree_pandas      |     0.713087 |       0.385754 |   0.482452 |
| k-d_tree_sklearn     |     3.45466  |       0.923313 |   0.659579 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735563 |       0.351218 |   0.346654 |
| k-d_tree_polars      |     0.749958 |       0.416703 |   0.34881  |
| barab-szabi-1        |     0.741887 |       0.41106  |   0.353034 |
| k-d_tree_pandas      |     0.73999  |       0.393589 |   0.492286 |
| Bori_Aron_solution-1 |     0.730853 |       0.481222 |   0.506735 |
| k-d_tree_sklearn     |     0.745566 |       0.856829 |   0.665586 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734277 |       0.366317 |   0.365572 |
| k-d_tree_polars      |     0.751535 |       0.436299 |   0.380908 |
| barab-szabi-1        |     0.741422 |       0.439687 |   0.381959 |
| Bori_Aron_solution-1 |     0.72419  |       0.52282  |   0.475027 |
| k-d_tree_pandas      |     0.75209  |       0.407128 |   0.53194  |
| k-d_tree_sklearn     |     0.748326 |       0.896657 |   0.698282 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743833 |       0.434686 |   0.394711 |
| k-d_tree_polars      |     0.738994 |       0.537268 |   0.490789 |
| Bori_Aron_solution-1 |     0.727801 |       0.703716 |   0.491612 |
| barab-szabi-1        |     0.735886 |       0.549385 |   0.493075 |
| k-d_tree_pandas      |     0.748962 |       0.484195 |   0.67207  |
| k-d_tree_sklearn     |     0.754651 |       1.15045  |   0.752431 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734706 |       0.68543  |   0.429788 |
| Bori_Aron_solution-1 |     0.729047 |       1.34186  |   0.517188 |
| k-d_tree_polars      |     0.74036  |       0.862607 |   0.829737 |
| k-d_tree_sklearn     |     0.74775  |       1.93242  |   0.856845 |
| barab-szabi-1        |     0.739478 |       0.856517 |   0.864313 |
| k-d_tree_pandas      |     0.733526 |       0.751486 |   1.10242  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.741282 |        5.37115 |   0.766161 |
| Bori_Aron_solution-1 |     0.728088 |       10.6647  |   0.78422  |
| k-d_tree_sklearn     |     0.74277  |       15.9775  |   1.0612   |
| barab-szabi-1        |     0.737616 |        4.85289 |   6.6038   |
| k-d_tree_polars      |     0.735266 |        4.90413 |   6.62788  |
| k-d_tree_pandas      |     0.734442 |        3.89137 |   6.89945  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.948784 |        76.4466 |    3.85831 |
| k-d_tree_sklearn     |     0.832876 |       241.126  |    4.94537 |
| Bori_Aron_solution-1 |     0.735466 |       149.014  |   18.5209  |