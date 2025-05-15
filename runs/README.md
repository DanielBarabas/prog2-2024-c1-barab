# 2025-05-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.50916  |       1e-06    |   0.394798 |
| barab-szabi-1        |     0.517133 |       0.421038 |   0.424936 |
| barab-szabi-2        |     0.517461 |       0.417211 |   0.426517 |
| k-d_tree_polars      |     7.86336  |       0.459305 |   0.485493 |
| Bori_Aron_solution-1 |     0.512012 |       0.554938 |   0.553812 |
| k-d_tree_pandas      |     0.517879 |       0.399318 |   0.568339 |
| k-d_tree_sklearn     |     3.03941  |       1.10847  |   1.09883  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535859 |       0.426309 |   0.424632 |
| k-d_tree_polars      |     0.540155 |       0.425822 |   0.43453  |
| barab-szabi-1        |     0.562443 |       0.431724 |   0.442465 |
| Bori_Aron_solution-1 |     0.533069 |       0.580198 |   0.570999 |
| k-d_tree_pandas      |     0.552709 |       0.432817 |   0.61375  |
| k-d_tree_sklearn     |     0.55302  |       1.01683  |   1.13915  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546236 |       0.457289 |   0.450152 |
| barab-szabi-1        |     0.560247 |       0.465569 |   0.472321 |
| k-d_tree_polars      |     0.546012 |       0.471121 |   0.474369 |
| Bori_Aron_solution-1 |     0.543113 |       0.613806 |   0.595932 |
| k-d_tree_pandas      |     0.567895 |       0.435941 |   0.650528 |
| k-d_tree_sklearn     |     0.542537 |       1.10345  |   1.14641  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544006 |       0.49954  |   0.4848   |
| k-d_tree_polars      |     0.545576 |       0.554241 |   0.558214 |
| barab-szabi-1        |     0.54775  |       0.575565 |   0.579281 |
| Bori_Aron_solution-1 |     0.551047 |       0.791228 |   0.596946 |
| k-d_tree_pandas      |     0.547494 |       0.532784 |   0.791339 |
| k-d_tree_sklearn     |     0.569627 |       1.31509  |   1.1929   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560659 |       0.755179 |   0.571902 |
| Bori_Aron_solution-1 |     0.55296  |       1.44675  |   0.638971 |
| k-d_tree_polars      |     0.547584 |       0.915621 |   0.944259 |
| barab-szabi-1        |     0.548671 |       0.914262 |   1.01369  |
| k-d_tree_pandas      |     0.544972 |       0.801763 |   1.26445  |
| k-d_tree_sklearn     |     0.545871 |       2.16727  |   1.3045   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537281 |        6.00256 |   0.823758 |
| Bori_Aron_solution-1 |     0.543991 |       11.3554  |   0.935939 |
| k-d_tree_sklearn     |     0.546183 |       18.7898  |   1.38469  |
| barab-szabi-1        |     0.556969 |        5.10652 |   7.0598   |
| k-d_tree_polars      |     0.559737 |        5.09727 |   7.1724   |
| k-d_tree_pandas      |     0.540615 |        4.10266 |   7.44714  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54844  |        79.2091 |    2.97293 |
| k-d_tree_sklearn     |     0.750781 |       243.497  |    4.41112 |
| Bori_Aron_solution-1 |     0.532753 |       143.722  |   18.3949  |