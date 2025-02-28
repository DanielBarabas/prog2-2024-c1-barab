# 2025-02-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.33315  |       1e-06    |   0.367871 |
| k-d_tree_polars      |     0.584627 |       0.411308 |   0.413825 |
| barab-szabi-2        |     0.596839 |       0.418987 |   0.416307 |
| barab-szabi-1        |     0.583935 |       0.415463 |   0.420015 |
| Bori_Aron_solution-1 |     0.581281 |       0.559044 |   0.576081 |
| k-d_tree_pandas      |     7.62606  |       0.40436  |   0.593481 |
| k-d_tree_sklearn     |     3.05454  |       1.01467  |   1.04808  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633496 |       0.420859 |   0.412268 |
| k-d_tree_polars      |     0.606199 |       0.420765 |   0.41838  |
| barab-szabi-1        |     0.609503 |       0.426154 |   0.420516 |
| Bori_Aron_solution-1 |     0.595241 |       0.575274 |   0.566476 |
| k-d_tree_pandas      |     0.600985 |       0.398573 |   0.597169 |
| k-d_tree_sklearn     |     0.608474 |       0.995568 |   1.0465   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598938 |       0.422271 |   0.426755 |
| barab-szabi-1        |     0.601248 |       0.436866 |   0.443792 |
| k-d_tree_polars      |     0.591039 |       0.436538 |   0.484511 |
| Bori_Aron_solution-1 |     0.586549 |       0.590856 |   0.553712 |
| k-d_tree_pandas      |     0.595224 |       0.418616 |   0.621107 |
| k-d_tree_sklearn     |     0.605912 |       1.02135  |   1.11792  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.595084 |       0.495096 |   0.457394 |
| k-d_tree_polars      |     0.589097 |       0.539424 |   0.535998 |
| barab-szabi-1        |     0.613395 |       0.540242 |   0.546996 |
| Bori_Aron_solution-1 |     0.586777 |       0.756402 |   0.561084 |
| k-d_tree_pandas      |     0.598607 |       0.484267 |   0.730822 |
| k-d_tree_sklearn     |     0.606148 |       1.23675  |   1.12772  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603058 |       0.753293 |   0.523382 |
| Bori_Aron_solution-1 |     0.601292 |       1.42937  |   0.605048 |
| k-d_tree_polars      |     0.606208 |       0.883085 |   0.896513 |
| barab-szabi-1        |     0.61336  |       0.883775 |   0.950274 |
| k-d_tree_pandas      |     0.594117 |       0.760873 |   1.2041   |
| k-d_tree_sklearn     |     0.599786 |       2.13276  |   1.28096  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625588 |        5.37688 |   0.782031 |
| Bori_Aron_solution-1 |     0.618645 |       10.693   |   0.91371  |
| k-d_tree_sklearn     |     0.598371 |       16.1728  |   1.31282  |
| barab-szabi-1        |     0.600474 |        4.96076 |   6.68696  |
| k-d_tree_polars      |     0.600876 |        4.99198 |   6.98961  |
| k-d_tree_pandas      |     0.596975 |        3.84854 |   7.16449  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.795091 |        74.2765 |    3.79398 |
| k-d_tree_sklearn     |     0.659655 |       231.211  |    4.17758 |
| Bori_Aron_solution-1 |     0.585241 |       154.327  |   16.309   |