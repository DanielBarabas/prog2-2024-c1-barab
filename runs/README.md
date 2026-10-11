# 2026-10-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.2311   |       1e-06    |   0.380502 |
| barab-szabi-2        |     0.408601 |       0.400224 |   0.403516 |
| k-d_tree_polars      |     0.409206 |       0.378621 |   0.421165 |
| barab-szabi-1        |     9.05914  |       0.434702 |   0.436529 |
| Bori_Aron_solution-1 |     0.407622 |       0.503278 |   0.502577 |
| k-d_tree_pandas      |     0.411693 |       0.359287 |   0.505214 |
| k-d_tree_sklearn     |     2.80339  |       1.06037  |   0.975058 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.422845 |       0.40169  |   0.40261  |
| k-d_tree_polars      |     0.420345 |       0.403364 |   0.415895 |
| barab-szabi-1        |     0.423902 |       0.409262 |   0.421046 |
| Bori_Aron_solution-1 |     0.410889 |       0.509934 |   0.508453 |
| k-d_tree_pandas      |     0.49053  |       0.377981 |   0.530896 |
| k-d_tree_sklearn     |     0.425381 |       0.935027 |   0.991374 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.422974 |       0.428209 |   0.40686  |
| k-d_tree_polars      |     0.435025 |       0.422864 |   0.434963 |
| barab-szabi-1        |     0.420355 |       0.425951 |   0.44109  |
| Bori_Aron_solution-1 |     0.41298  |       0.553173 |   0.536078 |
| k-d_tree_pandas      |     0.421589 |       0.385244 |   0.553223 |
| k-d_tree_sklearn     |     0.43076  |       0.954992 |   0.989956 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.424049 |       0.478512 |   0.445262 |
| k-d_tree_polars      |     0.42717  |       0.546237 |   0.507098 |
| barab-szabi-1        |     0.42376  |       0.713904 |   0.522699 |
| Bori_Aron_solution-1 |     0.415056 |       0.720232 |   0.540537 |
| k-d_tree_pandas      |     0.421047 |       0.468226 |   0.665667 |
| k-d_tree_sklearn     |     0.425732 |       1.19867  |   1.04007  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.428509 |       0.714135 |   0.478779 |
| Bori_Aron_solution-1 |     0.416183 |       1.30962  |   0.563155 |
| k-d_tree_polars      |     0.432518 |       0.911032 |   0.823163 |
| barab-szabi-1        |     0.426646 |       0.930704 |   0.868962 |
| k-d_tree_pandas      |     0.426493 |       0.724308 |   1.0399   |
| k-d_tree_sklearn     |     0.426771 |       2.03186  |   1.10546  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.428614 |        4.48534 |   0.667801 |
| Bori_Aron_solution-1 |     0.419749 |        9.52159 |   0.857729 |
| k-d_tree_sklearn     |     0.433894 |       14.9029  |   1.23713  |
| barab-szabi-1        |     0.427616 |        5.34849 |   5.76568  |
| k-d_tree_polars      |     0.462379 |        5.15908 |   5.99192  |
| k-d_tree_pandas      |     0.419663 |        3.69024 |   6.21166  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.726012 |        65.6985 |    2.4986  |
| k-d_tree_sklearn     |     0.560084 |       187.196  |    3.73759 |
| Bori_Aron_solution-1 |     0.419739 |       159.211  |   44.0848  |