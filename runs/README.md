# 2025-06-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.533638 |       0.399008 |   0.419658 |
| barab-szabi-2        |     0.532216 |       0.413726 |   0.420996 |
| barab-szabi-1        |     0.532728 |       0.430556 |   0.484137 |
| Bori_Aron_solution-1 |     0.531173 |       0.557076 |   0.542063 |
| solution-1           |     7.3115   |       1e-06    |   0.603348 |
| k-d_tree_pandas      |     7.67908  |       0.437052 |   0.707311 |
| k-d_tree_sklearn     |     3.04926  |       1.12911  |   1.04664  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55351  |       0.415886 |   0.417381 |
| k-d_tree_polars      |     0.550965 |       0.406862 |   0.421695 |
| barab-szabi-1        |     0.550483 |       0.40585  |   0.472054 |
| k-d_tree_pandas      |     0.546549 |       0.387742 |   0.544828 |
| Bori_Aron_solution-1 |     0.538682 |       0.543424 |   0.546206 |
| k-d_tree_sklearn     |     0.55607  |       0.966841 |   1.05017  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549894 |       0.42907  |   0.43     |
| k-d_tree_polars      |     0.546794 |       0.429799 |   0.446377 |
| barab-szabi-1        |     0.552349 |       0.441389 |   0.449263 |
| Bori_Aron_solution-1 |     0.539653 |       0.58371  |   0.545801 |
| k-d_tree_pandas      |     0.548321 |       0.399835 |   0.595922 |
| k-d_tree_sklearn     |     0.54884  |       1.00809  |   1.07816  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553879 |       0.488808 |   0.457376 |
| k-d_tree_polars      |     0.544982 |       0.537228 |   0.546362 |
| Bori_Aron_solution-1 |     0.537097 |       0.763945 |   0.550879 |
| barab-szabi-1        |     0.549904 |       0.537852 |   0.560147 |
| k-d_tree_pandas      |     0.546707 |       0.481249 |   0.735897 |
| k-d_tree_sklearn     |     0.550083 |       1.22512  |   1.1089   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546033 |       0.739601 |   0.491197 |
| Bori_Aron_solution-1 |     0.544741 |       1.41146  |   0.583922 |
| k-d_tree_polars      |     0.550621 |       0.880503 |   0.90571  |
| barab-szabi-1        |     0.553748 |       0.882055 |   0.941924 |
| k-d_tree_pandas      |     0.551274 |       0.757467 |   1.18288  |
| k-d_tree_sklearn     |     0.548645 |       2.05275  |   1.20861  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553384 |        5.33936 |   0.716138 |
| Bori_Aron_solution-1 |     0.547104 |       10.8524  |   0.857158 |
| k-d_tree_sklearn     |     0.554122 |       16.4603  |   1.30014  |
| barab-szabi-1        |     0.560323 |        4.98896 |   6.69464  |
| k-d_tree_polars      |     0.548055 |        5.00094 |   6.69499  |
| k-d_tree_pandas      |     0.546523 |        3.91852 |   7.21643  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.934841 |        71.0524 |    2.71371 |
| k-d_tree_sklearn     |     0.645725 |       228.093  |    3.88706 |
| Bori_Aron_solution-1 |     0.548212 |       142.685  |   17.7707  |