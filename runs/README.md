# 2025-11-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549896 |       0.524708 |   0.444447 |
| k-d_tree_polars      |     0.562754 |       0.432166 |   0.450043 |
| barab-szabi-1        |     0.542912 |       0.429199 |   0.451291 |
| solution-1           |     7.69875  |       1e-06    |   0.462909 |
| Bori_Aron_solution-1 |     0.532974 |       0.597134 |   0.58647  |
| k-d_tree_pandas      |     8.46403  |       0.439804 |   0.671381 |
| k-d_tree_sklearn     |     3.19913  |       1.13889  |   1.1059   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560616 |       0.445607 |   0.453799 |
| barab-szabi-1        |     0.553392 |       0.426532 |   0.454437 |
| k-d_tree_polars      |     0.554228 |       0.435884 |   0.45535  |
| Bori_Aron_solution-1 |     0.555764 |       0.592304 |   0.566192 |
| k-d_tree_pandas      |     0.559126 |       0.419519 |   0.60374  |
| k-d_tree_sklearn     |     0.546104 |       0.997361 |   1.11907  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55794  |       0.466295 |   0.467087 |
| k-d_tree_polars      |     0.553622 |       0.446921 |   0.471353 |
| barab-szabi-1        |     0.554046 |       0.457846 |   0.486808 |
| Bori_Aron_solution-1 |     0.534928 |       0.628857 |   0.561773 |
| k-d_tree_pandas      |     0.561993 |       0.427537 |   0.64438  |
| k-d_tree_sklearn     |     0.547903 |       1.07645  |   1.13932  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537545 |       0.512022 |   0.481143 |
| k-d_tree_polars      |     0.546553 |       0.574772 |   0.564048 |
| Bori_Aron_solution-1 |     0.539401 |       0.802508 |   0.580892 |
| barab-szabi-1        |     0.544577 |       0.575198 |   0.592358 |
| k-d_tree_pandas      |     0.5508   |       0.518746 |   0.751538 |
| k-d_tree_sklearn     |     0.546319 |       1.29457  |   1.1761   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560974 |       0.791843 |   0.581098 |
| Bori_Aron_solution-1 |     0.537471 |       1.49569  |   0.604665 |
| k-d_tree_polars      |     0.541403 |       0.937793 |   0.950156 |
| barab-szabi-1        |     0.542995 |       0.959128 |   1.00438  |
| k-d_tree_pandas      |     0.537658 |       0.819681 |   1.25159  |
| k-d_tree_sklearn     |     0.557056 |       2.21114  |   1.25771  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541499 |        5.40526 |   0.766773 |
| Bori_Aron_solution-1 |     0.55104  |       11.4427  |   0.86787  |
| k-d_tree_sklearn     |     0.545385 |       17.289   |   1.41765  |
| barab-szabi-1        |     0.567232 |        5.42374 |   6.73677  |
| k-d_tree_polars      |     0.547495 |        5.4769  |   6.79007  |
| k-d_tree_pandas      |     0.548081 |        4.46646 |   7.16157  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557703 |        82.1959 |    2.83533 |
| k-d_tree_sklearn     |     0.551252 |       250.803  |    4.2145  |
| Bori_Aron_solution-1 |     0.677975 |       159.821  |   14.7437  |