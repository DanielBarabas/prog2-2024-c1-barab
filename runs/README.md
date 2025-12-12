# 2025-12-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52583  |       0.524266 |   0.434916 |
| barab-szabi-1        |     0.538869 |       0.413424 |   0.44422  |
| k-d_tree_polars      |     0.53719  |       0.411793 |   0.466681 |
| solution-1           |     8.32955  |       1e-06    |   0.469911 |
| Bori_Aron_solution-1 |     0.539755 |       0.560787 |   0.565317 |
| k-d_tree_pandas      |     8.77817  |       0.427226 |   0.678535 |
| k-d_tree_sklearn     |     3.12723  |       1.1279   |   1.09627  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539037 |       0.444313 |   0.435371 |
| barab-szabi-1        |     0.550721 |       0.427764 |   0.441193 |
| k-d_tree_polars      |     0.535851 |       0.417357 |   0.447649 |
| Bori_Aron_solution-1 |     0.530892 |       0.57422  |   0.559723 |
| k-d_tree_pandas      |     0.56004  |       0.416485 |   0.577728 |
| k-d_tree_sklearn     |     0.568273 |       1.0347   |   1.096    |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544935 |       0.44919  |   0.45316  |
| k-d_tree_polars      |     0.541695 |       0.460828 |   0.46413  |
| barab-szabi-1        |     0.533363 |       0.453377 |   0.470115 |
| Bori_Aron_solution-1 |     0.533535 |       0.609561 |   0.567692 |
| k-d_tree_pandas      |     0.534413 |       0.424605 |   0.622496 |
| k-d_tree_sklearn     |     0.551913 |       1.05199  |   1.1142   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554497 |       0.54008  |   0.489991 |
| k-d_tree_polars      |     0.536255 |       0.56775  |   0.562778 |
| Bori_Aron_solution-1 |     0.52597  |       0.79849  |   0.568217 |
| barab-szabi-1        |     0.538843 |       0.56762  |   0.57474  |
| k-d_tree_pandas      |     0.543083 |       0.510063 |   0.744306 |
| k-d_tree_sklearn     |     0.547948 |       1.26987  |   1.16909  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546556 |       0.77219  |   0.521078 |
| Bori_Aron_solution-1 |     0.531919 |       1.48105  |   0.609581 |
| k-d_tree_polars      |     0.544999 |       0.935234 |   0.944164 |
| barab-szabi-1        |     0.543131 |       0.956554 |   0.994689 |
| k-d_tree_pandas      |     0.53291  |       0.827859 |   1.20694  |
| k-d_tree_sklearn     |     0.545492 |       2.1314   |   1.23799  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532077 |        5.40317 |   0.749365 |
| Bori_Aron_solution-1 |     0.531867 |       11.3899  |   0.84393  |
| k-d_tree_sklearn     |     0.551562 |       17.6007  |   1.41406  |
| k-d_tree_polars      |     0.540406 |        5.46454 |   6.97724  |
| barab-szabi-1        |     0.57523  |        5.39449 |   7.08314  |
| k-d_tree_pandas      |     0.53396  |        4.50394 |   7.28172  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535578 |        75.8882 |    2.74361 |
| k-d_tree_sklearn     |     0.545293 |       240.344  |    4.22009 |
| Bori_Aron_solution-1 |     0.674392 |       151.656  |   18.2048  |