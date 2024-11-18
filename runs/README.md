# 2024-11-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604427 |       0.378745 |   0.378695 |
| barab-szabi-1        |     0.608547 |       0.397226 |   0.38206  |
| k-d_tree_polars      |     0.621117 |       0.393469 |   0.384117 |
| solution-1           |     7.30104  |       1e-06    |   0.429584 |
| Bori_Aron_solution-1 |     0.604842 |       0.509332 |   0.517884 |
| k-d_tree_pandas      |     0.608323 |       0.380894 |   0.518604 |
| k-d_tree_sklearn     |    10.0106   |       1.06405  |   0.948831 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.642869 |       0.382728 |   0.37746  |
| barab-szabi-1        |     0.601896 |       0.39877  |   0.387145 |
| k-d_tree_polars      |     0.610794 |       0.398589 |   0.390593 |
| Bori_Aron_solution-1 |     0.602998 |       0.516194 |   0.511842 |
| k-d_tree_pandas      |     0.610693 |       0.405384 |   0.526188 |
| k-d_tree_sklearn     |     0.615425 |       0.877148 |   0.956446 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615505 |       0.400297 |   0.393713 |
| k-d_tree_polars      |     0.612803 |       0.423506 |   0.415701 |
| barab-szabi-1        |     0.618763 |       0.425318 |   0.416856 |
| Bori_Aron_solution-1 |     0.606724 |       0.560996 |   0.53829  |
| k-d_tree_pandas      |     0.612928 |       0.392403 |   0.563654 |
| k-d_tree_sklearn     |     0.613421 |       0.924877 |   0.982561 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608428 |       0.465226 |   0.421909 |
| k-d_tree_polars      |     0.619321 |       0.538894 |   0.511104 |
| barab-szabi-1        |     0.608989 |       0.532711 |   0.526517 |
| Bori_Aron_solution-1 |     0.600643 |       0.73593  |   0.528172 |
| k-d_tree_pandas      |     0.608681 |       0.472887 |   0.70012  |
| k-d_tree_sklearn     |     0.616867 |       1.14938  |   1.04032  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610449 |       0.712325 |   0.459529 |
| Bori_Aron_solution-1 |     0.608804 |       1.37148  |   0.557977 |
| k-d_tree_polars      |     0.604721 |       0.856248 |   0.858568 |
| barab-szabi-1        |     0.613576 |       0.854652 |   0.902787 |
| k-d_tree_sklearn     |     0.616636 |       1.9678   |   1.12063  |
| k-d_tree_pandas      |     0.604609 |       0.74508  |   1.13509  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60961  |        5.26369 |   0.72143  |
| Bori_Aron_solution-1 |     0.603026 |       10.6481  |   0.808789 |
| k-d_tree_sklearn     |     0.611788 |       15.7278  |   1.23876  |
| k-d_tree_polars      |     0.612604 |        4.89933 |   6.40158  |
| barab-szabi-1        |     0.608758 |        4.92983 |   6.47434  |
| k-d_tree_pandas      |     0.613889 |        3.87457 |   6.79489  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629401 |        70.2075 |    3.04394 |
| k-d_tree_sklearn     |     0.612753 |       222.412  |    4.21486 |
| Bori_Aron_solution-1 |     0.618085 |       146.671  |   16.103   |