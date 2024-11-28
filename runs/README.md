# 2024-11-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612231 |       0.380395 |   0.381874 |
| k-d_tree_polars      |     0.623181 |       0.395521 |   0.385021 |
| barab-szabi-1        |     0.612633 |       0.398006 |   0.389367 |
| solution-1           |     8.09815  |       1e-06    |   0.415147 |
| k-d_tree_pandas      |     0.619387 |       0.375625 |   0.517622 |
| Bori_Aron_solution-1 |     0.615007 |       0.520222 |   0.521079 |
| k-d_tree_sklearn     |    10.7631   |       1.12672  |   0.985333 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616768 |       0.386593 |   0.382314 |
| barab-szabi-1        |     0.618046 |       0.401913 |   0.392    |
| k-d_tree_polars      |     0.611056 |       0.409083 |   0.393558 |
| Bori_Aron_solution-1 |     0.618731 |       0.526265 |   0.518681 |
| k-d_tree_pandas      |     0.61563  |       0.383358 |   0.532471 |
| k-d_tree_sklearn     |     0.616087 |       0.882913 |   0.961956 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61124  |       0.404922 |   0.403098 |
| k-d_tree_polars      |     0.614251 |       0.427933 |   0.414848 |
| barab-szabi-1        |     0.617237 |       0.422481 |   0.419479 |
| Bori_Aron_solution-1 |     0.602521 |       0.568635 |   0.520972 |
| k-d_tree_pandas      |     0.611964 |       0.402725 |   0.571743 |
| k-d_tree_sklearn     |     0.620003 |       0.924812 |   0.98426  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611123 |       0.46871  |   0.425113 |
| k-d_tree_polars      |     0.640201 |       0.535107 |   0.515578 |
| barab-szabi-1        |     0.611078 |       0.533973 |   0.529043 |
| Bori_Aron_solution-1 |     0.619451 |       0.747718 |   0.535721 |
| k-d_tree_pandas      |     0.619311 |       0.478863 |   0.707935 |
| k-d_tree_sklearn     |     0.619799 |       1.14803  |   1.02948  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613201 |       0.721534 |   0.459187 |
| Bori_Aron_solution-1 |     0.608006 |       1.38027  |   0.558639 |
| k-d_tree_polars      |     0.608608 |       0.865994 |   0.866136 |
| barab-szabi-1        |     0.616275 |       0.861212 |   0.902036 |
| k-d_tree_sklearn     |     0.616416 |       1.98016  |   1.12753  |
| k-d_tree_pandas      |     0.608346 |       0.744369 |   1.14104  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607734 |        5.18403 |   0.729918 |
| Bori_Aron_solution-1 |     0.605707 |       10.5583  |   0.816447 |
| k-d_tree_sklearn     |     0.61939  |       15.6799  |   1.23019  |
| barab-szabi-1        |     0.606675 |        4.92882 |   6.38768  |
| k-d_tree_polars      |     0.614463 |        4.87547 |   6.41114  |
| k-d_tree_pandas      |     0.610698 |        3.88104 |   6.93446  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620074 |        70.8614 |    2.90672 |
| k-d_tree_sklearn     |     0.617284 |       223.445  |    4.20526 |
| Bori_Aron_solution-1 |     0.628821 |       143.649  |   17.8707  |