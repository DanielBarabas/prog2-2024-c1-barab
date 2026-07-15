# 2026-07-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.486654 |       0.428564 |   0.464262 |
| barab-szabi-2        |     0.495619 |       0.456806 |   0.465338 |
| solution-1           |     8.68989  |       1e-06    |   0.496949 |
| k-d_tree_pandas      |     0.493388 |       0.394604 |   0.566498 |
| Bori_Aron_solution-1 |     0.478336 |       0.58698  |   0.582843 |
| barab-szabi-1        |     8.3644   |       0.537195 |   0.703825 |
| k-d_tree_sklearn     |     4.02935  |       1.30735  |   1.18473  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.478317 |       0.424433 |   0.463546 |
| barab-szabi-2        |     0.482512 |       0.455266 |   0.464404 |
| k-d_tree_polars      |     0.488589 |       0.43627  |   0.480994 |
| Bori_Aron_solution-1 |     0.47386  |       0.581821 |   0.55727  |
| k-d_tree_pandas      |     0.485984 |       0.404002 |   0.579221 |
| k-d_tree_sklearn     |     0.482117 |       1.03091  |   1.10356  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491085 |       0.468046 |   0.463075 |
| k-d_tree_polars      |     0.478559 |       0.462196 |   0.486724 |
| barab-szabi-1        |     0.502389 |       0.470369 |   0.502466 |
| Bori_Aron_solution-1 |     0.479927 |       0.608701 |   0.562566 |
| k-d_tree_pandas      |     0.494763 |       0.428736 |   0.605977 |
| k-d_tree_sklearn     |     0.485757 |       1.06434  |   1.13552  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.493766 |       0.531859 |   0.506561 |
| Bori_Aron_solution-1 |     0.481746 |       0.787156 |   0.566295 |
| k-d_tree_polars      |     0.493829 |       0.59993  |   0.593956 |
| barab-szabi-1        |     0.480974 |       0.585883 |   0.606529 |
| k-d_tree_pandas      |     0.492951 |       0.532062 |   0.783456 |
| k-d_tree_sklearn     |     0.494641 |       1.32666  |   1.23098  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494901 |       0.777099 |   0.545561 |
| Bori_Aron_solution-1 |     0.483607 |       1.49116  |   0.607367 |
| k-d_tree_polars      |     0.489427 |       0.947021 |   0.958649 |
| barab-szabi-1        |     0.49387  |       0.947901 |   1.01458  |
| k-d_tree_pandas      |     0.485351 |       0.819027 |   1.2242   |
| k-d_tree_sklearn     |     0.484862 |       2.21967  |   1.29964  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488036 |        5.38809 |   0.792094 |
| Bori_Aron_solution-1 |     0.483543 |       11.0831  |   0.828592 |
| k-d_tree_sklearn     |     0.486598 |       17.7368  |   1.37879  |
| k-d_tree_polars      |     0.48667  |        5.3697  |   6.93212  |
| barab-szabi-1        |     0.492751 |        5.40243 |   7.10224  |
| k-d_tree_pandas      |     0.483765 |        4.33798 |   7.43407  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486227 |        74.1535 |    2.98187 |
| k-d_tree_sklearn     |     0.72433  |       243.292  |    4.08364 |
| Bori_Aron_solution-1 |     0.481391 |       160.258  |   17.1113  |