# 2026-08-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     5.01088  |       0.65365  |   0.451284 |
| barab-szabi-1        |     0.465387 |       0.417926 |   0.451751 |
| k-d_tree_polars      |     0.466073 |       0.417001 |   0.45469  |
| solution-1           |     8.20167  |       1e-06    |   0.478345 |
| Bori_Aron_solution-1 |     4.53345  |       0.60794  |   0.486333 |
| k-d_tree_pandas      |     0.478861 |       0.390352 |   0.586178 |
| k-d_tree_sklearn     |     3.06847  |       1.14271  |   1.08101  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474584 |       0.454623 |   0.448944 |
| k-d_tree_polars      |     0.481667 |       0.433027 |   0.455433 |
| barab-szabi-1        |     0.47171  |       0.428893 |   0.459937 |
| Bori_Aron_solution-1 |     0.463644 |       0.560604 |   0.549217 |
| k-d_tree_pandas      |     0.474431 |       0.391513 |   0.553949 |
| k-d_tree_sklearn     |     0.476495 |       1.00679  |   1.07595  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476132 |       0.459301 |   0.471562 |
| k-d_tree_polars      |     0.489035 |       0.488803 |   0.49249  |
| barab-szabi-1        |     0.49105  |       0.469069 |   0.496181 |
| Bori_Aron_solution-1 |     0.465776 |       0.595981 |   0.551735 |
| k-d_tree_pandas      |     0.472023 |       0.4225   |   0.614358 |
| k-d_tree_sklearn     |     0.486579 |       1.0998   |   1.17046  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484293 |       0.54241  |   0.493114 |
| k-d_tree_polars      |     0.486534 |       0.566848 |   0.590768 |
| Bori_Aron_solution-1 |     0.486661 |       0.800354 |   0.592803 |
| barab-szabi-1        |     0.48357  |       0.585173 |   0.596403 |
| k-d_tree_pandas      |     0.485615 |       0.505619 |   0.763951 |
| k-d_tree_sklearn     |     0.483194 |       1.31176  |   1.18697  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475595 |       0.746132 |   0.519464 |
| Bori_Aron_solution-1 |     0.476936 |       1.44043  |   0.581873 |
| k-d_tree_polars      |     0.46881  |       0.915243 |   0.923649 |
| barab-szabi-1        |     0.472117 |       0.927931 |   0.965625 |
| k-d_tree_pandas      |     0.47101  |       0.806792 |   1.18562  |
| k-d_tree_sklearn     |     0.478227 |       2.1215   |   1.22842  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471653 |        5.08328 |    0.75458 |
| Bori_Aron_solution-1 |     0.472032 |       10.8385  |    0.8083  |
| k-d_tree_sklearn     |     0.474232 |       16.6392  |    1.29816 |
| k-d_tree_polars      |     0.474742 |        5.3092  |    6.54995 |
| barab-szabi-1        |     0.474467 |        5.32948 |    6.58852 |
| k-d_tree_pandas      |     0.471835 |        4.3265  |    6.9412  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.651145 |        70.9683 |    2.77307 |
| k-d_tree_sklearn     |     0.578081 |       235.088  |    3.91904 |
| Bori_Aron_solution-1 |     0.464526 |       155.073  |   24.9243  |