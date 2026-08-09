# 2026-08-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.31508  |       1e-06    |   0.424595 |
| barab-szabi-1        |     0.493057 |       0.436157 |   0.47423  |
| barab-szabi-2        |     0.509596 |       0.46226  |   0.478085 |
| Bori_Aron_solution-1 |     0.900104 |       0.584284 |   0.58805  |
| k-d_tree_pandas      |     0.49631  |       0.406141 |   0.588454 |
| k-d_tree_polars      |     9.34975  |       0.487684 |   0.623774 |
| k-d_tree_sklearn     |     3.27969  |       1.3276   |   1.13932  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518016 |       0.491696 |   0.477259 |
| k-d_tree_polars      |     0.499028 |       0.456162 |   0.48378  |
| barab-szabi-1        |     0.506135 |       0.459218 |   0.487876 |
| Bori_Aron_solution-1 |     0.490905 |       0.601759 |   0.592569 |
| k-d_tree_pandas      |     0.512513 |       0.429539 |   0.615072 |
| k-d_tree_sklearn     |     0.513936 |       1.09791  |   1.14786  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488331 |       0.472052 |   0.475089 |
| barab-szabi-1        |     0.493341 |       0.467329 |   0.487458 |
| k-d_tree_polars      |     0.510581 |       0.485571 |   0.50034  |
| Bori_Aron_solution-1 |     0.49403  |       0.619454 |   0.605628 |
| k-d_tree_pandas      |     0.492575 |       0.413389 |   0.623738 |
| k-d_tree_sklearn     |     0.494943 |       1.14182  |   1.15548  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470803 |       0.513246 |   0.485219 |
| Bori_Aron_solution-1 |     0.469002 |       0.776793 |   0.568753 |
| k-d_tree_polars      |     0.485213 |       0.594872 |   0.580765 |
| barab-szabi-1        |     0.48813  |       0.567756 |   0.610476 |
| k-d_tree_pandas      |     0.481352 |       0.510174 |   0.736381 |
| k-d_tree_sklearn     |     0.478754 |       1.27133  |   1.16498  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.503611 |       0.769308 |   0.548622 |
| Bori_Aron_solution-1 |     0.485291 |       1.49955  |   0.613578 |
| k-d_tree_polars      |     0.471161 |       0.962582 |   0.975535 |
| barab-szabi-1        |     0.491013 |       0.952193 |   0.988856 |
| k-d_tree_pandas      |     0.495578 |       0.81633  |   1.21521  |
| k-d_tree_sklearn     |     0.496131 |       2.25791  |   1.2782   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474757 |        5.44793 |   0.794414 |
| Bori_Aron_solution-1 |     0.471313 |       11.0418  |   0.829728 |
| k-d_tree_sklearn     |     0.484921 |       17.1505  |   1.3364   |
| barab-szabi-1        |     0.473827 |        5.21049 |   6.6688   |
| k-d_tree_polars      |     0.48646  |        5.34385 |   6.68742  |
| k-d_tree_pandas      |     0.473483 |        4.37192 |   7.02442  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572191 |        71.1331 |    3.14357 |
| k-d_tree_sklearn     |     0.837417 |       240.413  |    4.11921 |
| Bori_Aron_solution-1 |     0.487823 |       158.828  |   21.1268  |