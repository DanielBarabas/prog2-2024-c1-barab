# 2025-03-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.28857  |       1e-06    |   0.384608 |
| k-d_tree_polars      |     0.603765 |       0.434728 |   0.432407 |
| barab-szabi-1        |     0.581561 |       0.429261 |   0.438262 |
| barab-szabi-2        |     0.575067 |       0.441932 |   0.439701 |
| Bori_Aron_solution-1 |     0.570517 |       0.575506 |   0.586383 |
| k-d_tree_pandas      |     8.4785   |       0.430658 |   0.619218 |
| k-d_tree_sklearn     |     3.23648  |       1.14451  |   1.12217  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596402 |       0.44613  |   0.44725  |
| k-d_tree_polars      |     0.611062 |       0.44771  |   0.450532 |
| barab-szabi-1        |     0.604463 |       0.452535 |   0.454058 |
| k-d_tree_pandas      |     0.607255 |       0.417865 |   0.598467 |
| Bori_Aron_solution-1 |     0.590677 |       0.603114 |   0.613652 |
| k-d_tree_sklearn     |     0.609992 |       1.06704  |   1.14443  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.601776 |       0.480167 |   0.455746 |
| k-d_tree_polars      |     0.598599 |       0.473246 |   0.469892 |
| barab-szabi-1        |     0.592309 |       0.467209 |   0.472008 |
| Bori_Aron_solution-1 |     0.594361 |       0.694492 |   0.596342 |
| k-d_tree_pandas      |     0.605827 |       0.442243 |   0.67702  |
| k-d_tree_sklearn     |     0.606835 |       1.09911  |   1.17735  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596337 |       0.514261 |   0.472461 |
| k-d_tree_polars      |     0.591357 |       0.56998  |   0.564967 |
| barab-szabi-1        |     0.595358 |       0.569882 |   0.576247 |
| Bori_Aron_solution-1 |     0.586635 |       0.795916 |   0.599776 |
| k-d_tree_pandas      |     0.59954  |       0.509885 |   0.767118 |
| k-d_tree_sklearn     |     0.607096 |       1.30875  |   1.2028   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568774 |       0.744906 |   0.507116 |
| Bori_Aron_solution-1 |     0.593576 |       1.45139  |   0.631211 |
| k-d_tree_polars      |     0.587044 |       0.878795 |   0.905483 |
| barab-szabi-1        |     0.595216 |       0.884264 |   0.962844 |
| k-d_tree_sklearn     |     0.580267 |       2.15762  |   1.22846  |
| k-d_tree_pandas      |     0.606312 |       0.770231 |   1.24545  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586467 |        6.24287 |   0.771914 |
| Bori_Aron_solution-1 |     0.590118 |       11.4285  |   0.913347 |
| k-d_tree_sklearn     |     0.605616 |       18.6794  |   1.42208  |
| k-d_tree_polars      |     0.598263 |        4.91087 |   7.38223  |
| barab-szabi-1        |     0.601515 |        4.97463 |   7.41719  |
| k-d_tree_pandas      |     0.590505 |        3.82327 |   7.86743  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.875105 |        74.3261 |    2.98677 |
| k-d_tree_sklearn     |     0.635298 |       234.804  |    4.27457 |
| Bori_Aron_solution-1 |     0.594222 |       154.74   |   16.5204  |