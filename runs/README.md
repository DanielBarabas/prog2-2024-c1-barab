# 2026-06-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.51049  |       1e-06    |   0.447709 |
| barab-szabi-1        |     0.485753 |       0.428461 |   0.457924 |
| k-d_tree_polars      |     0.482431 |       0.421568 |   0.46544  |
| barab-szabi-2        |     9.54086  |       0.642246 |   0.467174 |
| Bori_Aron_solution-1 |     0.467113 |       0.565269 |   0.566226 |
| k-d_tree_pandas      |     0.498955 |       0.407212 |   0.591617 |
| k-d_tree_sklearn     |     3.87822  |       1.10031  |   1.14686  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.491073 |       0.426925 |   0.462619 |
| barab-szabi-2        |     0.491991 |       0.470636 |   0.470577 |
| k-d_tree_polars      |     0.484795 |       0.422445 |   0.47172  |
| Bori_Aron_solution-1 |     0.4873   |       0.570543 |   0.567793 |
| k-d_tree_pandas      |     0.485237 |       0.39907  |   0.573497 |
| k-d_tree_sklearn     |     0.491054 |       1.03105  |   1.13031  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481079 |       0.481783 |   0.466127 |
| barab-szabi-1        |     0.484232 |       0.448392 |   0.480463 |
| k-d_tree_polars      |     0.494601 |       0.526734 |   0.505697 |
| Bori_Aron_solution-1 |     0.493046 |       0.625988 |   0.575742 |
| k-d_tree_pandas      |     0.47891  |       0.422734 |   0.623319 |
| k-d_tree_sklearn     |     0.489851 |       1.08165  |   1.14943  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497591 |       0.532722 |   0.483216 |
| k-d_tree_polars      |     0.495978 |       0.567753 |   0.578776 |
| Bori_Aron_solution-1 |     0.484849 |       0.800809 |   0.592896 |
| barab-szabi-1        |     0.476094 |       0.556963 |   0.608896 |
| k-d_tree_pandas      |     0.471919 |       0.514066 |   0.756917 |
| k-d_tree_sklearn     |     0.475972 |       1.28525  |   1.17264  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483027 |       0.753995 |   0.525084 |
| Bori_Aron_solution-1 |     0.470655 |       1.4754   |   0.588907 |
| k-d_tree_polars      |     0.482629 |       0.926317 |   0.940787 |
| barab-szabi-1        |     0.474255 |       0.927065 |   0.971913 |
| k-d_tree_pandas      |     0.475685 |       0.803534 |   1.20118  |
| k-d_tree_sklearn     |     0.47664  |       2.15004  |   1.23317  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470565 |        5.17697 |   0.750774 |
| Bori_Aron_solution-1 |     0.476136 |       11.0911  |   0.819102 |
| k-d_tree_sklearn     |     0.514172 |       17.6634  |   1.3497   |
| barab-szabi-1        |     0.472837 |        5.38636 |   6.84179  |
| k-d_tree_polars      |     0.479687 |        5.25724 |   6.99895  |
| k-d_tree_pandas      |     0.479903 |        4.35459 |   7.3002   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487439 |        72.3832 |    2.76283 |
| k-d_tree_sklearn     |     0.801205 |       243.706  |    4.12874 |
| Bori_Aron_solution-1 |     0.479951 |       150.274  |   23.5965  |