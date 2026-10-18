# 2026-10-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.74685  |       1e-06    |   0.405793 |
| k-d_tree_polars      |     0.434212 |       0.40405  |   0.430372 |
| barab-szabi-2        |     0.442703 |       0.440241 |   0.435007 |
| Bori_Aron_solution-1 |     0.426584 |       0.536255 |   0.534919 |
| k-d_tree_pandas      |     0.43978  |       0.382606 |   0.546239 |
| barab-szabi-1        |     7.93895  |       0.477045 |   0.565801 |
| k-d_tree_sklearn     |     2.67936  |       1.18975  |   1.04966  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.446098 |       0.440134 |   0.426452 |
| barab-szabi-2        |     0.459747 |       0.435087 |   0.426877 |
| k-d_tree_polars      |     0.448335 |       0.421496 |   0.452105 |
| Bori_Aron_solution-1 |     0.438086 |       0.543277 |   0.539551 |
| k-d_tree_pandas      |     0.445828 |       0.390548 |   0.54719  |
| k-d_tree_sklearn     |     0.452834 |       0.977077 |   1.08675  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.451073 |       0.447309 |   0.442766 |
| k-d_tree_polars      |     0.446748 |       0.452628 |   0.461143 |
| barab-szabi-1        |     0.461211 |       0.466156 |   0.461487 |
| Bori_Aron_solution-1 |     0.437884 |       0.578813 |   0.541503 |
| k-d_tree_pandas      |     0.463357 |       0.40333  |   0.578156 |
| k-d_tree_sklearn     |     0.450449 |       1.03048  |   1.08102  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.451334 |       0.513975 |   0.453702 |
| k-d_tree_polars      |     0.452694 |       0.572652 |   0.552747 |
| barab-szabi-1        |     0.460204 |       0.577521 |   0.555502 |
| Bori_Aron_solution-1 |     0.462436 |       0.749057 |   0.564356 |
| k-d_tree_pandas      |     0.457214 |       0.488837 |   0.713167 |
| k-d_tree_sklearn     |     0.455708 |       1.24945  |   1.10975  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.45266  |       0.78221  |   0.586825 |
| Bori_Aron_solution-1 |     0.443073 |       1.3557   |   0.592031 |
| k-d_tree_polars      |     0.449637 |       0.868439 |   0.861501 |
| barab-szabi-1        |     0.450117 |       0.885284 |   0.896667 |
| k-d_tree_pandas      |     0.459588 |       0.75242  |   1.13903  |
| k-d_tree_sklearn     |     0.45304  |       2.11031  |   1.1835   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.448215 |        5.12904 |   0.711597 |
| Bori_Aron_solution-1 |     0.442864 |        9.97874 |   0.883282 |
| k-d_tree_sklearn     |     0.456475 |       14.7763  |   1.31202  |
| k-d_tree_polars      |     0.452344 |        4.77331 |   6.14391  |
| barab-szabi-1        |     0.454618 |        4.90355 |   6.64244  |
| k-d_tree_pandas      |     0.459275 |        3.83192 |   6.82755  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.767128 |        74.4309 |    3.068   |
| k-d_tree_sklearn     |     0.612353 |       182.816  |    3.95966 |
| Bori_Aron_solution-1 |     0.449611 |       142.612  |   16.6402  |