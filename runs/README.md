# 2024-05-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.711278 |       0.345588 |   0.337279 |
| k-d_tree_polars      |     0.708104 |       0.403531 |   0.34726  |
| barab-szabi-1        |     8.44985  |       0.470714 |   0.359481 |
| Bori_Aron_solution-1 |     0.70223  |       0.48225  |   0.475299 |
| k-d_tree_pandas      |     0.704135 |       0.383512 |   0.475476 |
| solution-1           |     9.17405  |       1e-06    |   0.485623 |
| k-d_tree_sklearn     |     3.19389  |       0.961881 |   0.660153 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731492 |       0.35032  |   0.345428 |
| barab-szabi-1        |     0.739025 |       0.408254 |   0.350181 |
| k-d_tree_polars      |     0.738307 |       0.4146   |   0.350224 |
| Bori_Aron_solution-1 |     0.727948 |       0.488671 |   0.476099 |
| k-d_tree_pandas      |     0.737729 |       0.386831 |   0.487845 |
| k-d_tree_sklearn     |     0.740524 |       0.865817 |   0.670986 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744612 |       0.362863 |   0.356024 |
| k-d_tree_polars      |     0.757759 |       0.437703 |   0.378796 |
| barab-szabi-1        |     0.740838 |       0.433227 |   0.382291 |
| Bori_Aron_solution-1 |     0.721168 |       0.52351  |   0.482431 |
| k-d_tree_pandas      |     0.734556 |       0.402636 |   0.528747 |
| k-d_tree_sklearn     |     0.771071 |       0.88877  |   0.699055 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731902 |       0.430588 |   0.392539 |
| k-d_tree_polars      |     0.740731 |       0.545784 |   0.477221 |
| barab-szabi-1        |     0.742567 |       0.538797 |   0.485838 |
| Bori_Aron_solution-1 |     0.724303 |       0.698594 |   0.489331 |
| k-d_tree_pandas      |     0.73408  |       0.484407 |   0.670359 |
| k-d_tree_sklearn     |     0.745286 |       1.13807  |   0.752933 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.728873 |       0.680581 |   0.437502 |
| Bori_Aron_solution-1 |     0.725202 |       1.34796  |   0.516642 |
| k-d_tree_polars      |     0.736797 |       0.852249 |   0.839839 |
| barab-szabi-1        |     0.736659 |       0.857339 |   0.871762 |
| k-d_tree_sklearn     |     0.73809  |       1.93002  |   0.886274 |
| k-d_tree_pandas      |     0.73288  |       0.75209  |   1.10166  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731292 |        5.61601 |   0.751819 |
| Bori_Aron_solution-1 |     0.725267 |       10.7902  |   0.782983 |
| k-d_tree_sklearn     |     0.737075 |       16.3248  |   1.04639  |
| barab-szabi-1        |     0.741684 |        4.88101 |   6.64841  |
| k-d_tree_polars      |     0.74451  |        4.8447  |   6.71202  |
| k-d_tree_pandas      |     0.75382  |        3.8948  |   7.06282  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.962373 |        76.3664 |    3.82521 |
| k-d_tree_sklearn     |     0.833453 |       241.74   |    4.75533 |
| Bori_Aron_solution-1 |     0.722212 |       151.224  |   18.4734  |