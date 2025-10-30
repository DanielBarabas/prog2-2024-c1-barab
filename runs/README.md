# 2025-10-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.33061  |       1e-06    |   0.37543  |
| barab-szabi-2        |     0.534184 |       0.450192 |   0.431845 |
| k-d_tree_polars      |     0.547719 |       0.409753 |   0.432509 |
| barab-szabi-1        |     0.560591 |       0.422043 |   0.446191 |
| Bori_Aron_solution-1 |     0.53967  |       0.554994 |   0.605288 |
| k-d_tree_pandas      |     8.18786  |       0.423514 |   0.650316 |
| k-d_tree_sklearn     |     2.95588  |       1.06947  |   1.11149  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542476 |       0.42599  |   0.429947 |
| barab-szabi-1        |     0.541228 |       0.417628 |   0.43354  |
| k-d_tree_polars      |     0.546569 |       0.413786 |   0.435506 |
| Bori_Aron_solution-1 |     0.535496 |       0.55653  |   0.535583 |
| k-d_tree_pandas      |     0.55597  |       0.397327 |   0.564689 |
| k-d_tree_sklearn     |     0.563141 |       0.974173 |   1.06337  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538416 |       0.435473 |   0.436057 |
| barab-szabi-1        |     0.545948 |       0.452709 |   0.45883  |
| k-d_tree_polars      |     0.548204 |       0.442314 |   0.465188 |
| Bori_Aron_solution-1 |     0.536717 |       0.614131 |   0.564553 |
| k-d_tree_pandas      |     0.550508 |       0.406771 |   0.594428 |
| k-d_tree_sklearn     |     0.54217  |       0.997724 |   1.11113  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547518 |       0.505277 |   0.471715 |
| k-d_tree_polars      |     0.541755 |       0.560109 |   0.555525 |
| barab-szabi-1        |     0.541855 |       0.563749 |   0.566307 |
| Bori_Aron_solution-1 |     0.533768 |       0.791233 |   0.569924 |
| k-d_tree_pandas      |     0.546088 |       0.509148 |   0.749674 |
| k-d_tree_sklearn     |     0.548456 |       1.25832  |   1.12898  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549619 |       0.771936 |   0.507365 |
| Bori_Aron_solution-1 |     0.535833 |       1.48974  |   0.596917 |
| k-d_tree_polars      |     0.541578 |       0.960932 |   0.949832 |
| barab-szabi-1        |     0.542113 |       0.954042 |   0.951495 |
| k-d_tree_pandas      |     0.544654 |       0.833309 |   1.19348  |
| k-d_tree_sklearn     |     0.558923 |       2.18891  |   1.22029  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546894 |        5.65777 |   0.777455 |
| Bori_Aron_solution-1 |     0.584724 |       11.6266  |   0.857147 |
| k-d_tree_sklearn     |     0.550572 |       17.9539  |   1.36584  |
| barab-szabi-1        |     0.554693 |        5.56734 |   7.23614  |
| k-d_tree_polars      |     0.599252 |        5.63635 |   7.32213  |
| k-d_tree_pandas      |     0.554018 |        4.66693 |   7.39383  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565557 |        77.9512 |    2.99997 |
| k-d_tree_sklearn     |     0.570004 |       254.463  |    4.3711  |
| Bori_Aron_solution-1 |     0.781651 |       156.439  |   17.7281  |