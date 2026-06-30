# 2026-06-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.96928  |       1e-06    |   0.359283 |
| barab-szabi-2        |     9.1941   |       0.500062 |   0.439051 |
| barab-szabi-1        |     0.45826  |       0.396546 |   0.439341 |
| k-d_tree_polars      |     0.462051 |       0.415325 |   0.442028 |
| Bori_Aron_solution-1 |     0.452575 |       0.542406 |   0.539888 |
| k-d_tree_pandas      |     0.486511 |       0.384577 |   0.550036 |
| k-d_tree_sklearn     |     2.8158   |       0.995181 |   1.12861  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471294 |       0.440285 |   0.43815  |
| barab-szabi-1        |     0.466626 |       0.407851 |   0.441175 |
| k-d_tree_polars      |     0.463957 |       0.409236 |   0.452848 |
| Bori_Aron_solution-1 |     0.46657  |       0.55873  |   0.54003  |
| k-d_tree_pandas      |     0.466765 |       0.385777 |   0.550297 |
| k-d_tree_sklearn     |     0.473289 |       0.961465 |   1.056    |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.472912 |       0.439331 |   0.472216 |
| barab-szabi-2        |     0.464749 |       0.462877 |   0.473864 |
| barab-szabi-1        |     0.489416 |       0.448259 |   0.487421 |
| Bori_Aron_solution-1 |     0.486336 |       0.617992 |   0.555185 |
| k-d_tree_pandas      |     0.466234 |       0.401831 |   0.602754 |
| k-d_tree_sklearn     |     0.470398 |       1.01669  |   1.1407   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463906 |       0.522481 |   0.499228 |
| Bori_Aron_solution-1 |     0.467808 |       0.772957 |   0.557678 |
| k-d_tree_polars      |     0.482954 |       0.558611 |   0.572865 |
| barab-szabi-1        |     0.480027 |       0.564328 |   0.58158  |
| k-d_tree_pandas      |     0.476026 |       0.50266  |   0.739292 |
| k-d_tree_sklearn     |     0.482409 |       1.26348  |   1.15529  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470575 |       0.73986  |   0.511231 |
| Bori_Aron_solution-1 |     0.462233 |       1.41547  |   0.575902 |
| k-d_tree_polars      |     0.46375  |       0.914123 |   0.915573 |
| barab-szabi-1        |     0.471133 |       0.916998 |   0.951985 |
| k-d_tree_pandas      |     0.46176  |       0.795143 |   1.15946  |
| k-d_tree_sklearn     |     0.469549 |       2.08912  |   1.20426  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465507 |        5.19966 |   0.756645 |
| Bori_Aron_solution-1 |     0.465943 |       11.2492  |   0.83094  |
| k-d_tree_sklearn     |     0.476624 |       16.8611  |   1.32119  |
| k-d_tree_polars      |     0.484903 |        5.40216 |   6.68538  |
| barab-szabi-1        |     0.467519 |        5.3211  |   6.82933  |
| k-d_tree_pandas      |     0.472946 |        4.32209 |   7.18315  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463671 |        69.8081 |    2.65372 |
| k-d_tree_sklearn     |     0.658113 |       229.242  |    3.97392 |
| Bori_Aron_solution-1 |     0.459472 |       152.37   |   15.4242  |