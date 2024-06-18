# 2024-06-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     9.36003  |       1e-06    |   0.350049 |
| barab-szabi-2        |     0.764555 |       0.389878 |   0.379871 |
| barab-szabi-1        |     0.804544 |       0.391881 |   0.383671 |
| k-d_tree_polars      |     0.764649 |       0.405667 |   0.393966 |
| Bori_Aron_solution-1 |     0.759467 |       0.517242 |   0.52493  |
| k-d_tree_pandas      |     8.80455  |       0.392332 |   0.548332 |
| k-d_tree_sklearn     |     3.5322   |       0.937099 |   0.71775  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.806693 |       0.40529  |   0.393952 |
| barab-szabi-2        |     0.80055  |       0.417188 |   0.400139 |
| barab-szabi-1        |     0.808161 |       0.411817 |   0.408171 |
| Bori_Aron_solution-1 |     0.79579  |       0.521076 |   0.525982 |
| k-d_tree_pandas      |     0.798615 |       0.383829 |   0.531703 |
| k-d_tree_sklearn     |     0.836921 |       0.943086 |   0.737909 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.815951 |       0.412665 |   0.424446 |
| barab-szabi-1        |     0.830082 |       0.455945 |   0.438757 |
| k-d_tree_polars      |     0.825128 |       0.442379 |   0.444357 |
| Bori_Aron_solution-1 |     0.835861 |       0.586686 |   0.529044 |
| k-d_tree_pandas      |     0.813134 |       0.400572 |   0.598382 |
| k-d_tree_sklearn     |     0.828404 |       1.01914  |   0.834912 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.815807 |       0.475766 |   0.439987 |
| barab-szabi-1        |     0.822072 |       0.558328 |   0.533719 |
| k-d_tree_polars      |     0.827551 |       0.556166 |   0.544202 |
| Bori_Aron_solution-1 |     0.811933 |       0.759948 |   0.555468 |
| k-d_tree_pandas      |     0.816926 |       0.493942 |   0.728194 |
| k-d_tree_sklearn     |     0.806968 |       1.18826  |   0.840155 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.801253 |       0.727878 |   0.472155 |
| Bori_Aron_solution-1 |     0.787458 |       1.4013   |   0.555944 |
| k-d_tree_polars      |     0.80541  |       0.871228 |   0.877165 |
| barab-szabi-1        |     0.851875 |       0.872546 |   0.923273 |
| k-d_tree_sklearn     |     0.834738 |       2.03858  |   0.944512 |
| k-d_tree_pandas      |     0.81485  |       0.754467 |   1.16575  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.814874 |        5.61526 |   0.794315 |
| Bori_Aron_solution-1 |     0.786559 |       11.2625  |   0.872579 |
| k-d_tree_sklearn     |     0.808813 |       16.8376  |   1.1001   |
| k-d_tree_polars      |     0.801953 |        5.0144  |   6.77905  |
| barab-szabi-1        |     0.803655 |        5.02763 |   6.83881  |
| k-d_tree_pandas      |     0.813083 |        4.07047 |   7.24848  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.0735   |        79.5776 |    3.76594 |
| k-d_tree_sklearn     |     0.928151 |       236.15   |    4.53288 |
| Bori_Aron_solution-1 |     0.788459 |       153.679  |   17.4101  |