# 2024-06-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.32858  |       1e-06    |   0.360202 |
| barab-szabi-1        |     0.827354 |       0.40794  |   0.395576 |
| barab-szabi-2        |     0.794664 |       0.405677 |   0.39772  |
| k-d_tree_polars      |     0.782025 |       0.404066 |   0.402426 |
| Bori_Aron_solution-1 |     0.770905 |       0.52742  |   0.536657 |
| k-d_tree_pandas      |     8.9849   |       0.40073  |   0.572248 |
| k-d_tree_sklearn     |     3.37457  |       0.981613 |   0.754546 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.824098 |       0.411191 |   0.399357 |
| barab-szabi-2        |     0.807957 |       0.39537  |   0.405588 |
| k-d_tree_polars      |     0.809168 |       0.410129 |   0.410917 |
| Bori_Aron_solution-1 |     0.80675  |       0.547418 |   0.527689 |
| k-d_tree_pandas      |     0.81944  |       0.401329 |   0.537251 |
| k-d_tree_sklearn     |     0.813473 |       0.939277 |   0.749395 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.807117 |       0.42452  |   0.421475 |
| k-d_tree_polars      |     0.821486 |       0.435085 |   0.426559 |
| barab-szabi-1        |     0.810836 |       0.440351 |   0.432256 |
| Bori_Aron_solution-1 |     0.799046 |       0.574444 |   0.540517 |
| k-d_tree_pandas      |     0.816979 |       0.405566 |   0.57827  |
| k-d_tree_sklearn     |     0.831422 |       0.982529 |   0.77405  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.808148 |       0.472399 |   0.440059 |
| k-d_tree_polars      |     0.826858 |       0.58543  |   0.535767 |
| barab-szabi-1        |     0.82868  |       0.566288 |   0.538386 |
| Bori_Aron_solution-1 |     0.810517 |       0.751271 |   0.562705 |
| k-d_tree_pandas      |     0.825887 |       0.493052 |   0.728932 |
| k-d_tree_sklearn     |     0.836378 |       1.25269  |   0.853077 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.81172  |       0.719763 |   0.490147 |
| Bori_Aron_solution-1 |     0.818656 |       1.42525  |   0.575376 |
| k-d_tree_polars      |     0.811969 |       0.878256 |   0.884902 |
| barab-szabi-1        |     0.827757 |       0.884522 |   0.935137 |
| k-d_tree_sklearn     |     0.828804 |       2.04418  |   0.938285 |
| k-d_tree_pandas      |     0.814349 |       0.780723 |   1.16802  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.821068 |        5.51295 |   0.795636 |
| Bori_Aron_solution-1 |     0.828716 |       10.872   |   0.858302 |
| k-d_tree_sklearn     |     0.825828 |       16.7963  |   1.11342  |
| k-d_tree_polars      |     0.829    |        4.98194 |   6.74908  |
| barab-szabi-1        |     0.81785  |        4.97528 |   6.79562  |
| k-d_tree_pandas      |     0.82844  |        4.00258 |   7.11372  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.00355  |        75.2221 |     4.1126 |
| k-d_tree_sklearn     |     0.905323 |       235.201  |     4.5865 |
| Bori_Aron_solution-1 |     0.812484 |       145.894  |    18.9683 |