# 2025-11-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.566254 |       0.437548 |   0.46446  |
| k-d_tree_polars      |     0.575821 |       0.44726  |   0.475132 |
| barab-szabi-2        |     0.548214 |       0.532561 |   0.475247 |
| solution-1           |     8.77642  |       1e-06    |   0.501301 |
| Bori_Aron_solution-1 |     0.563731 |       0.619775 |   0.61484  |
| k-d_tree_pandas      |     8.61429  |       0.499649 |   0.727101 |
| k-d_tree_sklearn     |     3.30908  |       1.36008  |   1.16232  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576976 |       0.464874 |   0.460528 |
| barab-szabi-1        |     0.570741 |       0.447169 |   0.462867 |
| k-d_tree_polars      |     0.572412 |       0.445825 |   0.51864  |
| Bori_Aron_solution-1 |     0.558576 |       0.689279 |   0.602512 |
| k-d_tree_pandas      |     0.585011 |       0.438698 |   0.607491 |
| k-d_tree_sklearn     |     0.567159 |       1.0773   |   1.16606  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.582579 |       0.470474 |   0.489922 |
| barab-szabi-1        |     0.560805 |       0.466281 |   0.526304 |
| barab-szabi-2        |     0.560536 |       0.470781 |   0.554654 |
| Bori_Aron_solution-1 |     0.560346 |       0.660894 |   0.591291 |
| k-d_tree_pandas      |     0.565232 |       0.434623 |   0.632553 |
| k-d_tree_sklearn     |     0.621475 |       1.09622  |   1.18255  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561781 |       0.531249 |   0.498006 |
| k-d_tree_polars      |     0.564641 |       0.6053   |   0.580543 |
| barab-szabi-1        |     0.558588 |       0.592913 |   0.604301 |
| Bori_Aron_solution-1 |     0.561715 |       0.858754 |   0.645077 |
| k-d_tree_pandas      |     0.554218 |       0.541073 |   0.781672 |
| k-d_tree_sklearn     |     0.566686 |       1.34617  |   1.25359  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56717  |       0.855187 |   0.609258 |
| Bori_Aron_solution-1 |     0.551607 |       1.56707  |   0.644585 |
| k-d_tree_polars      |     0.560372 |       0.973386 |   0.974736 |
| barab-szabi-1        |     0.573493 |       0.960131 |   1.0078   |
| k-d_tree_pandas      |     0.565665 |       0.872895 |   1.27512  |
| k-d_tree_sklearn     |     0.569316 |       2.32663  |   1.34681  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566478 |        6.03135 |   0.817025 |
| Bori_Aron_solution-1 |     0.553825 |       12.2229  |   0.929405 |
| k-d_tree_sklearn     |     0.587596 |       19.0002  |   1.49451  |
| barab-szabi-1        |     0.571552 |        5.55774 |   7.47203  |
| k-d_tree_polars      |     0.562038 |        5.58535 |   7.77782  |
| k-d_tree_pandas      |     0.568743 |        4.52159 |   7.959    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563469 |        85.6472 |    2.71391 |
| k-d_tree_sklearn     |     0.568802 |       247.462  |    4.35165 |
| Bori_Aron_solution-1 |     0.704571 |       162.298  |   17.1569  |