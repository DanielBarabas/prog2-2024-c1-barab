# 2025-07-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.53597  |       0.653445 |   0.416384 |
| barab-szabi-1        |     0.552531 |       0.39711  |   0.416432 |
| k-d_tree_polars      |     0.548608 |       0.398222 |   0.417055 |
| solution-1           |     8.08833  |       1e-06    |   0.440433 |
| k-d_tree_pandas      |     0.588647 |       0.379571 |   0.543843 |
| Bori_Aron_solution-1 |     0.528003 |       0.535774 |   0.548654 |
| k-d_tree_sklearn     |     3.25372  |       1.09252  |   1.031    |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548812 |       0.415737 |   0.421138 |
| k-d_tree_polars      |     0.54751  |       0.40788  |   0.423069 |
| barab-szabi-1        |     0.550002 |       0.405788 |   0.42502  |
| Bori_Aron_solution-1 |     0.546909 |       0.544759 |   0.548458 |
| k-d_tree_pandas      |     0.551558 |       0.38758  |   0.555494 |
| k-d_tree_sklearn     |     0.568058 |       0.957478 |   1.03911  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551962 |       0.429979 |   0.434051 |
| barab-szabi-1        |     0.553156 |       0.432259 |   0.453213 |
| k-d_tree_polars      |     0.548878 |       0.428435 |   0.521336 |
| Bori_Aron_solution-1 |     0.542788 |       0.595091 |   0.540518 |
| k-d_tree_pandas      |     0.554876 |       0.400078 |   0.592487 |
| k-d_tree_sklearn     |     0.553972 |       0.996839 |   1.06914  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552016 |       0.498119 |   0.460028 |
| k-d_tree_polars      |     0.550066 |       0.54254  |   0.548527 |
| barab-szabi-1        |     0.558416 |       0.551245 |   0.566575 |
| Bori_Aron_solution-1 |     0.549812 |       0.766881 |   0.567384 |
| k-d_tree_pandas      |     0.564674 |       0.483664 |   0.747629 |
| k-d_tree_sklearn     |     0.563035 |       1.23185  |   1.12317  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572267 |       0.762411 |   0.534974 |
| Bori_Aron_solution-1 |     0.548687 |       1.40114  |   0.581002 |
| k-d_tree_polars      |     0.547843 |       0.882638 |   0.921666 |
| barab-szabi-1        |     0.56525  |       0.876791 |   0.96518  |
| k-d_tree_pandas      |     0.561425 |       0.759443 |   1.17617  |
| k-d_tree_sklearn     |     0.554505 |       2.06108  |   1.20121  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554001 |        5.32551 |   0.731619 |
| Bori_Aron_solution-1 |     0.555026 |       10.6551  |   0.836853 |
| k-d_tree_sklearn     |     0.557457 |       16.4567  |   1.31597  |
| barab-szabi-1        |     0.560867 |        4.95482 |   6.64517  |
| k-d_tree_polars      |     0.559438 |        4.99342 |   6.70067  |
| k-d_tree_pandas      |     0.550834 |        3.96307 |   7.1204   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55725  |        73.0724 |    2.69524 |
| k-d_tree_sklearn     |     0.87311  |       228.587  |    3.96624 |
| Bori_Aron_solution-1 |     0.555682 |       148.635  |   18.3485  |