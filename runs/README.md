# 2024-09-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.598038 |       0.396072 |   0.386448 |
| barab-szabi-2        |     0.633762 |       0.393537 |   0.395243 |
| Bori_Aron_solution-1 |     4.50007  |       0.673835 |   0.452713 |
| k-d_tree_polars      |     0.596858 |       0.426611 |   0.466794 |
| k-d_tree_pandas      |     4.30054  |       0.438019 |   0.524448 |
| solution-1           |     7.84379  |       1e-06    |   0.598388 |
| k-d_tree_sklearn     |     3.17448  |       1.06438  |   0.988631 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.620113 |       0.40749  |   0.390508 |
| barab-szabi-2        |     0.631249 |       0.39635  |   0.400141 |
| barab-szabi-1        |     0.612854 |       0.436687 |   0.401084 |
| k-d_tree_pandas      |     0.616702 |       0.389772 |   0.533808 |
| Bori_Aron_solution-1 |     0.62722  |       0.583457 |   0.534761 |
| k-d_tree_sklearn     |     0.624748 |       0.911084 |   1.00771  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612061 |       0.51165  |   0.402112 |
| k-d_tree_polars      |     0.6327   |       0.449269 |   0.438525 |
| barab-szabi-1        |     0.64506  |       0.451931 |   0.439111 |
| Bori_Aron_solution-1 |     0.627762 |       0.578311 |   0.535781 |
| k-d_tree_pandas      |     0.628579 |       0.407052 |   0.598081 |
| k-d_tree_sklearn     |     0.638344 |       0.96361  |   1.01063  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617195 |       0.461807 |   0.427999 |
| k-d_tree_polars      |     0.61704  |       0.547033 |   0.515763 |
| barab-szabi-1        |     0.612488 |       0.525238 |   0.521155 |
| Bori_Aron_solution-1 |     0.629584 |       0.740476 |   0.550765 |
| k-d_tree_pandas      |     0.627094 |       0.492137 |   0.719038 |
| k-d_tree_sklearn     |     0.622456 |       1.14721  |   1.07337  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608335 |       0.705692 |   0.476326 |
| Bori_Aron_solution-1 |     0.607046 |       1.38681  |   0.577084 |
| k-d_tree_polars      |     0.613851 |       0.867205 |   0.886513 |
| barab-szabi-1        |     0.614998 |       0.838825 |   0.900952 |
| k-d_tree_sklearn     |     0.612725 |       1.93605  |   1.12769  |
| k-d_tree_pandas      |     0.617297 |       0.741496 |   1.15181  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610786 |        5.28964 |   0.723264 |
| Bori_Aron_solution-1 |     0.613735 |       10.645   |   0.836066 |
| k-d_tree_sklearn     |     0.617998 |       16.232   |   1.24652  |
| barab-szabi-1        |     0.624099 |        4.83304 |   6.76116  |
| k-d_tree_polars      |     0.61622  |        4.803   |   6.81449  |
| k-d_tree_pandas      |     0.626931 |        3.80699 |   6.98263  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744158 |        67.8802 |    3.06913 |
| k-d_tree_sklearn     |     0.916609 |       222.55   |    4.32745 |
| Bori_Aron_solution-1 |     0.608163 |       145.909  |   15.1977  |