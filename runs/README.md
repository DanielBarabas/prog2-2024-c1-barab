# 2025-04-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.68978  |       1e-06    |   0.404637 |
| k-d_tree_polars      |     0.606779 |       0.447865 |   0.465718 |
| barab-szabi-2        |     0.602113 |       0.452999 |   0.472109 |
| barab-szabi-1        |     0.619901 |       0.479282 |   0.482008 |
| Bori_Aron_solution-1 |     0.597988 |       0.628546 |   0.632831 |
| k-d_tree_pandas      |     7.99654  |       0.450177 |   0.696915 |
| k-d_tree_sklearn     |     3.04971  |       1.1696   |   1.21354  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639086 |       0.466876 |   0.452958 |
| barab-szabi-1        |     0.643983 |       0.46958  |   0.470219 |
| k-d_tree_polars      |     0.623193 |       0.451672 |   0.477854 |
| k-d_tree_pandas      |     0.624786 |       0.451982 |   0.646785 |
| Bori_Aron_solution-1 |     0.631168 |       0.642413 |   0.652549 |
| k-d_tree_sklearn     |     0.629445 |       1.11303  |   1.17377  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.636921 |       0.470887 |   0.463326 |
| k-d_tree_polars      |     0.616562 |       0.498655 |   0.475232 |
| barab-szabi-1        |     0.618783 |       0.486137 |   0.481022 |
| Bori_Aron_solution-1 |     0.604683 |       0.700406 |   0.612255 |
| k-d_tree_pandas      |     0.604637 |       0.45463  |   0.671535 |
| k-d_tree_sklearn     |     0.618868 |       1.12183  |   1.20685  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612992 |       0.521637 |   0.489915 |
| k-d_tree_polars      |     0.609648 |       0.595782 |   0.588514 |
| barab-szabi-1        |     0.614422 |       0.622465 |   0.60067  |
| Bori_Aron_solution-1 |     0.608349 |       0.819057 |   0.612325 |
| k-d_tree_pandas      |     0.602109 |       0.544816 |   0.825779 |
| k-d_tree_sklearn     |     0.643658 |       1.36037  |   1.26322  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609588 |       0.787271 |   0.655802 |
| Bori_Aron_solution-1 |     0.61838  |       1.50733  |   0.656295 |
| k-d_tree_polars      |     0.616319 |       0.934429 |   0.97056  |
| barab-szabi-1        |     0.637216 |       0.937476 |   1.01676  |
| k-d_tree_pandas      |     0.611287 |       0.787045 |   1.28106  |
| k-d_tree_sklearn     |     0.623766 |       2.33425  |   1.32314  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617201 |        6.21556 |   0.825738 |
| Bori_Aron_solution-1 |     0.609478 |       11.2865  |   0.924594 |
| k-d_tree_sklearn     |     0.635083 |       19.1157  |   1.48226  |
| k-d_tree_polars      |     0.609564 |        5.06417 |   7.48746  |
| barab-szabi-1        |     0.603531 |        5.06979 |   7.57307  |
| k-d_tree_pandas      |     0.619272 |        3.93073 |   8.01836  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.860707 |         79.436 |    3.79683 |
| k-d_tree_sklearn     |     0.696433 |        252.217 |    4.42036 |
| Bori_Aron_solution-1 |     0.618493 |        171.816 |   14.2637  |