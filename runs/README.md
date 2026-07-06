# 2026-07-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.11705  |       1e-06    |   0.449662 |
| barab-szabi-2        |     8.62017  |       0.695529 |   0.461533 |
| k-d_tree_polars      |     0.496828 |       0.444431 |   0.462519 |
| barab-szabi-1        |     0.965817 |       0.439173 |   0.468072 |
| Bori_Aron_solution-1 |     0.640426 |       0.567786 |   0.566378 |
| k-d_tree_pandas      |     0.482157 |       0.396782 |   0.581356 |
| k-d_tree_sklearn     |     3.02754  |       1.33082  |   1.13165  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480037 |       0.451715 |   0.452219 |
| k-d_tree_polars      |     0.478454 |       0.436622 |   0.460632 |
| barab-szabi-1        |     0.497683 |       0.472148 |   0.481634 |
| Bori_Aron_solution-1 |     0.483498 |       0.572302 |   0.570132 |
| k-d_tree_pandas      |     0.519976 |       0.417489 |   0.598454 |
| k-d_tree_sklearn     |     0.481522 |       1.10986  |   1.1696   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496402 |       0.476487 |   0.477049 |
| barab-szabi-1        |     0.493264 |       0.476279 |   0.490105 |
| k-d_tree_polars      |     0.497515 |       0.465788 |   0.521714 |
| Bori_Aron_solution-1 |     0.47723  |       0.619309 |   0.591234 |
| k-d_tree_pandas      |     0.481181 |       0.426657 |   0.628528 |
| k-d_tree_sklearn     |     0.51523  |       1.09283  |   1.13628  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490719 |       0.52509  |   0.493375 |
| Bori_Aron_solution-1 |     0.487317 |       0.815071 |   0.578788 |
| k-d_tree_polars      |     0.48489  |       0.605013 |   0.614325 |
| barab-szabi-1        |     0.478635 |       0.597697 |   0.617175 |
| k-d_tree_pandas      |     0.506374 |       0.535419 |   0.755955 |
| k-d_tree_sklearn     |     0.499036 |       1.33222  |   1.2542   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.485428 |       1.46475  |   0.591113 |
| barab-szabi-2        |     0.4855   |       0.761637 |   0.600704 |
| k-d_tree_polars      |     0.485162 |       0.945412 |   0.945998 |
| barab-szabi-1        |     0.483141 |       0.933383 |   0.996883 |
| k-d_tree_pandas      |     0.500105 |       0.808997 |   1.21992  |
| k-d_tree_sklearn     |     0.477752 |       2.29173  |   1.34681  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.50241  |        5.41226 |   0.767578 |
| Bori_Aron_solution-1 |     0.480072 |       11.4163  |   0.826637 |
| k-d_tree_sklearn     |     0.477484 |       17.6003  |   1.333    |
| k-d_tree_polars      |     0.517514 |        5.42043 |   6.97857  |
| barab-szabi-1        |     0.474882 |        5.36512 |   7.09749  |
| k-d_tree_pandas      |     0.48033  |        4.43018 |   7.65741  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492487 |        74.8589 |    2.85648 |
| k-d_tree_sklearn     |     0.842848 |       253.42   |    4.17083 |
| Bori_Aron_solution-1 |     0.474169 |       150.286  |   23.9382  |