# 2026-03-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.903947 |       0.44849  |   0.44679  |
| k-d_tree_polars      |     0.486403 |       0.408948 |   0.449029 |
| solution-1           |     7.86483  |       1e-06    |   0.484322 |
| Bori_Aron_solution-1 |     0.480703 |       0.555654 |   0.55674  |
| k-d_tree_pandas      |     0.484676 |       0.387589 |   0.56586  |
| barab-szabi-1        |     8.43152  |       0.555615 |   0.627402 |
| k-d_tree_sklearn     |     2.94552  |       1.10745  |   1.21307  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495071 |       0.446186 |   0.441218 |
| k-d_tree_polars      |     0.507052 |       0.452276 |   0.446629 |
| barab-szabi-1        |     0.501546 |       0.424713 |   0.450289 |
| Bori_Aron_solution-1 |     0.490721 |       0.561612 |   0.556179 |
| k-d_tree_pandas      |     0.497228 |       0.396085 |   0.573229 |
| k-d_tree_sklearn     |     0.500589 |       0.986903 |   1.09381  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.501202 |       0.451299 |   0.455496 |
| k-d_tree_polars      |     0.510306 |       0.458439 |   0.476244 |
| barab-szabi-1        |     0.501666 |       0.443975 |   0.481551 |
| Bori_Aron_solution-1 |     0.488307 |       0.608927 |   0.568267 |
| k-d_tree_pandas      |     0.505025 |       0.417273 |   0.620867 |
| k-d_tree_sklearn     |     0.505821 |       1.03893  |   1.16249  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499569 |       0.518265 |   0.494236 |
| k-d_tree_polars      |     0.497079 |       0.574831 |   0.574563 |
| Bori_Aron_solution-1 |     0.494203 |       0.793413 |   0.574805 |
| barab-szabi-1        |     0.500254 |       0.575427 |   0.582451 |
| k-d_tree_pandas      |     0.496979 |       0.523185 |   0.750057 |
| k-d_tree_sklearn     |     0.499737 |       1.28991  |   1.15535  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498456 |       0.757498 |   0.546631 |
| Bori_Aron_solution-1 |     0.501469 |       1.4787   |   0.592472 |
| k-d_tree_polars      |     0.502268 |       0.951726 |   0.925555 |
| barab-szabi-1        |     0.504169 |       0.955    |   0.979036 |
| k-d_tree_pandas      |     0.499868 |       0.831652 |   1.19373  |
| k-d_tree_sklearn     |     0.501237 |       2.15468  |   1.23636  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492776 |        5.39323 |   0.751245 |
| Bori_Aron_solution-1 |     0.494684 |       11.6323  |   0.833236 |
| k-d_tree_sklearn     |     0.498525 |       17.5374  |   1.31539  |
| barab-szabi-1        |     0.495088 |        5.6231  |   6.83064  |
| k-d_tree_polars      |     0.505084 |        5.78981 |   6.89625  |
| k-d_tree_pandas      |     0.497192 |        4.61453 |   7.29509  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499071 |        72.0817 |    2.65091 |
| k-d_tree_sklearn     |     0.833838 |       240.114  |    3.94685 |
| Bori_Aron_solution-1 |     0.497715 |       150.143  |   21.5944  |