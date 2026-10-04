# 2026-10-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465649 |       0.455341 |   0.450053 |
| k-d_tree_polars      |     0.467193 |       0.428655 |   0.458275 |
| solution-1           |     8.44589  |       1e-06    |   0.530953 |
| Bori_Aron_solution-1 |     0.468777 |       0.574602 |   0.567193 |
| k-d_tree_pandas      |     0.464351 |       0.390787 |   0.591286 |
| barab-szabi-1        |     9.27844  |       0.486219 |   0.819916 |
| k-d_tree_sklearn     |     3.4462   |       1.27159  |   1.14296  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.495429 |       0.437975 |   0.471843 |
| barab-szabi-1        |     0.491602 |       0.448523 |   0.475539 |
| barab-szabi-2        |     0.486644 |       0.471814 |   0.477111 |
| Bori_Aron_solution-1 |     0.473654 |       0.564325 |   0.563325 |
| k-d_tree_pandas      |     0.483291 |       0.408223 |   0.568195 |
| k-d_tree_sklearn     |     0.501218 |       1.12199  |   1.11544  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.4769   |       0.467028 |   0.459136 |
| k-d_tree_polars      |     0.477906 |       0.450327 |   0.481021 |
| barab-szabi-1        |     0.485205 |       0.474487 |   0.48772  |
| Bori_Aron_solution-1 |     0.473252 |       0.602999 |   0.560188 |
| k-d_tree_pandas      |     0.488036 |       0.437362 |   0.614735 |
| k-d_tree_sklearn     |     0.477739 |       1.08008  |   1.11901  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484979 |       0.527212 |   0.500337 |
| k-d_tree_polars      |     0.488957 |       0.583393 |   0.581254 |
| Bori_Aron_solution-1 |     0.477682 |       0.812945 |   0.586684 |
| barab-szabi-1        |     0.480195 |       0.586859 |   0.606729 |
| k-d_tree_pandas      |     0.48361  |       0.514877 |   0.759102 |
| k-d_tree_sklearn     |     0.496083 |       1.30749  |   1.14301  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474069 |       0.749241 |   0.534442 |
| Bori_Aron_solution-1 |     0.470495 |       1.43766  |   0.589202 |
| k-d_tree_polars      |     0.480918 |       0.930973 |   0.939264 |
| barab-szabi-1        |     0.483511 |       0.952436 |   1.00708  |
| k-d_tree_pandas      |     0.487844 |       0.803104 |   1.18973  |
| k-d_tree_sklearn     |     0.483499 |       2.16289  |   1.25044  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465626 |        5.17964 |   0.735112 |
| Bori_Aron_solution-1 |     0.465694 |       11.1795  |   0.821595 |
| k-d_tree_sklearn     |     0.477679 |       17.4179  |   1.33653  |
| k-d_tree_polars      |     0.485905 |        5.36826 |   6.65701  |
| barab-szabi-1        |     0.475953 |        5.3843  |   6.84769  |
| k-d_tree_pandas      |     0.486364 |        4.36614 |   7.02199  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.93441  |        74.5982 |    2.98838 |
| k-d_tree_sklearn     |     0.652331 |       234.383  |    3.71183 |
| Bori_Aron_solution-1 |     0.471927 |       159.633  |   17.0685  |