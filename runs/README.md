# 2026-04-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459295 |       0.429043 |   0.423352 |
| barab-szabi-1        |     0.458116 |       0.403817 |   0.42713  |
| k-d_tree_polars      |     0.45789  |       0.405142 |   0.428823 |
| k-d_tree_pandas      |     0.455103 |       0.379381 |   0.535739 |
| Bori_Aron_solution-1 |     0.448684 |       0.537709 |   0.582693 |
| solution-1           |     8.07885  |       1e-06    |   0.799621 |
| k-d_tree_sklearn     |    11.3639   |       1.92223  |   1.0734   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452416 |       0.427541 |   0.423604 |
| k-d_tree_polars      |     0.453371 |       0.423541 |   0.430717 |
| barab-szabi-1        |     0.454715 |       0.411337 |   0.431406 |
| Bori_Aron_solution-1 |     0.443821 |       0.548472 |   0.541258 |
| k-d_tree_pandas      |     0.453395 |       0.387135 |   0.546309 |
| k-d_tree_sklearn     |     0.466084 |       0.972831 |   1.04817  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458986 |       0.434339 |   0.435022 |
| k-d_tree_polars      |     0.452105 |       0.452827 |   0.456438 |
| barab-szabi-1        |     0.457279 |       0.436788 |   0.471261 |
| Bori_Aron_solution-1 |     0.453086 |       0.585047 |   0.551328 |
| k-d_tree_pandas      |     0.458692 |       0.409365 |   0.580065 |
| k-d_tree_sklearn     |     0.46786  |       1.01253  |   1.08416  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456062 |       0.494687 |   0.463712 |
| Bori_Aron_solution-1 |     0.447408 |       0.773785 |   0.548445 |
| k-d_tree_polars      |     0.453314 |       0.561298 |   0.552048 |
| barab-szabi-1        |     0.45701  |       0.555948 |   0.558048 |
| k-d_tree_pandas      |     0.458039 |       0.494346 |   0.715472 |
| k-d_tree_sklearn     |     0.460783 |       1.252    |   1.13317  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458637 |       0.750208 |   0.506871 |
| Bori_Aron_solution-1 |     0.448636 |       1.48692  |   0.580895 |
| k-d_tree_polars      |     0.45923  |       0.912251 |   0.951254 |
| barab-szabi-1        |     0.455469 |       0.889196 |   0.974636 |
| k-d_tree_sklearn     |     0.455831 |       2.12696  |   1.1402   |
| k-d_tree_pandas      |     0.46285  |       0.781354 |   1.17127  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.450683 |        5.39376 |    0.71542 |
| Bori_Aron_solution-1 |     0.445268 |       11.2846  |    0.80343 |
| k-d_tree_sklearn     |     0.457193 |       17.1457  |    1.23672 |
| k-d_tree_polars      |     0.455618 |        5.21735 |    7.22128 |
| barab-szabi-1        |     0.45126  |        5.14509 |    7.29486 |
| k-d_tree_pandas      |     0.454938 |        4.23991 |    7.64383 |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.67223  |        75.7116 |    2.52923 |
| k-d_tree_sklearn     |     0.459154 |       256.277  |    3.29262 |
| Bori_Aron_solution-1 |     0.456032 |       151.791  |   17.9015  |