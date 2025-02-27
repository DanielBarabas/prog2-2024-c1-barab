# 2025-02-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.85813  |       1e-06    |   0.414298 |
| barab-szabi-2        |     0.609151 |       0.432906 |   0.435265 |
| barab-szabi-1        |     0.606882 |       0.430044 |   0.439797 |
| k-d_tree_polars      |     0.599144 |       0.430337 |   0.458341 |
| Bori_Aron_solution-1 |     0.587317 |       0.569561 |   0.574014 |
| k-d_tree_pandas      |     8.21344  |       0.441573 |   0.65844  |
| k-d_tree_sklearn     |     3.32001  |       1.09723  |   1.10468  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621429 |       0.440773 |   0.436714 |
| barab-szabi-1        |     0.615061 |       0.43705  |   0.438458 |
| k-d_tree_polars      |     0.628914 |       0.437014 |   0.44194  |
| Bori_Aron_solution-1 |     0.639787 |       0.594425 |   0.588722 |
| k-d_tree_pandas      |     0.623975 |       0.41491  |   0.590686 |
| k-d_tree_sklearn     |     0.62988  |       1.01631  |   1.0978   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613525 |       0.447468 |   0.442755 |
| barab-szabi-1        |     0.614071 |       0.468311 |   0.461275 |
| k-d_tree_polars      |     0.62123  |       0.458275 |   0.477401 |
| Bori_Aron_solution-1 |     0.631983 |       0.616844 |   0.584119 |
| k-d_tree_pandas      |     0.61545  |       0.435332 |   0.635109 |
| k-d_tree_sklearn     |     0.616619 |       1.08238  |   1.14592  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619401 |       0.512437 |   0.468924 |
| k-d_tree_polars      |     0.621783 |       0.562796 |   0.5513   |
| barab-szabi-1        |     0.616329 |       0.56753  |   0.564457 |
| Bori_Aron_solution-1 |     0.614121 |       0.799914 |   0.607866 |
| k-d_tree_pandas      |     0.616122 |       0.510263 |   0.762056 |
| k-d_tree_sklearn     |     0.62584  |       1.28339  |   1.20006  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619052 |       0.788131 |   0.565677 |
| Bori_Aron_solution-1 |     0.600539 |       1.44905  |   0.612239 |
| k-d_tree_polars      |     0.61084  |       0.904089 |   0.942671 |
| barab-szabi-1        |     0.615909 |       0.89553  |   0.981971 |
| k-d_tree_pandas      |     0.623654 |       0.769215 |   1.25392  |
| k-d_tree_sklearn     |     0.62435  |       2.24083  |   1.28275  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617127 |        5.85328 |   0.758931 |
| Bori_Aron_solution-1 |     0.601239 |       11.2321  |   0.901157 |
| k-d_tree_sklearn     |     0.614662 |       17.8146  |   1.3833   |
| barab-szabi-1        |     0.606703 |        4.97842 |   7.17173  |
| k-d_tree_polars      |     0.62038  |        4.94454 |   7.18783  |
| k-d_tree_pandas      |     0.624335 |        3.85738 |   7.58624  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.776519 |        76.2329 |    3.4348  |
| k-d_tree_sklearn     |     0.676902 |       237.686  |    4.35663 |
| Bori_Aron_solution-1 |     0.606886 |       160.846  |   15.0867  |