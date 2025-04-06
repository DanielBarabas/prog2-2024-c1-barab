# 2025-04-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |      1.04314 |       0.411391 |   0.412033 |
| barab-szabi-2        |      1.0402  |       0.421196 |   0.445297 |
| barab-szabi-1        |      1.04802 |       0.442246 |   0.471078 |
| Bori_Aron_solution-1 |      1.03312 |       0.548129 |   0.578443 |
| solution-1           |      7.80493 |       1e-06    |   0.746716 |
| k-d_tree_pandas      |      8.36737 |       0.452744 |   0.909726 |
| k-d_tree_sklearn     |      3.48606 |       1.26425  |   1.04271  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.576734 |       0.427046 |   0.416065 |
| k-d_tree_polars      |     0.563921 |       0.409156 |   0.418314 |
| barab-szabi-2        |     0.570037 |       0.4219   |   0.419326 |
| Bori_Aron_solution-1 |     0.568863 |       0.558803 |   0.55994  |
| k-d_tree_pandas      |     0.721964 |       0.390006 |   0.568053 |
| k-d_tree_sklearn     |     0.576283 |       0.979417 |   1.06715  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574886 |       0.430315 |   0.429323 |
| k-d_tree_polars      |     0.59292  |       0.448432 |   0.445006 |
| barab-szabi-1        |     0.567129 |       0.491082 |   0.451213 |
| Bori_Aron_solution-1 |     0.567394 |       0.600372 |   0.56041  |
| k-d_tree_pandas      |     0.57184  |       0.406273 |   0.598792 |
| k-d_tree_sklearn     |     0.57315  |       1.02644  |   1.0593   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575543 |       0.493747 |   0.455537 |
| barab-szabi-1        |     0.587434 |       0.536372 |   0.551031 |
| k-d_tree_polars      |     0.576612 |       0.568734 |   0.561584 |
| Bori_Aron_solution-1 |     0.570704 |       0.762981 |   0.579335 |
| k-d_tree_pandas      |     0.573374 |       0.487545 |   0.748005 |
| k-d_tree_sklearn     |     0.577914 |       1.24455  |   1.13715  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564371 |       0.722908 |   0.479812 |
| Bori_Aron_solution-1 |     0.554374 |       1.40616  |   0.595018 |
| k-d_tree_polars      |     0.561354 |       0.86473  |   0.882075 |
| barab-szabi-1        |     0.569904 |       0.862677 |   0.91774  |
| k-d_tree_pandas      |     0.567517 |       0.743236 |   1.18882  |
| k-d_tree_sklearn     |     0.563846 |       2.05348  |   1.19278  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57104  |        5.26567 |   0.737547 |
| Bori_Aron_solution-1 |     0.596049 |       10.515   |   0.866406 |
| k-d_tree_sklearn     |     0.564392 |       16.5793  |   1.31449  |
| barab-szabi-1        |     0.559397 |        4.93605 |   6.50559  |
| k-d_tree_polars      |     0.560896 |        4.93253 |   6.64842  |
| k-d_tree_pandas      |     0.564709 |        3.8064  |   7.0572   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.918965 |        72.7966 |    2.75959 |
| k-d_tree_sklearn     |     0.700927 |       227.541  |    4.14467 |
| Bori_Aron_solution-1 |     0.559834 |       166.683  |   14.5058  |