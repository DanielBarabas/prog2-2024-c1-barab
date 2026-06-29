# 2026-06-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.1518   |       1e-06    |   0.416739 |
| barab-szabi-2        |     9.04519  |       0.616389 |   0.449728 |
| k-d_tree_polars      |     0.481194 |       0.429707 |   0.454396 |
| barab-szabi-1        |     0.471601 |       0.423421 |   0.470779 |
| Bori_Aron_solution-1 |     0.479891 |       0.576094 |   0.577012 |
| k-d_tree_pandas      |     0.505878 |       0.415852 |   0.596661 |
| k-d_tree_sklearn     |     3.04671  |       1.19843  |   1.13561  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.491644 |       0.438803 |   0.447399 |
| barab-szabi-1        |     0.47973  |       0.415908 |   0.452569 |
| barab-szabi-2        |     0.487065 |       0.438423 |   0.479863 |
| Bori_Aron_solution-1 |     0.481059 |       0.567487 |   0.588816 |
| k-d_tree_pandas      |     0.495975 |       0.426874 |   0.603678 |
| k-d_tree_sklearn     |     0.486644 |       1.02625  |   1.1503   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.471491 |       0.437473 |   0.456093 |
| barab-szabi-2        |     0.501011 |       0.462553 |   0.464812 |
| barab-szabi-1        |     0.492136 |       0.460689 |   0.498576 |
| Bori_Aron_solution-1 |     0.484741 |       0.634929 |   0.580184 |
| k-d_tree_pandas      |     0.480497 |       0.486896 |   0.633584 |
| k-d_tree_sklearn     |     0.49207  |       1.06217  |   1.19192  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497027 |       0.535685 |   0.477197 |
| Bori_Aron_solution-1 |     0.52017  |       0.831157 |   0.579335 |
| k-d_tree_polars      |     0.495657 |       0.571914 |   0.581165 |
| barab-szabi-1        |     0.476482 |       0.560094 |   0.588787 |
| k-d_tree_pandas      |     0.487243 |       0.511839 |   0.732565 |
| k-d_tree_sklearn     |     0.513408 |       1.31998  |   1.22287  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482312 |       0.792696 |   0.584348 |
| Bori_Aron_solution-1 |     0.494919 |       1.55775  |   0.639259 |
| k-d_tree_polars      |     0.500708 |       0.940614 |   1.02441  |
| barab-szabi-1        |     0.481944 |       0.921856 |   1.02715  |
| k-d_tree_pandas      |     0.507693 |       0.82022  |   1.29272  |
| k-d_tree_sklearn     |     0.504655 |       2.35195  |   1.32001  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498484 |        6.056   |   0.777364 |
| Bori_Aron_solution-1 |     0.496036 |       11.6344  |   0.823939 |
| k-d_tree_sklearn     |     0.490613 |       18.5026  |   1.31373  |
| k-d_tree_polars      |     0.472106 |        5.16429 |   7.76917  |
| barab-szabi-1        |     0.500464 |        5.13378 |   7.98308  |
| k-d_tree_pandas      |     0.484977 |        4.11372 |   8.07645  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483126 |        77.8181 |    2.71252 |
| k-d_tree_sklearn     |     0.721939 |       254.261  |    3.41366 |
| Bori_Aron_solution-1 |     0.492375 |       155.044  |   17.8027  |