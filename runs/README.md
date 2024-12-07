# 2024-12-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613959 |       0.388946 |   0.380284 |
| barab-szabi-1        |     0.612435 |       0.3943   |   0.383052 |
| k-d_tree_polars      |     0.616361 |       0.410542 |   0.387132 |
| Bori_Aron_solution-1 |     0.609444 |       0.517122 |   0.513225 |
| solution-1           |     7.52628  |       1e-06    |   0.516342 |
| k-d_tree_pandas      |     0.60873  |       0.374427 |   0.523383 |
| k-d_tree_sklearn     |    10.3006   |       1.29221  |   0.968506 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.61266  |       0.402774 |   0.392692 |
| barab-szabi-2        |     0.603366 |       0.399331 |   0.397791 |
| barab-szabi-1        |     0.621424 |       0.444254 |   0.400487 |
| Bori_Aron_solution-1 |     0.648166 |       0.540001 |   0.532368 |
| k-d_tree_pandas      |     0.625557 |       0.393457 |   0.546143 |
| k-d_tree_sklearn     |     0.618226 |       0.902778 |   0.945664 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632792 |       0.398825 |   0.396047 |
| barab-szabi-1        |     0.633871 |       0.424057 |   0.41434  |
| k-d_tree_polars      |     0.613331 |       0.424971 |   0.416371 |
| Bori_Aron_solution-1 |     0.606098 |       0.557814 |   0.513386 |
| k-d_tree_pandas      |     0.606028 |       0.396778 |   0.567312 |
| k-d_tree_sklearn     |     0.625455 |       0.95543  |   0.968878 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610883 |       0.4634   |   0.422682 |
| k-d_tree_polars      |     0.62065  |       0.530593 |   0.517304 |
| barab-szabi-1        |     0.61383  |       0.535234 |   0.529012 |
| Bori_Aron_solution-1 |     0.610538 |       0.738809 |   0.54101  |
| k-d_tree_pandas      |     0.63322  |       0.479302 |   0.708797 |
| k-d_tree_sklearn     |     0.636097 |       1.17021  |   1.05782  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619146 |       0.721162 |   0.461878 |
| Bori_Aron_solution-1 |     0.606449 |       1.38931  |   0.557798 |
| k-d_tree_polars      |     0.614527 |       0.85438  |   0.879178 |
| barab-szabi-1        |     0.609405 |       0.853929 |   0.908005 |
| k-d_tree_sklearn     |     0.616499 |       1.99047  |   1.11698  |
| k-d_tree_pandas      |     0.608851 |       0.745744 |   1.14109  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610511 |        5.11183 |   0.737115 |
| Bori_Aron_solution-1 |     0.607179 |       10.4134  |   0.802214 |
| k-d_tree_sklearn     |     0.619262 |       15.5711  |   1.2391   |
| k-d_tree_polars      |     0.617701 |        4.95015 |   6.30785  |
| barab-szabi-1        |     0.612184 |        4.88404 |   6.34289  |
| k-d_tree_pandas      |     0.611799 |        3.91549 |   6.69335  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.644077 |        73.1207 |    2.82698 |
| k-d_tree_sklearn     |     0.616596 |       227.538  |    4.17692 |
| Bori_Aron_solution-1 |     0.63781  |       151.315  |   15.5909  |