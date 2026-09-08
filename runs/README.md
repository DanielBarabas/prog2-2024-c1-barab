# 2026-09-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.384104 |       0.376382 |   0.356478 |
| k-d_tree_polars      |     0.375856 |       0.348555 |   0.367966 |
| solution-1           |     6.61166  |       1e-06    |   0.452789 |
| Bori_Aron_solution-1 |     0.383711 |       0.470578 |   0.465501 |
| k-d_tree_pandas      |     0.377963 |       0.321673 |   0.490132 |
| barab-szabi-1        |     8.9971   |       0.451272 |   0.51685  |
| k-d_tree_sklearn     |     3.44238  |       0.996861 |   0.94373  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.384856 |       0.356821 |   0.37287  |
| k-d_tree_polars      |     0.376234 |       0.373031 |   0.378435 |
| barab-szabi-2        |     0.377943 |       0.45356  |   0.390539 |
| Bori_Aron_solution-1 |     0.379382 |       0.505828 |   0.455327 |
| k-d_tree_pandas      |     0.383812 |       0.325636 |   0.472605 |
| k-d_tree_sklearn     |     0.380025 |       0.83489  |   0.89828  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.386514 |       0.445969 |   0.384363 |
| k-d_tree_polars      |     0.379671 |       0.393    |   0.388746 |
| barab-szabi-1        |     0.376023 |       0.380101 |   0.39285  |
| Bori_Aron_solution-1 |     0.374671 |       0.492861 |   0.473279 |
| k-d_tree_pandas      |     0.387438 |       0.340313 |   0.496615 |
| k-d_tree_sklearn     |     0.384922 |       0.874315 |   0.899954 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.397528 |       0.433697 |   0.406546 |
| k-d_tree_polars      |     0.381366 |       0.47246  |   0.467401 |
| barab-szabi-1        |     0.389478 |       0.465558 |   0.472198 |
| Bori_Aron_solution-1 |     0.387799 |       0.64275  |   0.4727   |
| k-d_tree_pandas      |     0.373514 |       0.412512 |   0.652634 |
| k-d_tree_sklearn     |     0.389721 |       1.10123  |   0.978733 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.381899 |       0.642262 |   0.446161 |
| Bori_Aron_solution-1 |     0.392948 |       1.17768  |   0.479649 |
| k-d_tree_polars      |     0.384317 |       0.722528 |   0.767483 |
| barab-szabi-1        |     0.393839 |       0.722704 |   0.810702 |
| k-d_tree_pandas      |     0.375823 |       0.623135 |   0.955265 |
| k-d_tree_sklearn     |     0.370653 |       1.76976  |   0.994584 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.359305 |        4.51622 |   0.636628 |
| Bori_Aron_solution-1 |     0.374879 |        8.97893 |   0.644608 |
| k-d_tree_sklearn     |     0.372138 |       14.9646  |   1.03131  |
| k-d_tree_polars      |     0.360988 |        4.68145 |   5.88136  |
| barab-szabi-1        |     0.391502 |        4.65194 |   6.0959   |
| k-d_tree_pandas      |     0.371721 |        3.23607 |   6.40728  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.47742  |        72.8345 |    3.88657 |
| k-d_tree_sklearn     |     1.04412  |       233.048  |    5.91214 |
| Bori_Aron_solution-1 |     0.365109 |       173.416  |   19.9279  |