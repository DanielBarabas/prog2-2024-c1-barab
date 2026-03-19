# 2026-03-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51567  |       0.469566 |   0.47122  |
| k-d_tree_polars      |     0.509252 |       0.42906  |   0.475192 |
| Bori_Aron_solution-1 |     0.502596 |       0.582624 |   0.587091 |
| k-d_tree_pandas      |     0.521356 |       0.410889 |   0.593602 |
| barab-szabi-1        |     8.86683  |       0.486546 |   0.607862 |
| solution-1           |     8.38597  |       2e-06    |   0.622617 |
| k-d_tree_sklearn     |     3.12109  |       1.18112  |   1.1784   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.523307 |       0.444213 |   0.467618 |
| barab-szabi-2        |     0.524393 |       0.46916  |   0.480155 |
| k-d_tree_polars      |     0.520266 |       0.435035 |   0.499801 |
| Bori_Aron_solution-1 |     0.50652  |       0.607128 |   0.586859 |
| k-d_tree_pandas      |     0.528119 |       0.418268 |   0.602275 |
| k-d_tree_sklearn     |     0.525047 |       1.02823  |   1.08697  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.517126 |       0.456194 |   0.452524 |
| k-d_tree_polars      |     0.533628 |       0.469709 |   0.470813 |
| barab-szabi-1        |     0.501743 |       0.445851 |   0.486026 |
| Bori_Aron_solution-1 |     0.495144 |       0.612544 |   0.565775 |
| k-d_tree_pandas      |     0.500291 |       0.424181 |   0.616061 |
| k-d_tree_sklearn     |     0.503472 |       1.03629  |   1.12054  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492067 |       0.517079 |   0.492107 |
| k-d_tree_polars      |     0.496456 |       0.58014  |   0.572951 |
| Bori_Aron_solution-1 |     0.532646 |       0.808516 |   0.578485 |
| barab-szabi-1        |     0.497535 |       0.571052 |   0.582083 |
| k-d_tree_pandas      |     0.494253 |       0.512065 |   0.781017 |
| k-d_tree_sklearn     |     0.528068 |       1.3171   |   1.18317  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.503431 |       0.767118 |   0.547164 |
| Bori_Aron_solution-1 |     0.497579 |       1.51451  |   0.611783 |
| k-d_tree_polars      |     0.509101 |       0.962368 |   0.940132 |
| barab-szabi-1        |     0.499738 |       0.943519 |   0.988869 |
| k-d_tree_pandas      |     0.510989 |       0.842432 |   1.2063   |
| k-d_tree_sklearn     |     0.52031  |       2.23622  |   1.25168  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518877 |        5.61829 |   0.793681 |
| Bori_Aron_solution-1 |     0.525649 |       11.4132  |   0.856689 |
| k-d_tree_sklearn     |     0.496802 |       17.0324  |   1.30806  |
| k-d_tree_polars      |     0.504598 |        5.63787 |   6.66139  |
| k-d_tree_pandas      |     0.493167 |        4.49417 |   7.01131  |
| barab-szabi-1        |     0.53135  |        5.58692 |   7.09331  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49299  |        73.6472 |    2.75389 |
| k-d_tree_sklearn     |     0.761583 |       234.487  |    3.74599 |
| Bori_Aron_solution-1 |     0.510041 |       148.363  |   18.0092  |