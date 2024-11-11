# 2024-11-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     1.08907  |       0.397535 |   0.389426 |
| barab-szabi-1        |     0.6289   |       0.400809 |   0.396419 |
| barab-szabi-2        |     0.689257 |       0.398086 |   0.398104 |
| solution-1           |     8.03035  |       1e-06    |   0.47201  |
| Bori_Aron_solution-1 |     0.634094 |       0.546304 |   0.533015 |
| k-d_tree_pandas      |     0.624329 |       0.385222 |   0.56181  |
| k-d_tree_sklearn     |    10.6247   |       1.32769  |   0.984392 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.648283 |       0.423572 |   0.394608 |
| barab-szabi-1        |     0.619699 |       0.410119 |   0.405273 |
| k-d_tree_polars      |     0.641219 |       0.439888 |   0.416013 |
| Bori_Aron_solution-1 |     0.623575 |       0.545773 |   0.543682 |
| k-d_tree_pandas      |     0.631119 |       0.394515 |   0.548481 |
| k-d_tree_sklearn     |     0.626674 |       0.905976 |   0.978716 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639633 |       0.406599 |   0.401922 |
| k-d_tree_polars      |     0.636239 |       0.432082 |   0.422685 |
| barab-szabi-1        |     0.620288 |       0.437579 |   0.425279 |
| Bori_Aron_solution-1 |     0.620622 |       0.593934 |   0.535075 |
| k-d_tree_pandas      |     0.631952 |       0.403104 |   0.576326 |
| k-d_tree_sklearn     |     0.628945 |       0.939136 |   1.01918  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622515 |       0.484662 |   0.447712 |
| k-d_tree_polars      |     0.628621 |       0.55153  |   0.52386  |
| barab-szabi-1        |     0.637999 |       0.558856 |   0.537293 |
| Bori_Aron_solution-1 |     0.62606  |       0.746735 |   0.539407 |
| k-d_tree_pandas      |     0.631144 |       0.486873 |   0.716781 |
| k-d_tree_sklearn     |     0.630264 |       1.17067  |   1.07057  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623031 |       0.72095  |   0.476111 |
| Bori_Aron_solution-1 |     0.613856 |       1.39488  |   0.564331 |
| k-d_tree_polars      |     0.618174 |       0.877697 |   0.865061 |
| barab-szabi-1        |     0.621825 |       0.873462 |   0.910624 |
| k-d_tree_sklearn     |     0.617481 |       2.01486  |   1.14027  |
| k-d_tree_pandas      |     0.620334 |       0.762762 |   1.14779  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620703 |        5.53292 |   0.756762 |
| Bori_Aron_solution-1 |     0.612936 |       10.9655  |   0.818161 |
| k-d_tree_sklearn     |     0.621816 |       16.6741  |   1.27526  |
| k-d_tree_polars      |     0.632741 |        4.98729 |   6.68187  |
| barab-szabi-1        |     0.62683  |        4.91696 |   6.75063  |
| k-d_tree_pandas      |     0.637614 |        3.89578 |   7.08997  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.657407 |        77.5471 |    3.14224 |
| k-d_tree_sklearn     |     0.623988 |       237.872  |    4.32667 |
| Bori_Aron_solution-1 |     0.633422 |       156.228  |   15.659   |