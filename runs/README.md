# 2026-11-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.90562  |       1e-06    |   0.278465 |
| k-d_tree_polars      |     0.369437 |       0.347417 |   0.348895 |
| barab-szabi-2        |     0.346739 |       0.343038 |   0.351611 |
| barab-szabi-1        |     8.59178  |       0.351049 |   0.361658 |
| Bori_Aron_solution-1 |     0.371735 |       0.443642 |   0.453996 |
| k-d_tree_pandas      |     0.342063 |       0.326507 |   0.475702 |
| k-d_tree_sklearn     |     2.51951  |       0.810818 |   0.861018 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.35188  |       0.400979 |   0.352015 |
| barab-szabi-2        |     0.349953 |       0.385875 |   0.359402 |
| k-d_tree_polars      |     0.35913  |       0.384771 |   0.366208 |
| Bori_Aron_solution-1 |     0.349315 |       0.442991 |   0.439115 |
| k-d_tree_pandas      |     0.363897 |       0.329451 |   0.481148 |
| k-d_tree_sklearn     |     0.352201 |       0.810739 |   0.857814 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.360084 |       0.359102 |   0.35875  |
| barab-szabi-1        |     0.352736 |       0.359509 |   0.369924 |
| k-d_tree_polars      |     0.358122 |       0.365224 |   0.378857 |
| Bori_Aron_solution-1 |     0.34545  |       0.473616 |   0.44102  |
| k-d_tree_pandas      |     0.358506 |       0.334414 |   0.482286 |
| k-d_tree_sklearn     |     0.360212 |       0.87744  |   0.875082 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.353957 |       0.421495 |   0.388075 |
| barab-szabi-1        |     0.362839 |       0.470414 |   0.463469 |
| Bori_Aron_solution-1 |     0.361305 |       0.64206  |   0.469481 |
| k-d_tree_polars      |     0.361042 |       0.471284 |   0.532177 |
| k-d_tree_pandas      |     0.396375 |       0.393444 |   0.567876 |
| k-d_tree_sklearn     |     0.368725 |       1.03911  |   0.914102 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.375    |       0.684633 |   0.513187 |
| Bori_Aron_solution-1 |     0.375144 |       1.28133  |   0.522408 |
| k-d_tree_polars      |     0.368312 |       0.93338  |   0.817202 |
| barab-szabi-1        |     0.358114 |       0.824171 |   0.859431 |
| k-d_tree_pandas      |     0.38099  |       0.633411 |   0.984363 |
| k-d_tree_sklearn     |     0.375589 |       2.09876  |   1.08483  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.369063 |        4.84303 |   0.725028 |
| Bori_Aron_solution-1 |     0.383613 |        9.45125 |   0.920676 |
| k-d_tree_sklearn     |     0.349194 |       15.2679  |   1.18376  |
| barab-szabi-1        |     0.373908 |        5.65164 |   6.41908  |
| k-d_tree_polars      |     0.344383 |        4.99521 |   6.42906  |
| k-d_tree_pandas      |     0.367517 |        3.18152 |   6.55794  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.440233 |       229.754  |    3.05518 |
| barab-szabi-2        |     0.36552  |        74.9456 |    3.5453  |
| Bori_Aron_solution-1 |     0.366961 |       145.912  |   33.7527  |