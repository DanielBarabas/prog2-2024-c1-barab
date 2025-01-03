# 2025-01-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.49287  |       1e-06    |   0.350492 |
| k-d_tree_polars      |     0.613392 |       0.397635 |   0.396245 |
| barab-szabi-1        |     0.618702 |       0.400588 |   0.397125 |
| barab-szabi-2        |     0.616159 |       0.42171  |   0.407045 |
| k-d_tree_pandas      |     0.607782 |       0.37559  |   0.530444 |
| Bori_Aron_solution-1 |     0.611917 |       0.530032 |   0.531601 |
| k-d_tree_sklearn     |    10.5702   |       1.12609  |   1.00763  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.622203 |       0.404188 |   0.398947 |
| barab-szabi-2        |     0.60599  |       0.399775 |   0.399454 |
| k-d_tree_polars      |     0.609803 |       0.40158  |   0.40151  |
| k-d_tree_pandas      |     0.612473 |       0.380296 |   0.541271 |
| Bori_Aron_solution-1 |     0.606504 |       0.535202 |   0.568496 |
| k-d_tree_sklearn     |     0.634804 |       0.940132 |   1.0122   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608677 |       0.413041 |   0.406179 |
| k-d_tree_polars      |     0.610274 |       0.427814 |   0.425532 |
| barab-szabi-1        |     0.622213 |       0.436429 |   0.446939 |
| Bori_Aron_solution-1 |     0.608735 |       0.570146 |   0.527113 |
| k-d_tree_pandas      |     0.611634 |       0.398634 |   0.579555 |
| k-d_tree_sklearn     |     0.615265 |       0.991373 |   1.04878  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608516 |       0.475827 |   0.436026 |
| k-d_tree_polars      |     0.61756  |       0.54984  |   0.527764 |
| Bori_Aron_solution-1 |     0.60427  |       0.74823  |   0.544273 |
| barab-szabi-1        |     0.608095 |       0.542649 |   0.548843 |
| k-d_tree_pandas      |     0.610589 |       0.486334 |   0.712586 |
| k-d_tree_sklearn     |     0.616308 |       1.20711  |   1.08785  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60696  |       0.724566 |   0.473032 |
| Bori_Aron_solution-1 |     0.618074 |       1.40139  |   0.568606 |
| k-d_tree_polars      |     0.606022 |       0.865873 |   0.865073 |
| barab-szabi-1        |     0.606278 |       0.864548 |   0.906756 |
| k-d_tree_pandas      |     0.606697 |       0.735471 |   1.14459  |
| k-d_tree_sklearn     |     0.618708 |       2.01995  |   1.17438  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616828 |        5.5469  |   0.755507 |
| Bori_Aron_solution-1 |     0.602561 |       10.9271  |   0.835854 |
| k-d_tree_sklearn     |     0.609991 |       16.6304  |   1.2933   |
| barab-szabi-1        |     0.607321 |        4.90368 |   6.69049  |
| k-d_tree_polars      |     0.610702 |        4.91249 |   6.8213   |
| k-d_tree_pandas      |     0.629884 |        3.90666 |   7.14861  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.628899 |        80.7683 |    3.56451 |
| k-d_tree_sklearn     |     0.610112 |       266.637  |    4.28795 |
| Bori_Aron_solution-1 |     0.630532 |       148.588  |   17.723   |