# 2026-01-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.541821 |       0.41173  |   0.426116 |
| barab-szabi-2        |     0.936332 |       0.526121 |   0.427464 |
| k-d_tree_polars      |     0.497332 |       0.400752 |   0.430207 |
| solution-1           |     7.56986  |       1e-06    |   0.476336 |
| Bori_Aron_solution-1 |     0.483852 |       0.551583 |   0.539664 |
| k-d_tree_pandas      |     9.57777  |       0.410877 |   0.820169 |
| k-d_tree_sklearn     |     3.28668  |       1.07876  |   1.03636  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.527865 |       0.431291 |   0.442448 |
| barab-szabi-2        |     0.494611 |       0.446534 |   0.456433 |
| barab-szabi-1        |     0.537287 |       0.441736 |   0.46252  |
| k-d_tree_pandas      |     0.494626 |       0.388172 |   0.547369 |
| Bori_Aron_solution-1 |     0.491352 |       0.554686 |   0.54793  |
| k-d_tree_sklearn     |     0.513258 |       0.985082 |   1.13648  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500485 |       0.4505   |   0.446018 |
| barab-szabi-1        |     0.491945 |       0.43772  |   0.46382  |
| k-d_tree_polars      |     0.514555 |       0.439936 |   0.463938 |
| Bori_Aron_solution-1 |     0.493793 |       0.595244 |   0.580734 |
| k-d_tree_pandas      |     0.503098 |       0.408945 |   0.595258 |
| k-d_tree_sklearn     |     0.503175 |       1.00841  |   1.07586  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497582 |       0.510279 |   0.477525 |
| k-d_tree_polars      |     0.50014  |       0.549884 |   0.540349 |
| barab-szabi-1        |     0.504854 |       0.577187 |   0.565119 |
| Bori_Aron_solution-1 |     0.489084 |       0.776158 |   0.592042 |
| k-d_tree_pandas      |     0.505353 |       0.492653 |   0.728464 |
| k-d_tree_sklearn     |     0.505867 |       1.28276  |   1.13356  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.512516 |       0.734442 |   0.533316 |
| Bori_Aron_solution-1 |     0.490292 |       1.41044  |   0.605009 |
| k-d_tree_polars      |     0.49481  |       0.900776 |   0.889548 |
| barab-szabi-1        |     0.506384 |       0.906224 |   0.917192 |
| k-d_tree_pandas      |     0.513142 |       0.775092 |   1.12071  |
| k-d_tree_sklearn     |     0.516088 |       2.08111  |   1.2163   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.509074 |        5.89379 |   0.849151 |
| Bori_Aron_solution-1 |     0.486135 |       11.022   |   1.02191  |
| k-d_tree_sklearn     |     0.509816 |       16.2584  |   1.39423  |
| k-d_tree_polars      |     0.501531 |        5.06592 |   6.79849  |
| barab-szabi-1        |     0.502273 |        5.13248 |   6.89405  |
| k-d_tree_pandas      |     0.508084 |        4.00176 |   7.46189  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491607 |        97.7844 |    3.69104 |
| k-d_tree_sklearn     |     0.521744 |       210.238  |    4.85292 |
| Bori_Aron_solution-1 |     0.594811 |       154.735  |   15.8666  |