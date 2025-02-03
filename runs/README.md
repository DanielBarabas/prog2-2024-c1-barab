# 2025-02-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.2329   |       1e-06    |   0.375952 |
| barab-szabi-1        |     0.580962 |       0.401189 |   0.401849 |
| barab-szabi-2        |     7.4804   |       0.478611 |   0.409847 |
| k-d_tree_polars      |     0.591691 |       0.407946 |   0.410018 |
| k-d_tree_pandas      |     0.581027 |       0.381094 |   0.528421 |
| Bori_Aron_solution-1 |     0.575291 |       0.52916  |   0.53108  |
| k-d_tree_sklearn     |     2.92317  |       1.02523  |   1.01252  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581625 |       0.403083 |   0.402498 |
| k-d_tree_polars      |     0.581118 |       0.439361 |   0.40784  |
| barab-szabi-1        |     0.58568  |       0.41828  |   0.409139 |
| Bori_Aron_solution-1 |     0.581403 |       0.538335 |   0.530212 |
| k-d_tree_pandas      |     0.58504  |       0.388616 |   0.539948 |
| k-d_tree_sklearn     |     0.58646  |       0.944487 |   1.00994  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582435 |       0.419832 |   0.418753 |
| k-d_tree_polars      |     0.584454 |       0.44609  |   0.434532 |
| barab-szabi-1        |     0.58959  |       0.433879 |   0.436351 |
| Bori_Aron_solution-1 |     0.584138 |       0.586401 |   0.554734 |
| k-d_tree_pandas      |     0.591174 |       0.408003 |   0.586966 |
| k-d_tree_sklearn     |     0.586796 |       0.999685 |   1.04174  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591517 |       0.484205 |   0.447533 |
| k-d_tree_polars      |     0.606884 |       0.53738  |   0.533318 |
| barab-szabi-1        |     0.586648 |       0.53469  |   0.543486 |
| Bori_Aron_solution-1 |     0.580715 |       0.745614 |   0.547422 |
| k-d_tree_pandas      |     0.581821 |       0.481493 |   0.722216 |
| k-d_tree_sklearn     |     0.585834 |       1.21263  |   1.10288  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585418 |       0.723334 |   0.47812  |
| Bori_Aron_solution-1 |     0.575754 |       1.37686  |   0.572437 |
| k-d_tree_polars      |     0.579271 |       0.870263 |   0.901832 |
| barab-szabi-1        |     0.585965 |       0.874835 |   0.947393 |
| k-d_tree_pandas      |     0.600586 |       0.749189 |   1.16708  |
| k-d_tree_sklearn     |     0.606381 |       2.01752  |   1.21124  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584712 |        5.35097 |   0.7372   |
| Bori_Aron_solution-1 |     0.577456 |       10.55    |   0.879393 |
| k-d_tree_sklearn     |     0.584905 |       16.388   |   1.33356  |
| k-d_tree_polars      |     0.587932 |        4.88044 |   6.55443  |
| barab-szabi-1        |     0.598238 |        4.89198 |   6.60173  |
| k-d_tree_pandas      |     0.587338 |        3.85514 |   7.29043  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602436 |        75.5216 |    2.90484 |
| k-d_tree_sklearn     |     0.609727 |       230.013  |    4.66633 |
| Bori_Aron_solution-1 |     0.702099 |       152.917  |   17.828   |