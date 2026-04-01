# 2026-04-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457454 |       0.430124 |   0.426167 |
| k-d_tree_polars      |     0.458819 |       0.403499 |   0.426872 |
| solution-1           |     7.42479  |       1e-06    |   0.460333 |
| Bori_Aron_solution-1 |     0.450064 |       0.557798 |   0.540951 |
| k-d_tree_pandas      |     0.460798 |       0.38074  |   0.546094 |
| barab-szabi-1        |     8.42949  |       0.430515 |   0.56023  |
| k-d_tree_sklearn     |     2.93074  |       1.05272  |   1.06562  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464543 |       0.428317 |   0.429064 |
| barab-szabi-1        |     0.455401 |       0.403228 |   0.432917 |
| k-d_tree_polars      |     0.457195 |       0.401459 |   0.43677  |
| Bori_Aron_solution-1 |     0.444564 |       0.54059  |   0.537752 |
| k-d_tree_pandas      |     0.457921 |       0.385174 |   0.547074 |
| k-d_tree_sklearn     |     0.458055 |       0.962772 |   1.05717  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452413 |       0.441372 |   0.437729 |
| k-d_tree_polars      |     0.462594 |       0.434777 |   0.458035 |
| barab-szabi-1        |     0.457932 |       0.429247 |   0.463125 |
| Bori_Aron_solution-1 |     0.447707 |       0.588009 |   0.545683 |
| k-d_tree_pandas      |     0.458093 |       0.402075 |   0.591281 |
| k-d_tree_sklearn     |     0.460185 |       1.00458  |   1.08095  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458252 |       0.498885 |   0.467412 |
| Bori_Aron_solution-1 |     0.462324 |       0.767148 |   0.555847 |
| k-d_tree_polars      |     0.458477 |       0.567507 |   0.560839 |
| barab-szabi-1        |     0.453545 |       0.566414 |   0.570453 |
| k-d_tree_pandas      |     0.452502 |       0.497619 |   0.728692 |
| k-d_tree_sklearn     |     0.458011 |       1.24075  |   1.13411  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.455885 |       0.718545 |   0.50787  |
| Bori_Aron_solution-1 |     0.448359 |       1.4318   |   0.575443 |
| k-d_tree_polars      |     0.458908 |       0.924214 |   0.903686 |
| barab-szabi-1        |     0.458247 |       0.92455  |   0.950738 |
| k-d_tree_pandas      |     0.453944 |       0.809602 |   1.16048  |
| k-d_tree_sklearn     |     0.45658  |       2.12071  |   1.20028  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459138 |        5.11957 |   0.752586 |
| Bori_Aron_solution-1 |     0.452586 |       10.938   |   0.802147 |
| k-d_tree_sklearn     |     0.457733 |       17.0863  |   1.29665  |
| barab-szabi-1        |     0.454893 |        5.66639 |   6.65814  |
| k-d_tree_polars      |     0.457311 |        5.63373 |   6.69163  |
| k-d_tree_pandas      |     0.457033 |        4.49334 |   7.0823   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73148  |        69.8022 |    2.74214 |
| k-d_tree_sklearn     |     0.462181 |       237.537  |    3.81422 |
| Bori_Aron_solution-1 |     0.455138 |       155.47   |   16.8631  |