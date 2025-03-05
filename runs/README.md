# 2025-03-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577708 |       0.404827 |   0.399947 |
| k-d_tree_polars      |     0.577059 |       0.400899 |   0.409317 |
| barab-szabi-1        |     0.617084 |       0.423334 |   0.474491 |
| Bori_Aron_solution-1 |     0.568069 |       0.540257 |   0.537586 |
| solution-1           |     7.80435  |       1e-06    |   0.566865 |
| k-d_tree_pandas      |     8.15997  |       0.447284 |   0.780143 |
| k-d_tree_sklearn     |     3.04441  |       1.10677  |   1.0239   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.595626 |       0.412847 |   0.404718 |
| barab-szabi-1        |     0.585062 |       0.410116 |   0.411917 |
| k-d_tree_polars      |     0.608662 |       0.405726 |   0.412756 |
| Bori_Aron_solution-1 |     0.584912 |       0.550329 |   0.540211 |
| k-d_tree_pandas      |     0.585047 |       0.38534  |   0.559315 |
| k-d_tree_sklearn     |     0.599021 |       0.966776 |   1.02799  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587792 |       0.424005 |   0.418037 |
| k-d_tree_polars      |     0.586479 |       0.436631 |   0.436405 |
| barab-szabi-1        |     0.600729 |       0.439663 |   0.437541 |
| Bori_Aron_solution-1 |     0.585507 |       0.58159  |   0.546966 |
| k-d_tree_pandas      |     0.587154 |       0.404261 |   0.597507 |
| k-d_tree_sklearn     |     0.593204 |       1.01756  |   1.0682   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588317 |       0.490488 |   0.455405 |
| k-d_tree_polars      |     0.588437 |       0.540256 |   0.532881 |
| barab-szabi-1        |     0.592102 |       0.543499 |   0.545838 |
| Bori_Aron_solution-1 |     0.592577 |       0.77337  |   0.581411 |
| k-d_tree_pandas      |     0.592522 |       0.478636 |   0.730163 |
| k-d_tree_sklearn     |     0.603863 |       1.22714  |   1.0955   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586743 |       0.736887 |   0.482154 |
| Bori_Aron_solution-1 |     0.582456 |       1.39399  |   0.588385 |
| k-d_tree_polars      |     0.587957 |       0.869055 |   0.883832 |
| barab-szabi-1        |     0.587797 |       0.866626 |   0.918876 |
| k-d_tree_pandas      |     0.588392 |       0.750077 |   1.17494  |
| k-d_tree_sklearn     |     0.592612 |       2.04718  |   1.20606  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.59381  |        5.29178 |   0.735366 |
| Bori_Aron_solution-1 |     0.60921  |       10.5796  |   0.901259 |
| k-d_tree_sklearn     |     0.595145 |       16.2963  |   1.33782  |
| k-d_tree_polars      |     0.592599 |        4.94835 |   6.61941  |
| barab-szabi-1        |     0.58968  |        4.94303 |   6.65112  |
| k-d_tree_pandas      |     0.587853 |        3.79701 |   7.03346  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.798105 |        73.3249 |    2.96333 |
| k-d_tree_sklearn     |     0.659684 |       228.596  |    4.12838 |
| Bori_Aron_solution-1 |     0.59137  |       158.682  |   15.114   |