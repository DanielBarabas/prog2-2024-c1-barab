# 2026-06-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.36838  |       0.335002 |   0.350273 |
| k-d_tree_polars      |     0.380071 |       0.348932 |   0.373429 |
| barab-szabi-2        |     8.19444  |       0.81589  |   0.378072 |
| k-d_tree_pandas      |     0.361702 |       0.302444 |   0.432554 |
| Bori_Aron_solution-1 |     0.35406  |       0.44104  |   0.454912 |
| solution-1           |     6.45169  |       1e-06    |   0.468671 |
| k-d_tree_sklearn     |     2.70408  |       1.05494  |   0.83165  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.373547 |       0.39047  |   0.356662 |
| k-d_tree_polars      |     0.364944 |       0.346705 |   0.359747 |
| barab-szabi-2        |     0.361723 |       0.339374 |   0.36971  |
| Bori_Aron_solution-1 |     0.358046 |       0.441123 |   0.427573 |
| k-d_tree_pandas      |     0.362118 |       0.311531 |   0.492326 |
| k-d_tree_sklearn     |     0.366346 |       0.765335 |   0.847289 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.420429 |       0.350055 |   0.358589 |
| barab-szabi-1        |     0.360929 |       0.343507 |   0.366274 |
| k-d_tree_polars      |     0.364383 |       0.357958 |   0.38508  |
| Bori_Aron_solution-1 |     0.35888  |       0.475534 |   0.434215 |
| k-d_tree_pandas      |     0.361125 |       0.3243   |   0.473546 |
| k-d_tree_sklearn     |     0.366852 |       0.818274 |   0.86147  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.358838 |       0.408978 |   0.387347 |
| Bori_Aron_solution-1 |     0.378015 |       0.623151 |   0.444381 |
| k-d_tree_polars      |     0.362423 |       0.467569 |   0.455314 |
| k-d_tree_pandas      |     0.374008 |       0.400987 |   0.571587 |
| barab-szabi-1        |     0.366121 |       0.469342 |   0.587684 |
| k-d_tree_sklearn     |     0.36689  |       1.0213   |   0.909417 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.367102 |       0.602232 |   0.411753 |
| Bori_Aron_solution-1 |     0.358735 |       1.19987  |   0.469812 |
| k-d_tree_polars      |     0.370069 |       0.80036  |   0.753216 |
| barab-szabi-1        |     0.365955 |       0.772145 |   0.787441 |
| k-d_tree_pandas      |     0.360553 |       0.618661 |   0.924719 |
| k-d_tree_sklearn     |     0.369478 |       1.78877  |   0.9408   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.366304 |        4.55159 |   0.614171 |
| Bori_Aron_solution-1 |     0.362337 |        9.20168 |   0.640708 |
| k-d_tree_sklearn     |     0.365004 |       14.6039  |   0.995723 |
| barab-szabi-1        |     0.362436 |        4.77581 |   6.00501  |
| k-d_tree_polars      |     0.358665 |        4.82147 |   6.02462  |
| k-d_tree_pandas      |     0.37032  |        3.30713 |   6.20444  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364393 |        68.7244 |    2.52406 |
| k-d_tree_sklearn     |     0.995192 |       229.109  |    4.00389 |
| Bori_Aron_solution-1 |     0.36221  |       151.257  |   15.8455  |