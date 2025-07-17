# 2025-07-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.07172  |       0.855314 |   0.438374 |
| barab-szabi-1        |     0.566463 |       0.419946 |   0.440068 |
| k-d_tree_polars      |     0.58589  |       0.442305 |   0.448843 |
| solution-1           |     7.90896  |       1e-06    |   0.552521 |
| Bori_Aron_solution-1 |     0.561246 |       0.579394 |   0.572311 |
| k-d_tree_pandas      |     0.583014 |       0.424258 |   0.593142 |
| k-d_tree_sklearn     |     3.11889  |       1.17593  |   1.14873  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577725 |       0.437795 |   0.447231 |
| k-d_tree_polars      |     0.581196 |       0.443016 |   0.44798  |
| barab-szabi-1        |     0.583884 |       0.443569 |   0.451331 |
| k-d_tree_pandas      |     0.568929 |       0.403153 |   0.580907 |
| Bori_Aron_solution-1 |     0.576303 |       0.588197 |   0.592859 |
| k-d_tree_sklearn     |     0.584733 |       1.0642   |   1.13491  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572161 |       0.455326 |   0.470336 |
| barab-szabi-1        |     0.598735 |       0.471915 |   0.486558 |
| k-d_tree_polars      |     0.608415 |       0.496248 |   0.489748 |
| Bori_Aron_solution-1 |     0.576312 |       0.621353 |   0.61167  |
| k-d_tree_pandas      |     0.593649 |       0.43835  |   0.639307 |
| k-d_tree_sklearn     |     0.604517 |       1.15214  |   1.20154  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588343 |       0.532608 |   0.494672 |
| k-d_tree_polars      |     0.586497 |       0.595249 |   0.585701 |
| barab-szabi-1        |     0.592361 |       0.5806   |   0.610533 |
| Bori_Aron_solution-1 |     0.579103 |       0.829765 |   0.625068 |
| k-d_tree_pandas      |     0.575274 |       0.519115 |   0.784032 |
| k-d_tree_sklearn     |     0.596415 |       1.34587  |   1.23671  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594084 |       0.797857 |   0.60311  |
| Bori_Aron_solution-1 |     0.612583 |       1.55226  |   0.689852 |
| k-d_tree_polars      |     0.642075 |       0.959402 |   1.00841  |
| barab-szabi-1        |     0.585122 |       0.9228   |   1.05551  |
| k-d_tree_pandas      |     0.60922  |       0.830321 |   1.31958  |
| k-d_tree_sklearn     |     0.622048 |       2.38714  |   1.44239  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61343  |        6.09462 |   0.804268 |
| Bori_Aron_solution-1 |     0.573642 |       11.5255  |   0.891551 |
| k-d_tree_sklearn     |     0.591589 |       18.093   |   1.38071  |
| k-d_tree_polars      |     0.569662 |        5.10248 |   7.47048  |
| barab-szabi-1        |     0.60666  |        5.12549 |   7.56826  |
| k-d_tree_pandas      |     0.589386 |        4.00192 |   7.98012  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622662 |        74.1884 |    2.80357 |
| k-d_tree_sklearn     |     0.779558 |       249.526  |    4.15329 |
| Bori_Aron_solution-1 |     0.557981 |       146.387  |   17.3134  |