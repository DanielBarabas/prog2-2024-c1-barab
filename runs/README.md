# 2024-08-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.623557 |       0.422475 |   0.402719 |
| k-d_tree_polars      |     0.619402 |       0.419974 |   0.403613 |
| barab-szabi-2        |     8.06132  |       0.70711  |   0.41432  |
| Bori_Aron_solution-1 |     0.639147 |       0.545656 |   0.536032 |
| k-d_tree_pandas      |     0.612122 |       0.45547  |   0.568095 |
| solution-1           |     7.78703  |       1e-06    |   0.619227 |
| k-d_tree_sklearn     |     3.05915  |       1.21339  |   0.748517 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630837 |       0.403487 |   0.405269 |
| barab-szabi-1        |     0.632436 |       0.427775 |   0.407501 |
| k-d_tree_polars      |     0.632929 |       0.423068 |   0.410311 |
| Bori_Aron_solution-1 |     0.625157 |       0.539747 |   0.524901 |
| k-d_tree_pandas      |     0.615987 |       0.397215 |   0.551879 |
| k-d_tree_sklearn     |     0.641011 |       0.938484 |   0.73408  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625488 |       0.411743 |   0.412448 |
| k-d_tree_polars      |     0.636431 |       0.443326 |   0.429517 |
| barab-szabi-1        |     0.630508 |       0.437986 |   0.468254 |
| Bori_Aron_solution-1 |     0.624004 |       0.585773 |   0.5682   |
| k-d_tree_pandas      |     0.618442 |       0.411892 |   0.595908 |
| k-d_tree_sklearn     |     0.626058 |       0.9672   |   0.762387 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633892 |       0.470308 |   0.430484 |
| barab-szabi-1        |     0.640446 |       0.541868 |   0.536859 |
| k-d_tree_polars      |     0.657132 |       0.564322 |   0.537634 |
| Bori_Aron_solution-1 |     0.614115 |       0.770523 |   0.551993 |
| k-d_tree_pandas      |     0.621986 |       0.499053 |   0.730455 |
| k-d_tree_sklearn     |     0.619184 |       1.18165  |   0.797317 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62915  |       0.720729 |   0.479299 |
| Bori_Aron_solution-1 |     0.61114  |       1.39905  |   0.577376 |
| k-d_tree_polars      |     0.619455 |       0.856412 |   0.878428 |
| k-d_tree_sklearn     |     0.623846 |       1.99849  |   0.888427 |
| barab-szabi-1        |     0.614899 |       0.874721 |   0.907715 |
| k-d_tree_pandas      |     0.617396 |       0.753695 |   1.15291  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613085 |        5.63231 |   0.740932 |
| Bori_Aron_solution-1 |     0.642145 |       10.8258  |   0.855879 |
| k-d_tree_sklearn     |     0.620852 |       16.6747  |   1.03693  |
| k-d_tree_polars      |     0.621947 |        4.82507 |   6.66997  |
| barab-szabi-1        |     0.611053 |        4.96998 |   6.71059  |
| k-d_tree_pandas      |     0.632959 |        3.82677 |   7.09305  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62689  |        76.0605 |    3.00308 |
| k-d_tree_sklearn     |     0.670871 |       240.301  |    4.12483 |
| Bori_Aron_solution-1 |     0.732918 |       148.525  |   19.3587  |