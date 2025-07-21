# 2025-07-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.86582  |       1e-06    |   0.392046 |
| barab-szabi-2        |     7.99596  |       0.541247 |   0.41857  |
| barab-szabi-1        |     0.537055 |       0.400747 |   0.419548 |
| k-d_tree_polars      |     0.565084 |       0.399812 |   0.425791 |
| k-d_tree_pandas      |     0.547454 |       0.384654 |   0.552824 |
| Bori_Aron_solution-1 |     0.533095 |       0.603259 |   0.614166 |
| k-d_tree_sklearn     |     3.25801  |       1.1536   |   1.04858  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593106 |       0.428615 |   0.4229   |
| barab-szabi-1        |     0.554556 |       0.411916 |   0.428751 |
| k-d_tree_polars      |     0.551378 |       0.417392 |   0.433439 |
| Bori_Aron_solution-1 |     0.556833 |       0.563694 |   0.551691 |
| k-d_tree_pandas      |     0.554306 |       0.387403 |   0.55313  |
| k-d_tree_sklearn     |     0.563264 |       1.00072  |   1.06155  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55058  |       0.433765 |   0.439958 |
| k-d_tree_polars      |     0.553441 |       0.438037 |   0.457668 |
| barab-szabi-1        |     0.576421 |       0.47178  |   0.499509 |
| k-d_tree_pandas      |     0.55299  |       0.414224 |   0.597583 |
| Bori_Aron_solution-1 |     0.580973 |       0.657271 |   0.604209 |
| k-d_tree_sklearn     |     0.580331 |       1.0281   |   1.06912  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614602 |       0.498861 |   0.459265 |
| k-d_tree_polars      |     0.547905 |       0.541455 |   0.549969 |
| Bori_Aron_solution-1 |     0.537176 |       0.757478 |   0.553974 |
| barab-szabi-1        |     0.550942 |       0.555638 |   0.55657  |
| k-d_tree_pandas      |     0.548983 |       0.485839 |   0.724519 |
| k-d_tree_sklearn     |     0.55158  |       1.23589  |   1.12453  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54444  |       0.729907 |   0.497494 |
| Bori_Aron_solution-1 |     0.541121 |       1.39231  |   0.579532 |
| k-d_tree_polars      |     0.549216 |       0.876276 |   0.888307 |
| barab-szabi-1        |     0.555777 |       0.883715 |   0.926749 |
| k-d_tree_pandas      |     0.54725  |       0.754493 |   1.15747  |
| k-d_tree_sklearn     |     0.560792 |       2.05116  |   1.19251  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544067 |        5.29144 |   0.725116 |
| Bori_Aron_solution-1 |     0.539975 |       10.709   |   0.847616 |
| k-d_tree_sklearn     |     0.561731 |       16.4763  |   1.28819  |
| barab-szabi-1        |     0.549828 |        5.04054 |   6.56391  |
| k-d_tree_polars      |     0.550061 |        4.97538 |   6.65698  |
| k-d_tree_pandas      |     0.560932 |        4.01647 |   7.09133  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559655 |         72.075 |    2.62343 |
| k-d_tree_sklearn     |     0.679802 |        227.869 |    3.89578 |
| Bori_Aron_solution-1 |     0.545347 |        143.809 |   18.3505  |