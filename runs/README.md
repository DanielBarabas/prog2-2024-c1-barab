# 2026-02-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498255 |       0.457893 |   0.44298  |
| k-d_tree_polars      |     0.501481 |       0.42644  |   0.462363 |
| solution-1           |     8.8805   |       1e-06    |   0.540285 |
| k-d_tree_pandas      |     0.498236 |       0.408291 |   0.58042  |
| Bori_Aron_solution-1 |     0.497496 |       0.574964 |   0.582879 |
| barab-szabi-1        |     9.25813  |       0.458878 |   0.609169 |
| k-d_tree_sklearn     |     3.48948  |       1.14171  |   1.13316  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.525495 |       0.444628 |   0.453126 |
| barab-szabi-1        |     0.513973 |       0.443555 |   0.458119 |
| barab-szabi-2        |     0.512253 |       0.461099 |   0.463374 |
| k-d_tree_pandas      |     0.514572 |       0.414681 |   0.580878 |
| Bori_Aron_solution-1 |     0.514927 |       0.585777 |   0.587521 |
| k-d_tree_sklearn     |     0.516475 |       1.03812  |   1.12093  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.513608 |       0.474467 |   0.478907 |
| k-d_tree_polars      |     0.520492 |       0.511926 |   0.494071 |
| barab-szabi-1        |     0.516785 |       0.458956 |   0.505245 |
| Bori_Aron_solution-1 |     0.520057 |       0.618134 |   0.584954 |
| k-d_tree_pandas      |     0.505901 |       0.431406 |   0.635778 |
| k-d_tree_sklearn     |     0.523702 |       1.08659  |   1.16314  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.510159 |       0.529311 |   0.490862 |
| k-d_tree_polars      |     0.51629  |       0.574071 |   0.579732 |
| Bori_Aron_solution-1 |     0.502694 |       0.810291 |   0.593943 |
| barab-szabi-1        |     0.511843 |       0.589718 |   0.594665 |
| k-d_tree_pandas      |     0.512473 |       0.525816 |   0.775722 |
| k-d_tree_sklearn     |     0.522123 |       1.31084  |   1.18292  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518459 |       0.766927 |   0.597265 |
| Bori_Aron_solution-1 |     0.513716 |       1.51798  |   0.609811 |
| k-d_tree_polars      |     0.512228 |       0.954633 |   0.959073 |
| barab-szabi-1        |     0.511719 |       0.951877 |   1.0151   |
| k-d_tree_pandas      |     0.511261 |       0.848718 |   1.23695  |
| k-d_tree_sklearn     |     0.522539 |       2.24866  |   1.29418  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519474 |        5.33142 |   0.776871 |
| Bori_Aron_solution-1 |     0.509991 |       11.4046  |   0.869332 |
| k-d_tree_sklearn     |     0.5149   |       17.4859  |   1.40571  |
| k-d_tree_polars      |     0.518178 |        5.7338  |   6.85023  |
| barab-szabi-1        |     0.521924 |        5.73128 |   6.87143  |
| k-d_tree_pandas      |     0.512287 |        4.45181 |   7.3451   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.700121 |       247.248  |    4.01081 |
| barab-szabi-2        |     0.510591 |        76.8927 |    4.82381 |
| Bori_Aron_solution-1 |     0.530431 |       156.024  |   18.5046  |