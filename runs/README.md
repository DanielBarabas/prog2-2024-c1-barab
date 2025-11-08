# 2025-11-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519835 |       0.510731 |   0.435434 |
| k-d_tree_polars      |     0.538922 |       0.409586 |   0.443956 |
| barab-szabi-1        |     0.536335 |       0.414113 |   0.450532 |
| solution-1           |     8.82638  |       1e-06    |   0.509821 |
| Bori_Aron_solution-1 |     0.534801 |       0.568623 |   0.592346 |
| k-d_tree_pandas      |     8.97664  |       0.44353  |   0.857743 |
| k-d_tree_sklearn     |     3.42805  |       1.19458  |   1.13605  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.536051 |       0.415382 |   0.435724 |
| barab-szabi-2        |     0.547402 |       0.433397 |   0.437411 |
| k-d_tree_polars      |     0.538779 |       0.419288 |   0.447028 |
| Bori_Aron_solution-1 |     0.53274  |       0.559891 |   0.551832 |
| k-d_tree_pandas      |     0.532869 |       0.400512 |   0.571001 |
| k-d_tree_sklearn     |     0.549042 |       0.988104 |   1.14928  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539348 |       0.442919 |   0.450363 |
| k-d_tree_polars      |     0.535326 |       0.444008 |   0.463126 |
| barab-szabi-1        |     0.536823 |       0.445341 |   0.53432  |
| Bori_Aron_solution-1 |     0.53073  |       0.613905 |   0.55268  |
| k-d_tree_pandas      |     0.540283 |       0.414583 |   0.61033  |
| k-d_tree_sklearn     |     0.542974 |       1.05849  |   1.11447  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543232 |       0.506867 |   0.474689 |
| Bori_Aron_solution-1 |     0.529827 |       0.804734 |   0.570409 |
| k-d_tree_polars      |     0.545146 |       0.56758  |   0.575173 |
| barab-szabi-1        |     0.53639  |       0.563431 |   0.582891 |
| k-d_tree_pandas      |     0.534998 |       0.507629 |   0.742554 |
| k-d_tree_sklearn     |     0.536779 |       1.26418  |   1.15163  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536052 |       0.753251 |   0.506303 |
| Bori_Aron_solution-1 |     0.529079 |       1.47837  |   0.596802 |
| k-d_tree_polars      |     0.538735 |       0.935096 |   0.920048 |
| barab-szabi-1        |     0.536595 |       0.944276 |   0.972097 |
| k-d_tree_pandas      |     0.532488 |       0.825154 |   1.20301  |
| k-d_tree_sklearn     |     0.550763 |       2.15947  |   1.27162  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540799 |        5.41804 |   0.770487 |
| Bori_Aron_solution-1 |     0.534312 |       11.516   |   0.848505 |
| k-d_tree_sklearn     |     0.545918 |       17.1319  |   1.33896  |
| k-d_tree_polars      |     0.533942 |        5.41575 |   6.77837  |
| barab-szabi-1        |     0.535688 |        5.40555 |   6.86446  |
| k-d_tree_pandas      |     0.537816 |        4.50548 |   7.22691  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536634 |        75.6527 |    2.85    |
| k-d_tree_sklearn     |     0.574554 |       245.285  |    4.32492 |
| Bori_Aron_solution-1 |     0.668947 |       155.391  |   15.6063  |