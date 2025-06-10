# 2025-06-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.06885  |       1e-06    |   0.382524 |
| barab-szabi-2        |     0.535895 |       0.419805 |   0.41501  |
| k-d_tree_polars      |     0.540287 |       0.401967 |   0.416513 |
| barab-szabi-1        |     0.535546 |       0.407897 |   0.426467 |
| Bori_Aron_solution-1 |     0.53037  |       0.538715 |   0.546337 |
| k-d_tree_pandas      |     7.96962  |       0.436106 |   0.635645 |
| k-d_tree_sklearn     |     3.08853  |       0.997514 |   1.03716  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553887 |       0.414525 |   0.42051  |
| barab-szabi-1        |     0.544966 |       0.410903 |   0.422686 |
| k-d_tree_polars      |     0.545919 |       0.406977 |   0.425886 |
| Bori_Aron_solution-1 |     0.542117 |       0.543672 |   0.545403 |
| k-d_tree_pandas      |     0.556456 |       0.448347 |   0.545904 |
| k-d_tree_sklearn     |     0.552013 |       0.971113 |   1.04952  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544912 |       0.428403 |   0.426205 |
| k-d_tree_polars      |     0.554053 |       0.473158 |   0.445452 |
| barab-szabi-1        |     0.547594 |       0.43815  |   0.448099 |
| Bori_Aron_solution-1 |     0.540969 |       0.584733 |   0.538768 |
| k-d_tree_pandas      |     0.55315  |       0.409356 |   0.607936 |
| k-d_tree_sklearn     |     0.551184 |       1.00342  |   1.0684   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557604 |       0.487905 |   0.458718 |
| k-d_tree_polars      |     0.55132  |       0.544282 |   0.541417 |
| barab-szabi-1        |     0.547434 |       0.538508 |   0.555243 |
| Bori_Aron_solution-1 |     0.539997 |       0.760451 |   0.568283 |
| k-d_tree_pandas      |     0.558012 |       0.482683 |   0.724124 |
| k-d_tree_sklearn     |     0.553258 |       1.23767  |   1.1229   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54773  |       0.737568 |   0.488268 |
| Bori_Aron_solution-1 |     0.549701 |       1.39511  |   0.576133 |
| k-d_tree_polars      |     0.547193 |       0.870125 |   0.898264 |
| barab-szabi-1        |     0.549863 |       0.874159 |   0.933394 |
| k-d_tree_pandas      |     0.552881 |       0.767009 |   1.17477  |
| k-d_tree_sklearn     |     0.550469 |       2.0461   |   1.18661  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547585 |        5.21727 |   0.739697 |
| Bori_Aron_solution-1 |     0.545067 |       10.5838  |   0.829907 |
| k-d_tree_sklearn     |     0.551793 |       15.9706  |   1.30015  |
| k-d_tree_polars      |     0.54632  |        4.98634 |   6.50718  |
| barab-szabi-1        |     0.548262 |        4.90502 |   6.51999  |
| k-d_tree_pandas      |     0.545895 |        3.91864 |   6.87923  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.793074 |        76.7106 |    2.89646 |
| k-d_tree_sklearn     |     0.628006 |       236.529  |    3.9171  |
| Bori_Aron_solution-1 |     0.541363 |       140.78   |   17.6612  |