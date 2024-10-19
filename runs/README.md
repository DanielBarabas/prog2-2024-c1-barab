# 2024-10-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.606693 |       0.397609 |   0.379714 |
| barab-szabi-2        |     0.615411 |       0.380298 |   0.379917 |
| barab-szabi-1        |     0.615782 |       0.39746  |   0.381544 |
| k-d_tree_pandas      |     0.613006 |       0.380193 |   0.517606 |
| Bori_Aron_solution-1 |     0.602022 |       0.51836  |   0.521373 |
| solution-1           |     7.53199  |       1e-06    |   0.553892 |
| k-d_tree_sklearn     |    10.084    |       1.23288  |   0.953876 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607021 |       0.383404 |   0.378147 |
| k-d_tree_polars      |     0.61201  |       0.39869  |   0.384573 |
| barab-szabi-1        |     0.610728 |       0.416353 |   0.386265 |
| Bori_Aron_solution-1 |     0.601278 |       0.52001  |   0.517386 |
| k-d_tree_pandas      |     0.603739 |       0.379621 |   0.5246   |
| k-d_tree_sklearn     |     0.638252 |       0.879439 |   0.942189 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609233 |       0.397194 |   0.386302 |
| k-d_tree_polars      |     0.609012 |       0.426986 |   0.409698 |
| barab-szabi-1        |     0.604743 |       0.434646 |   0.418721 |
| Bori_Aron_solution-1 |     0.600788 |       0.556572 |   0.515427 |
| k-d_tree_pandas      |     0.607233 |       0.398629 |   0.571262 |
| k-d_tree_sklearn     |     0.612122 |       0.923841 |   0.979953 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608462 |       0.464337 |   0.419952 |
| k-d_tree_polars      |     0.612937 |       0.538736 |   0.514775 |
| barab-szabi-1        |     0.611823 |       0.530632 |   0.525969 |
| Bori_Aron_solution-1 |     0.604289 |       0.741019 |   0.535226 |
| k-d_tree_pandas      |     0.611325 |       0.4766   |   0.705748 |
| k-d_tree_sklearn     |     0.615092 |       1.14763  |   1.03402  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614804 |       0.704835 |   0.461409 |
| Bori_Aron_solution-1 |     0.609614 |       1.39728  |   0.56152  |
| k-d_tree_polars      |     0.604925 |       0.850518 |   0.852395 |
| barab-szabi-1        |     0.612918 |       0.866568 |   0.89379  |
| k-d_tree_sklearn     |     0.609001 |       1.95303  |   1.13198  |
| k-d_tree_pandas      |     0.607802 |       0.745507 |   1.14069  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608642 |        5.3008  |   0.750641 |
| Bori_Aron_solution-1 |     0.608439 |       10.6649  |   0.823475 |
| k-d_tree_sklearn     |     0.612589 |       15.854   |   1.2344   |
| k-d_tree_polars      |     0.611797 |        4.84113 |   6.57966  |
| barab-szabi-1        |     0.639098 |        4.84283 |   6.61007  |
| k-d_tree_pandas      |     0.603407 |        3.90453 |   6.96197  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639781 |         72.002 |    2.97818 |
| k-d_tree_sklearn     |     0.617123 |        228.296 |    4.26926 |
| Bori_Aron_solution-1 |     0.633534 |        146.129 |   18.342   |