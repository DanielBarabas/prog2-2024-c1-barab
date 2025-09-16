# 2025-09-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.76631  |       0.839787 |   0.428353 |
| barab-szabi-1        |     0.540988 |       0.409526 |   0.440414 |
| k-d_tree_polars      |     0.54396  |       0.416839 |   0.440619 |
| solution-1           |     7.45486  |       1e-06    |   0.48851  |
| Bori_Aron_solution-1 |     0.528532 |       0.554088 |   0.557657 |
| k-d_tree_pandas      |     0.533494 |       0.393433 |   0.573153 |
| k-d_tree_sklearn     |     3.0021   |       1.18798  |   1.08831  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552965 |       0.426739 |   0.435335 |
| barab-szabi-1        |     0.558056 |       0.420273 |   0.444712 |
| k-d_tree_polars      |     0.570292 |       0.42616  |   0.448901 |
| Bori_Aron_solution-1 |     0.542874 |       0.569618 |   0.570714 |
| k-d_tree_pandas      |     0.550296 |       0.408301 |   0.573276 |
| k-d_tree_sklearn     |     0.586302 |       1.01452  |   1.12449  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554304 |       0.447375 |   0.454543 |
| barab-szabi-1        |     0.577487 |       0.444481 |   0.469301 |
| k-d_tree_polars      |     0.557168 |       0.445152 |   0.46943  |
| Bori_Aron_solution-1 |     0.548703 |       0.604734 |   0.578821 |
| k-d_tree_pandas      |     0.561616 |       0.417432 |   0.615234 |
| k-d_tree_sklearn     |     0.555774 |       1.05225  |   1.13198  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560623 |       0.51384  |   0.47291  |
| k-d_tree_polars      |     0.55362  |       0.560197 |   0.568626 |
| barab-szabi-1        |     0.550732 |       0.558841 |   0.577708 |
| Bori_Aron_solution-1 |     0.544705 |       0.788272 |   0.582002 |
| k-d_tree_pandas      |     0.549948 |       0.497307 |   0.75063  |
| k-d_tree_sklearn     |     0.555504 |       1.2968   |   1.18813  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557359 |       0.763366 |   0.521166 |
| Bori_Aron_solution-1 |     0.546052 |       1.43593  |   0.603589 |
| k-d_tree_polars      |     0.554136 |       0.892216 |   0.939116 |
| barab-szabi-1        |     0.555333 |       0.905824 |   0.979836 |
| k-d_tree_pandas      |     0.556101 |       0.775017 |   1.20929  |
| k-d_tree_sklearn     |     0.555485 |       2.1654   |   1.25493  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553882 |        5.48842 |   0.769896 |
| Bori_Aron_solution-1 |     0.548441 |       10.8903  |   0.87973  |
| k-d_tree_sklearn     |     0.552348 |       17.3244  |   1.34942  |
| barab-szabi-1        |     0.552732 |        5.04035 |   6.89246  |
| k-d_tree_polars      |     0.548978 |        5.04474 |   6.92858  |
| k-d_tree_pandas      |     0.55934  |        3.96342 |   7.20533  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556967 |        77.0859 |    2.89007 |
| k-d_tree_sklearn     |     1.15342  |       243.284  |    4.06127 |
| Bori_Aron_solution-1 |     0.558021 |       144.954  |   17.665   |