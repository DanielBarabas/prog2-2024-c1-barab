# 2026-08-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.43112  |       1e-06    |   0.358023 |
| k-d_tree_polars      |     0.470081 |       0.428337 |   0.44382  |
| barab-szabi-2        |     4.50866  |       0.46342  |   0.44784  |
| barab-szabi-1        |     0.479288 |       0.438909 |   0.46116  |
| Bori_Aron_solution-1 |     4.48522  |       0.608496 |   0.488278 |
| k-d_tree_pandas      |     0.478978 |       0.397114 |   0.567522 |
| k-d_tree_sklearn     |     2.92617  |       1.17409  |   1.09252  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.468926 |       0.442569 |   0.45204  |
| k-d_tree_polars      |     0.492528 |       0.439526 |   0.454733 |
| barab-szabi-2        |     0.474794 |       0.44876  |   0.456167 |
| Bori_Aron_solution-1 |     0.471744 |       0.61454  |   0.564127 |
| k-d_tree_pandas      |     0.472506 |       0.403034 |   0.566967 |
| k-d_tree_sklearn     |     0.486448 |       1.02687  |   1.10588  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48475  |       0.457382 |   0.457187 |
| barab-szabi-1        |     0.473387 |       0.468688 |   0.479603 |
| k-d_tree_polars      |     0.481319 |       0.461108 |   0.483266 |
| Bori_Aron_solution-1 |     0.479558 |       0.60319  |   0.563172 |
| k-d_tree_pandas      |     0.483631 |       0.416271 |   0.594093 |
| k-d_tree_sklearn     |     0.476046 |       1.09326  |   1.12355  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471398 |       0.551527 |   0.483546 |
| Bori_Aron_solution-1 |     0.47227  |       0.790521 |   0.571039 |
| k-d_tree_polars      |     0.479027 |       0.577271 |   0.571764 |
| barab-szabi-1        |     0.476885 |       0.5801   |   0.591458 |
| k-d_tree_pandas      |     0.485176 |       0.496618 |   0.727106 |
| k-d_tree_sklearn     |     0.487833 |       1.32131  |   1.15737  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497311 |       0.778847 |   0.564488 |
| Bori_Aron_solution-1 |     0.46165  |       1.47302  |   0.593155 |
| k-d_tree_polars      |     0.481863 |       0.919936 |   0.969426 |
| barab-szabi-1        |     0.480597 |       0.899063 |   1.01099  |
| k-d_tree_pandas      |     0.479629 |       0.763108 |   1.19069  |
| k-d_tree_sklearn     |     0.478787 |       2.21763  |   1.20761  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482984 |        5.66112 |   0.765214 |
| Bori_Aron_solution-1 |     0.469933 |       11.4924  |   0.835772 |
| k-d_tree_sklearn     |     0.491709 |       18.4655  |   1.38353  |
| barab-szabi-1        |     0.475165 |        5.03188 |   7.482    |
| k-d_tree_polars      |     0.47766  |        5.13217 |   7.6256   |
| k-d_tree_pandas      |     0.473629 |        3.99228 |   7.83865  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.767525 |        80.7094 |    2.64613 |
| k-d_tree_sklearn     |     0.565581 |       272.667  |    3.42395 |
| Bori_Aron_solution-1 |     0.496432 |       161.019  |   21.0496  |