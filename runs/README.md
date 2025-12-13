# 2025-12-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.79131  |       1e-06    |   0.376879 |
| k-d_tree_polars      |     0.551191 |       0.404333 |   0.43651  |
| barab-szabi-1        |     0.531417 |       0.410361 |   0.436649 |
| barab-szabi-2        |     0.530124 |       0.468874 |   0.445486 |
| Bori_Aron_solution-1 |     0.52733  |       0.551147 |   0.553474 |
| k-d_tree_pandas      |     8.51948  |       0.427245 |   0.597852 |
| k-d_tree_sklearn     |     3.1074   |       1.03116  |   1.0748   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535262 |       0.432633 |   0.436223 |
| barab-szabi-1        |     0.537329 |       0.416069 |   0.440504 |
| k-d_tree_polars      |     0.535567 |       0.41803  |   0.443146 |
| Bori_Aron_solution-1 |     0.536393 |       0.562214 |   0.559265 |
| k-d_tree_pandas      |     0.596438 |       0.410685 |   0.57142  |
| k-d_tree_sklearn     |     0.543056 |       0.989957 |   1.07202  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532353 |       0.446806 |   0.453142 |
| k-d_tree_polars      |     0.534193 |       0.443927 |   0.468597 |
| barab-szabi-1        |     0.538164 |       0.451045 |   0.470811 |
| Bori_Aron_solution-1 |     0.519109 |       0.599371 |   0.577577 |
| k-d_tree_pandas      |     0.534557 |       0.409583 |   0.610548 |
| k-d_tree_sklearn     |     0.546057 |       1.03802  |   1.15785  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531014 |       0.512035 |   0.475702 |
| k-d_tree_polars      |     0.529141 |       0.563802 |   0.561954 |
| Bori_Aron_solution-1 |     0.523463 |       0.790202 |   0.567725 |
| barab-szabi-1        |     0.529648 |       0.576652 |   0.58464  |
| k-d_tree_pandas      |     0.532346 |       0.509995 |   0.740844 |
| k-d_tree_sklearn     |     0.537513 |       1.26462  |   1.15062  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537658 |       0.742246 |   0.512561 |
| Bori_Aron_solution-1 |     0.531161 |       1.47157  |   0.599195 |
| k-d_tree_polars      |     0.529433 |       0.936812 |   0.913659 |
| barab-szabi-1        |     0.542651 |       0.954194 |   0.953611 |
| k-d_tree_pandas      |     0.540358 |       0.833046 |   1.20157  |
| k-d_tree_sklearn     |     0.543596 |       2.16242  |   1.25449  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542065 |        5.29614 |   0.757372 |
| Bori_Aron_solution-1 |     0.522232 |       11.3361  |   0.856456 |
| k-d_tree_sklearn     |     0.54455  |       17.1764  |   1.37299  |
| barab-szabi-1        |     0.535484 |        5.38205 |   6.72571  |
| k-d_tree_polars      |     0.531238 |        5.42238 |   6.77419  |
| k-d_tree_pandas      |     0.538138 |        4.50871 |   7.17687  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53407  |        80.8558 |    2.80809 |
| k-d_tree_sklearn     |     0.551414 |       240.284  |    4.241   |
| Bori_Aron_solution-1 |     0.69766  |       153.857  |   18.1388  |