# 2025-10-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.551713 |       0.409492 |   0.429691 |
| k-d_tree_polars      |     0.55002  |       0.413972 |   0.436447 |
| barab-szabi-2        |     0.593211 |       0.977716 |   0.436605 |
| Bori_Aron_solution-1 |     0.541681 |       0.551747 |   0.572913 |
| solution-1           |     8.19826  |       1e-06    |   0.803083 |
| k-d_tree_sklearn     |     3.11046  |       1.52528  |   1.0685   |
| k-d_tree_pandas      |     8.40889  |       0.458483 |   1.07121  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.557773 |       0.418175 |   0.432556 |
| barab-szabi-2        |     0.580402 |       0.45535  |   0.447802 |
| barab-szabi-1        |     0.57492  |       0.422579 |   0.451067 |
| Bori_Aron_solution-1 |     0.558163 |       0.577348 |   0.569842 |
| k-d_tree_pandas      |     0.576202 |       0.419498 |   0.599015 |
| k-d_tree_sklearn     |     0.589977 |       1.07863  |   1.15851  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571354 |       0.442561 |   0.447902 |
| barab-szabi-1        |     0.552318 |       0.468267 |   0.461172 |
| k-d_tree_polars      |     0.548368 |       0.43902  |   0.482746 |
| Bori_Aron_solution-1 |     0.545372 |       0.604714 |   0.553466 |
| k-d_tree_pandas      |     0.562875 |       0.419945 |   0.605335 |
| k-d_tree_sklearn     |     0.57185  |       1.04019  |   1.11102  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546314 |       0.527766 |   0.482392 |
| k-d_tree_polars      |     0.57668  |       0.576676 |   0.583742 |
| barab-szabi-1        |     0.554939 |       0.593154 |   0.604879 |
| Bori_Aron_solution-1 |     0.575972 |       0.845951 |   0.630456 |
| k-d_tree_pandas      |     0.550472 |       0.512913 |   0.739956 |
| k-d_tree_sklearn     |     0.551118 |       1.27777  |   1.14555  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545937 |       0.75175  |   0.507392 |
| Bori_Aron_solution-1 |     0.565512 |       1.54486  |   0.62731  |
| k-d_tree_polars      |     0.551517 |       0.976525 |   0.94524  |
| barab-szabi-1        |     0.549681 |       0.956414 |   0.954938 |
| k-d_tree_pandas      |     0.569923 |       0.803939 |   1.16999  |
| k-d_tree_sklearn     |     0.553219 |       2.14297  |   1.22436  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565063 |        5.56116 |   0.770175 |
| Bori_Aron_solution-1 |     0.546088 |       11.2799  |   0.855096 |
| k-d_tree_sklearn     |     0.564059 |       17.5949  |   1.37127  |
| k-d_tree_polars      |     0.627219 |        5.52449 |   6.70578  |
| barab-szabi-1        |     0.55889  |        5.55638 |   7.06989  |
| k-d_tree_pandas      |     0.576834 |        4.76897 |   7.52068  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553479 |        76.1764 |    2.82084 |
| k-d_tree_sklearn     |     0.55867  |       247.136  |    4.23752 |
| Bori_Aron_solution-1 |     0.80541  |       153.263  |   17.4358  |