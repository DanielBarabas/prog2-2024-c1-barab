# 2026-08-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.43858  |       1e-06    |   0.428135 |
| barab-szabi-2        |     4.5735   |       0.539565 |   0.453721 |
| barab-szabi-1        |     0.477855 |       0.442444 |   0.466888 |
| k-d_tree_polars      |     0.473353 |       0.434335 |   0.46977  |
| Bori_Aron_solution-1 |     4.85283  |       0.649822 |   0.502524 |
| k-d_tree_pandas      |     0.478433 |       0.418419 |   0.589723 |
| k-d_tree_sklearn     |     3.19235  |       1.1869   |   1.11892  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476865 |       0.466713 |   0.466422 |
| barab-szabi-1        |     0.510213 |       0.450233 |   0.471667 |
| k-d_tree_polars      |     0.506689 |       0.457169 |   0.487065 |
| Bori_Aron_solution-1 |     0.474389 |       0.56629  |   0.557256 |
| k-d_tree_pandas      |     0.481415 |       0.404827 |   0.568371 |
| k-d_tree_sklearn     |     0.493213 |       1.01851  |   1.14496  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478194 |       0.479172 |   0.469689 |
| k-d_tree_polars      |     0.494876 |       0.50322  |   0.50197  |
| barab-szabi-1        |     0.510524 |       0.525138 |   0.52362  |
| Bori_Aron_solution-1 |     0.47386  |       0.624108 |   0.567964 |
| k-d_tree_pandas      |     0.501776 |       0.440263 |   0.653    |
| k-d_tree_sklearn     |     0.491746 |       1.08395  |   1.2178   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495966 |       0.521614 |   0.520177 |
| barab-szabi-1        |     0.491873 |       0.585217 |   0.588511 |
| k-d_tree_polars      |     0.497748 |       0.588051 |   0.592099 |
| Bori_Aron_solution-1 |     0.496752 |       0.815128 |   0.605446 |
| k-d_tree_pandas      |     0.492126 |       0.534578 |   0.794104 |
| k-d_tree_sklearn     |     0.495382 |       1.36943  |   1.20587  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.513511 |       0.747083 |   0.54826  |
| Bori_Aron_solution-1 |     0.48182  |       1.47589  |   0.620342 |
| k-d_tree_polars      |     0.485807 |       0.928934 |   0.978647 |
| barab-szabi-1        |     0.478779 |       0.975118 |   0.998593 |
| k-d_tree_pandas      |     0.490782 |       0.810666 |   1.22488  |
| k-d_tree_sklearn     |     0.499983 |       2.25826  |   1.30124  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482142 |        5.41457 |   0.786945 |
| Bori_Aron_solution-1 |     0.493881 |       11.1749  |   0.830756 |
| k-d_tree_sklearn     |     0.504577 |       17.6589  |   1.37071  |
| barab-szabi-1        |     0.482805 |        5.33414 |   7.06061  |
| k-d_tree_polars      |     0.484013 |        5.38607 |   7.1069   |
| k-d_tree_pandas      |     0.490533 |        4.26267 |   7.45705  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.789269 |        72.3443 |    2.86974 |
| k-d_tree_sklearn     |     0.603643 |       241.63   |    4.00755 |
| Bori_Aron_solution-1 |     0.487954 |       155.431  |   27.6267  |