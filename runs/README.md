# 2026-08-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     6.46054  |       0.740746 |   0.330629 |
| k-d_tree_polars      |     0.349691 |       0.337184 |   0.341123 |
| barab-szabi-1        |     0.325609 |       0.313505 |   0.346943 |
| Bori_Aron_solution-1 |     4.02344  |       0.868025 |   0.360707 |
| k-d_tree_pandas      |     0.326293 |       0.303591 |   0.42318  |
| solution-1           |     6.90076  |       1e-06    |   0.443729 |
| k-d_tree_sklearn     |     3.03541  |       0.986754 |   0.798364 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.334917 |       0.319511 |   0.344697 |
| barab-szabi-1        |     0.332846 |       0.317147 |   0.34889  |
| barab-szabi-2        |     0.339092 |       0.353413 |   0.349553 |
| Bori_Aron_solution-1 |     0.335696 |       0.426544 |   0.416453 |
| k-d_tree_pandas      |     0.332436 |       0.29778  |   0.42029  |
| k-d_tree_sklearn     |     0.341059 |       0.748899 |   0.817599 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.332411 |       0.483453 |   0.341885 |
| k-d_tree_polars      |     0.341709 |       0.341352 |   0.36194  |
| barab-szabi-1        |     0.332889 |       0.382648 |   0.372984 |
| Bori_Aron_solution-1 |     0.32889  |       0.478333 |   0.439517 |
| k-d_tree_pandas      |     0.332113 |       0.365911 |   0.451438 |
| k-d_tree_sklearn     |     0.344699 |       0.822834 |   0.821455 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.331816 |       0.427851 |   0.375052 |
| k-d_tree_polars      |     0.332807 |       0.562969 |   0.415557 |
| Bori_Aron_solution-1 |     0.347952 |       0.564946 |   0.430653 |
| barab-szabi-1        |     0.335402 |       0.451169 |   0.433825 |
| k-d_tree_pandas      |     0.33365  |       0.401857 |   0.526831 |
| k-d_tree_sklearn     |     0.337282 |       0.963489 |   0.843102 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.330009 |       0.67616  |   0.428382 |
| Bori_Aron_solution-1 |     0.328695 |       1.0276   |   0.456595 |
| k-d_tree_polars      |     0.360981 |       0.831949 |   0.66394  |
| barab-szabi-1        |     0.333611 |       0.75574  |   0.688798 |
| k-d_tree_pandas      |     0.327503 |       0.547796 |   0.821117 |
| k-d_tree_sklearn     |     0.340325 |       1.61659  |   0.870034 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.336936 |        3.99717 |   0.62678  |
| Bori_Aron_solution-1 |     0.342374 |        8.09665 |   0.754563 |
| k-d_tree_sklearn     |     0.324551 |       12.6191  |   0.993663 |
| barab-szabi-1        |     0.335521 |        4.39853 |   5.33654  |
| k-d_tree_pandas      |     0.330584 |        2.80144 |   5.54548  |
| k-d_tree_polars      |     0.331886 |        4.00148 |   6.51345  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.51509  |        64.6675 |    4.15723 |
| k-d_tree_sklearn     |     1.95545  |       171.719  |    4.29213 |
| Bori_Aron_solution-1 |     0.344318 |       132.695  |   68.7676  |