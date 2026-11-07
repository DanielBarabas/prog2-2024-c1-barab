# 2026-11-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.346437 |       0.335665 |   0.326645 |
| barab-szabi-1        |     0.345284 |       0.346581 |   0.362507 |
| k-d_tree_polars      |     7.66004  |       0.346969 |   0.373361 |
| k-d_tree_pandas      |     0.357364 |       0.299575 |   0.427964 |
| Bori_Aron_solution-1 |     0.334828 |       0.444351 |   0.443613 |
| solution-1           |     6.69745  |       1e-06    |   0.453437 |
| k-d_tree_sklearn     |     2.39962  |       0.84477  |   0.871891 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.356183 |       0.349291 |   0.341311 |
| k-d_tree_polars      |     0.352987 |       0.331544 |   0.351203 |
| barab-szabi-1        |     0.35228  |       0.340284 |   0.356394 |
| Bori_Aron_solution-1 |     0.350252 |       0.438718 |   0.44218  |
| k-d_tree_pandas      |     0.357457 |       0.328158 |   0.451312 |
| k-d_tree_sklearn     |     0.355247 |       0.815097 |   0.842734 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.352518 |       0.357093 |   0.339473 |
| barab-szabi-1        |     0.356105 |       0.361608 |   0.372395 |
| k-d_tree_polars      |     0.353204 |       0.368505 |   0.385059 |
| Bori_Aron_solution-1 |     0.350126 |       0.470845 |   0.437973 |
| k-d_tree_pandas      |     0.35882  |       0.329786 |   0.466492 |
| k-d_tree_sklearn     |     0.355959 |       0.830231 |   0.874896 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.35134  |       0.439128 |   0.373816 |
| k-d_tree_polars      |     0.347565 |       0.455911 |   0.450879 |
| barab-szabi-1        |     0.351562 |       0.457764 |   0.463354 |
| Bori_Aron_solution-1 |     0.341012 |       0.634288 |   0.465361 |
| k-d_tree_pandas      |     0.3562   |       0.397155 |   0.569228 |
| k-d_tree_sklearn     |     0.362756 |       1.00958  |   0.893609 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.357847 |       0.651492 |   0.455084 |
| Bori_Aron_solution-1 |     0.342982 |       1.22932  |   0.497453 |
| k-d_tree_polars      |     0.345589 |       0.701517 |   0.788113 |
| barab-szabi-1        |     0.348306 |       0.711828 |   0.810978 |
| k-d_tree_pandas      |     0.357311 |       0.61837  |   0.944196 |
| k-d_tree_sklearn     |     0.357023 |       1.67939  |   0.956769 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.342179 |        4.5796  |   0.713497 |
| Bori_Aron_solution-1 |     0.354411 |        9.10416 |   0.885592 |
| k-d_tree_sklearn     |     0.353482 |       13.9877  |   1.04582  |
| k-d_tree_polars      |     0.352075 |        5.07001 |   6.05442  |
| barab-szabi-1        |     0.34893  |        4.55403 |   6.12462  |
| k-d_tree_pandas      |     0.354682 |        3.17223 |   6.28771  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.638515 |       215.033  |    3.32331 |
| barab-szabi-2        |     0.595288 |        70.2043 |    3.54466 |
| Bori_Aron_solution-1 |     0.352497 |       147.064  |   25.0835  |