# 2025-07-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556897 |       0.420225 |   0.418915 |
| barab-szabi-1        |     0.984367 |       0.412379 |   0.419271 |
| k-d_tree_polars      |     0.550947 |       0.40669  |   0.427985 |
| solution-1           |     7.71987  |       1e-06    |   0.458542 |
| Bori_Aron_solution-1 |     0.54737  |       0.549923 |   0.546231 |
| k-d_tree_pandas      |     0.555625 |       0.386998 |   0.558451 |
| k-d_tree_sklearn     |    10.4739   |       1.21862  |   1.05299  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550758 |       0.415586 |   0.425598 |
| k-d_tree_polars      |     0.550258 |       0.411233 |   0.428319 |
| barab-szabi-1        |     0.551464 |       0.411763 |   0.433779 |
| k-d_tree_pandas      |     0.552051 |       0.404952 |   0.556651 |
| Bori_Aron_solution-1 |     0.545723 |       0.559076 |   0.561904 |
| k-d_tree_sklearn     |     0.555808 |       0.979984 |   1.05708  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55742  |       0.435731 |   0.440773 |
| k-d_tree_polars      |     0.551842 |       0.441844 |   0.455773 |
| barab-szabi-1        |     0.548382 |       0.446638 |   0.45763  |
| Bori_Aron_solution-1 |     0.551857 |       0.592433 |   0.555237 |
| k-d_tree_pandas      |     0.552022 |       0.405643 |   0.603214 |
| k-d_tree_sklearn     |     0.559353 |       1.01891  |   1.09202  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555626 |       0.501228 |   0.463375 |
| k-d_tree_polars      |     0.548572 |       0.545204 |   0.549737 |
| Bori_Aron_solution-1 |     0.544152 |       0.763338 |   0.561792 |
| barab-szabi-1        |     0.548517 |       0.548623 |   0.563166 |
| k-d_tree_pandas      |     0.553806 |       0.488923 |   0.734747 |
| k-d_tree_sklearn     |     0.558414 |       1.26867  |   1.14155  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552468 |       0.747201 |   0.494816 |
| Bori_Aron_solution-1 |     0.543383 |       1.40115  |   0.58376  |
| k-d_tree_polars      |     0.549559 |       0.876261 |   0.912791 |
| barab-szabi-1        |     0.554613 |       0.891285 |   0.94895  |
| k-d_tree_pandas      |     0.552934 |       0.759096 |   1.1818   |
| k-d_tree_sklearn     |     0.552421 |       2.07126  |   1.20209  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565451 |        5.1058  |   0.72647  |
| Bori_Aron_solution-1 |     0.545971 |       10.5917  |   0.837025 |
| k-d_tree_sklearn     |     0.556322 |       15.8206  |   1.30043  |
| k-d_tree_polars      |     0.555741 |        4.89027 |   6.40157  |
| barab-szabi-1        |     0.554478 |        4.96232 |   6.41018  |
| k-d_tree_pandas      |     0.552466 |        3.90642 |   6.95414  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561044 |        70.8477 |    2.62332 |
| k-d_tree_sklearn     |     0.556706 |       227.505  |    3.92085 |
| Bori_Aron_solution-1 |     0.550297 |       137.71   |   17.7153  |