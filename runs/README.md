# 2025-04-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.73301  |       1e-06    |   0.360385 |
| k-d_tree_polars      |     0.548607 |       0.397296 |   0.407673 |
| barab-szabi-1        |     0.552043 |       0.401111 |   0.413351 |
| barab-szabi-2        |     0.547821 |       0.415581 |   0.415505 |
| Bori_Aron_solution-1 |     0.545097 |       0.564134 |   0.567115 |
| k-d_tree_pandas      |     7.59853  |       0.395725 |   0.665134 |
| k-d_tree_sklearn     |     3.06911  |       1.15535  |   1.05301  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56009  |       0.410002 |   0.405423 |
| k-d_tree_polars      |     0.571622 |       0.40815  |   0.412236 |
| barab-szabi-1        |     0.56749  |       0.407869 |   0.41341  |
| Bori_Aron_solution-1 |     0.555881 |       0.55027  |   0.540689 |
| k-d_tree_pandas      |     0.561347 |       0.392361 |   0.554157 |
| k-d_tree_sklearn     |     0.563526 |       0.953087 |   1.02506  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561282 |       0.425199 |   0.416695 |
| k-d_tree_polars      |     0.567097 |       0.43259  |   0.436561 |
| barab-szabi-1        |     0.564071 |       0.431654 |   0.481047 |
| Bori_Aron_solution-1 |     0.553844 |       0.5834   |   0.550183 |
| k-d_tree_pandas      |     0.563928 |       0.404368 |   0.602342 |
| k-d_tree_sklearn     |     0.56532  |       0.998365 |   1.07248  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57481  |       0.491579 |   0.446325 |
| k-d_tree_polars      |     0.563316 |       0.537436 |   0.54517  |
| barab-szabi-1        |     0.56585  |       0.532117 |   0.545292 |
| Bori_Aron_solution-1 |     0.556643 |       0.758009 |   0.553749 |
| k-d_tree_pandas      |     0.567716 |       0.477354 |   0.726882 |
| k-d_tree_sklearn     |     0.565644 |       1.21612  |   1.10773  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56966  |       0.726151 |   0.481218 |
| Bori_Aron_solution-1 |     0.55627  |       1.38675  |   0.59193  |
| k-d_tree_polars      |     0.559494 |       0.86362  |   0.885213 |
| barab-szabi-1        |     0.560036 |       0.86516  |   0.926401 |
| k-d_tree_pandas      |     0.571483 |       0.746126 |   1.17006  |
| k-d_tree_sklearn     |     0.566509 |       2.03639  |   1.20516  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565958 |        5.30984 |   0.710849 |
| Bori_Aron_solution-1 |     0.553703 |       10.5108  |   0.877378 |
| k-d_tree_sklearn     |     0.567367 |       16.0518  |   1.30771  |
| barab-szabi-1        |     0.564791 |        4.98486 |   6.50242  |
| k-d_tree_polars      |     0.569069 |        4.92629 |   6.51558  |
| k-d_tree_pandas      |     0.561553 |        3.82809 |   6.86805  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735765 |         70.671 |    2.86103 |
| k-d_tree_sklearn     |     0.656714 |        226.976 |    4.16701 |
| Bori_Aron_solution-1 |     0.555731 |        150.169 |   16.4005  |