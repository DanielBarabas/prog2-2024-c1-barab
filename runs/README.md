# 2026-05-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.481391 |       0.412504 |   0.435746 |
| k-d_tree_polars      |     0.476277 |       0.423252 |   0.440423 |
| barab-szabi-2        |     0.502041 |       0.52705  |   0.447268 |
| solution-1           |     7.91266  |       1e-06    |   0.534639 |
| k-d_tree_pandas      |     0.485622 |       0.394819 |   0.570165 |
| Bori_Aron_solution-1 |     0.466339 |       0.574815 |   0.58105  |
| k-d_tree_sklearn     |    10.5952   |       1.92093  |   1.09446  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.466887 |       0.412627 |   0.438281 |
| barab-szabi-2        |     0.493318 |       0.450503 |   0.465451 |
| k-d_tree_polars      |     0.474961 |       0.441131 |   0.475494 |
| k-d_tree_pandas      |     0.470731 |       0.400885 |   0.569326 |
| Bori_Aron_solution-1 |     0.467815 |       0.585647 |   0.590449 |
| k-d_tree_sklearn     |     0.47313  |       0.993953 |   1.10403  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474488 |       0.482636 |   0.45471  |
| barab-szabi-1        |     0.469812 |       0.442241 |   0.46925  |
| k-d_tree_polars      |     0.469104 |       0.463656 |   0.49073  |
| Bori_Aron_solution-1 |     0.457134 |       0.610099 |   0.565578 |
| k-d_tree_pandas      |     0.46536  |       0.425228 |   0.596643 |
| k-d_tree_sklearn     |     0.468833 |       1.04144  |   1.13792  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497708 |       0.511595 |   0.487444 |
| Bori_Aron_solution-1 |     0.465461 |       0.782291 |   0.567053 |
| k-d_tree_polars      |     0.473888 |       0.583444 |   0.575556 |
| barab-szabi-1        |     0.469718 |       0.576252 |   0.592505 |
| k-d_tree_pandas      |     0.46937  |       0.501183 |   0.738088 |
| k-d_tree_sklearn     |     0.484266 |       1.31052  |   1.18159  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476918 |       0.72556  |   0.503281 |
| Bori_Aron_solution-1 |     0.459005 |       1.4672   |   0.598133 |
| k-d_tree_polars      |     0.478369 |       0.937145 |   0.954772 |
| barab-szabi-1        |     0.456743 |       0.941359 |   0.991649 |
| k-d_tree_pandas      |     0.464987 |       0.81919  |   1.1761   |
| k-d_tree_sklearn     |     0.477472 |       2.22202  |   1.24394  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483144 |        5.18453 |   0.7466   |
| Bori_Aron_solution-1 |     0.451547 |       11.0383  |   0.808349 |
| k-d_tree_sklearn     |     0.470243 |       16.3836  |   1.28856  |
| barab-szabi-1        |     0.466302 |        5.31311 |   6.49243  |
| k-d_tree_polars      |     0.473994 |        5.4778  |   6.73913  |
| k-d_tree_pandas      |     0.465311 |        4.49545 |   7.00853  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.820491 |        72.2725 |    2.65293 |
| k-d_tree_sklearn     |     0.475809 |       239.177  |    3.71791 |
| Bori_Aron_solution-1 |     0.460949 |       155.422  |   18.0243  |