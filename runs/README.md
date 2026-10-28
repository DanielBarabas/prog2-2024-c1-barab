# 2026-10-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.94922  |       1e-06    |   0.36422  |
| barab-szabi-2        |     0.470279 |       0.434355 |   0.437037 |
| k-d_tree_polars      |     0.480837 |       0.432365 |   0.444288 |
| barab-szabi-1        |     9.06569  |       0.460864 |   0.458434 |
| k-d_tree_pandas      |     0.466955 |       0.397951 |   0.560808 |
| Bori_Aron_solution-1 |     0.471849 |       0.621631 |   0.56986  |
| k-d_tree_sklearn     |     3.29719  |       1.06456  |   1.11004  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483278 |       0.461392 |   0.437334 |
| barab-szabi-1        |     0.480123 |       0.443068 |   0.444083 |
| k-d_tree_polars      |     0.478961 |       0.444389 |   0.448786 |
| k-d_tree_pandas      |     0.47949  |       0.410827 |   0.567974 |
| Bori_Aron_solution-1 |     0.47974  |       0.574694 |   0.575375 |
| k-d_tree_sklearn     |     0.488884 |       1.07858  |   1.15854  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498248 |       0.473973 |   0.451987 |
| barab-szabi-1        |     0.483021 |       0.472669 |   0.473022 |
| k-d_tree_polars      |     0.485077 |       0.485048 |   0.473895 |
| Bori_Aron_solution-1 |     0.480451 |       0.628844 |   0.567266 |
| k-d_tree_pandas      |     0.482023 |       0.433623 |   0.609999 |
| k-d_tree_sklearn     |     0.505412 |       1.07812  |   1.14305  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484448 |       0.52812  |   0.473559 |
| k-d_tree_polars      |     0.486725 |       0.59669  |   0.576503 |
| Bori_Aron_solution-1 |     0.482123 |       0.836205 |   0.586483 |
| barab-szabi-1        |     0.486485 |       0.582932 |   0.600498 |
| k-d_tree_pandas      |     0.488276 |       0.517835 |   0.746518 |
| k-d_tree_sklearn     |     0.485751 |       1.34761  |   1.2104   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475572 |       0.809044 |   0.558271 |
| Bori_Aron_solution-1 |     0.483947 |       1.52508  |   0.635242 |
| k-d_tree_polars      |     0.483283 |       0.903832 |   1.02762  |
| barab-szabi-1        |     0.485411 |       0.909972 |   1.08387  |
| k-d_tree_pandas      |     0.483691 |       0.795486 |   1.23204  |
| k-d_tree_sklearn     |     0.481402 |       2.23829  |   1.24584  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499372 |        6.28796 |   0.908327 |
| Bori_Aron_solution-1 |     0.491174 |       12.1237  |   1.18986  |
| k-d_tree_sklearn     |     0.516807 |       18.1438  |   1.41176  |
| barab-szabi-1        |     0.485575 |        5.03803 |   7.99146  |
| k-d_tree_polars      |     0.507441 |        5.05168 |   8.18535  |
| k-d_tree_pandas      |     0.491337 |        4.05305 |   8.34053  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.469364 |        255.19  |    3.63598 |
| barab-szabi-2        |     0.508492 |         78.893 |    4.03069 |
| Bori_Aron_solution-1 |     0.458571 |        158.112 |   22.0744  |