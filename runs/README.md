# 2026-03-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.33282  |       1e-06    |   0.399438 |
| barab-szabi-2        |     0.499152 |       0.454515 |   0.443248 |
| k-d_tree_polars      |     0.513516 |       0.493513 |   0.448529 |
| barab-szabi-1        |     8.61798  |       0.453565 |   0.525582 |
| k-d_tree_pandas      |     0.489993 |       0.398015 |   0.565286 |
| Bori_Aron_solution-1 |     0.490481 |       0.554486 |   0.565331 |
| k-d_tree_sklearn     |     3.06489  |       1.08183  |   1.08984  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.500609 |       0.423447 |   0.448884 |
| barab-szabi-2        |     0.50285  |       0.443966 |   0.456243 |
| barab-szabi-1        |     0.509341 |       0.418682 |   0.45848  |
| Bori_Aron_solution-1 |     0.496864 |       0.58028  |   0.562697 |
| k-d_tree_pandas      |     0.508627 |       0.41273  |   0.582465 |
| k-d_tree_sklearn     |     0.50998  |       1.00966  |   1.10979  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.509915 |       0.476681 |   0.459482 |
| k-d_tree_polars      |     0.509865 |       0.451548 |   0.473769 |
| barab-szabi-1        |     0.499128 |       0.453921 |   0.488292 |
| Bori_Aron_solution-1 |     0.49689  |       0.615309 |   0.573331 |
| k-d_tree_pandas      |     0.500535 |       0.45629  |   0.619462 |
| k-d_tree_sklearn     |     0.508141 |       1.04217  |   1.12491  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.50724  |       0.51541  |   0.48416  |
| k-d_tree_polars      |     0.501612 |       0.57408  |   0.569813 |
| Bori_Aron_solution-1 |     0.492646 |       0.802609 |   0.57451  |
| barab-szabi-1        |     0.502291 |       0.581552 |   0.591014 |
| k-d_tree_pandas      |     0.499009 |       0.521059 |   0.751109 |
| k-d_tree_sklearn     |     0.501398 |       1.2779   |   1.18581  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.501228 |       0.740329 |   0.523902 |
| Bori_Aron_solution-1 |     0.496178 |       1.49209  |   0.594077 |
| k-d_tree_polars      |     0.506994 |       0.943211 |   0.934585 |
| barab-szabi-1        |     0.499031 |       0.93776  |   0.964756 |
| k-d_tree_pandas      |     0.499781 |       0.84031  |   1.21279  |
| k-d_tree_sklearn     |     0.503975 |       2.19059  |   1.28061  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.501782 |        5.2249  |   0.751789 |
| Bori_Aron_solution-1 |     0.500768 |       11.2866  |   0.832833 |
| k-d_tree_sklearn     |     0.508877 |       17.0768  |   1.3311   |
| k-d_tree_polars      |     0.505419 |        5.54796 |   6.77304  |
| barab-szabi-1        |     0.504839 |        5.62539 |   6.8527   |
| k-d_tree_pandas      |     0.49901  |        4.53838 |   7.00662  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.503016 |        72.3195 |    2.71108 |
| k-d_tree_sklearn     |     0.816166 |       240.699  |    4.03726 |
| Bori_Aron_solution-1 |     0.503528 |       150.754  |   20.7782  |