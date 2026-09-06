# 2026-09-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.13238  |       1e-06    |   0.413709 |
| barab-szabi-2        |     0.473022 |       0.436693 |   0.436678 |
| Bori_Aron_solution-1 |     0.465954 |       0.565891 |   0.542845 |
| k-d_tree_polars      |     0.459805 |       0.418149 |   0.545283 |
| k-d_tree_pandas      |     0.461419 |       0.392892 |   0.546716 |
| barab-szabi-1        |     9.43221  |       0.493595 |   0.592175 |
| k-d_tree_sklearn     |     3.0803   |       1.21399  |   1.05972  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.470318 |       0.43398  |   0.444337 |
| barab-szabi-2        |     0.47944  |       0.446337 |   0.449919 |
| k-d_tree_polars      |     0.474168 |       0.428564 |   0.450559 |
| Bori_Aron_solution-1 |     0.464862 |       0.553903 |   0.541585 |
| k-d_tree_pandas      |     0.465252 |       0.39895  |   0.555555 |
| k-d_tree_sklearn     |     0.476965 |       1.03507  |   1.10859  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.4749   |       0.454263 |   0.449682 |
| k-d_tree_polars      |     0.486256 |       0.457423 |   0.473223 |
| barab-szabi-1        |     0.481563 |       0.46047  |   0.477098 |
| Bori_Aron_solution-1 |     0.469051 |       0.599128 |   0.556645 |
| k-d_tree_pandas      |     0.476047 |       0.420283 |   0.599903 |
| k-d_tree_sklearn     |     0.479686 |       1.07571  |   1.10604  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466724 |       0.51582  |   0.483476 |
| Bori_Aron_solution-1 |     0.461229 |       0.78314  |   0.562193 |
| k-d_tree_polars      |     0.474829 |       0.600583 |   0.58316  |
| barab-szabi-1        |     0.507913 |       0.611135 |   0.624868 |
| k-d_tree_pandas      |     0.507063 |       0.510216 |   0.715684 |
| k-d_tree_sklearn     |     0.516635 |       1.27094  |   1.10726  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476617 |       0.780287 |   0.547308 |
| Bori_Aron_solution-1 |     0.46416  |       1.49214  |   0.598241 |
| k-d_tree_polars      |     0.475912 |       0.914321 |   0.957866 |
| barab-szabi-1        |     0.490609 |       0.96456  |   1.00371  |
| k-d_tree_sklearn     |     0.516174 |       2.16202  |   1.17637  |
| k-d_tree_pandas      |     0.467369 |       0.786501 |   1.18395  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475388 |        5.72606 |   0.77482  |
| Bori_Aron_solution-1 |     0.473508 |       11.5928  |   0.838961 |
| k-d_tree_sklearn     |     0.497767 |       17.2937  |   1.34925  |
| k-d_tree_polars      |     0.475044 |        5.22845 |   7.79796  |
| barab-szabi-1        |     0.487923 |        5.12718 |   7.88777  |
| k-d_tree_pandas      |     0.483595 |        4.08477 |   8.12873  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559163 |        82.2457 |    2.73155 |
| k-d_tree_sklearn     |     0.734585 |       270.89   |    3.47142 |
| Bori_Aron_solution-1 |     0.489253 |       162.645  |   14.9885  |