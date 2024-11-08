# 2024-11-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.620854 |       0.405058 |   0.390241 |
| barab-szabi-2        |     0.623218 |       0.387981 |   0.39096  |
| k-d_tree_polars      |     0.61862  |       0.404587 |   0.404253 |
| solution-1           |     7.75623  |       1e-06    |   0.411164 |
| Bori_Aron_solution-1 |     0.615103 |       0.531231 |   0.522935 |
| k-d_tree_pandas      |     0.616569 |       0.376555 |   0.528935 |
| k-d_tree_sklearn     |    10.5181   |       1.12979  |   0.970245 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626742 |       0.398884 |   0.39797  |
| k-d_tree_polars      |     0.647313 |       0.4108   |   0.399502 |
| barab-szabi-1        |     0.632504 |       0.431479 |   0.405911 |
| Bori_Aron_solution-1 |     0.619832 |       0.534636 |   0.525925 |
| k-d_tree_pandas      |     0.619665 |       0.38257  |   0.535474 |
| k-d_tree_sklearn     |     0.629429 |       0.90354  |   0.970795 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621271 |       0.410217 |   0.405951 |
| k-d_tree_polars      |     0.649761 |       0.432892 |   0.419673 |
| barab-szabi-1        |     0.623351 |       0.44523  |   0.431129 |
| Bori_Aron_solution-1 |     0.637959 |       0.570487 |   0.531525 |
| k-d_tree_pandas      |     0.633719 |       0.412594 |   0.576612 |
| k-d_tree_sklearn     |     0.643631 |       0.974648 |   1.03597  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619785 |       0.470555 |   0.43217  |
| k-d_tree_polars      |     0.630773 |       0.539822 |   0.521919 |
| barab-szabi-1        |     0.626894 |       0.544892 |   0.547483 |
| Bori_Aron_solution-1 |     0.621307 |       0.750447 |   0.552217 |
| k-d_tree_pandas      |     0.627397 |       0.485611 |   0.716414 |
| k-d_tree_sklearn     |     0.631256 |       1.17084  |   1.06128  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626559 |       0.737807 |   0.467602 |
| Bori_Aron_solution-1 |     0.619874 |       1.41213  |   0.571414 |
| k-d_tree_polars      |     0.627519 |       0.879487 |   0.898881 |
| barab-szabi-1        |     0.625897 |       0.852594 |   0.931186 |
| k-d_tree_sklearn     |     0.630446 |       2.03193  |   1.16947  |
| k-d_tree_pandas      |     0.627614 |       0.749012 |   1.18278  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62484  |        5.43855 |   0.723533 |
| Bori_Aron_solution-1 |     0.617301 |       11.1428  |   0.85436  |
| k-d_tree_sklearn     |     0.63002  |       16.8962  |   1.23362  |
| barab-szabi-1        |     0.616524 |        4.84553 |   6.52435  |
| k-d_tree_polars      |     0.614659 |        4.86404 |   6.53781  |
| k-d_tree_pandas      |     0.640022 |        3.90881 |   7.40258  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.624686 |        74.2039 |    2.9167  |
| k-d_tree_sklearn     |     0.660353 |       225.379  |    4.16175 |
| Bori_Aron_solution-1 |     0.643414 |       145.869  |   18.3115  |