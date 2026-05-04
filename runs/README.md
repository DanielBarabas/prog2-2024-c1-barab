# 2026-05-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498108 |       0.468526 |   0.463497 |
| k-d_tree_polars      |     0.503033 |       0.442188 |   0.466334 |
| barab-szabi-1        |     0.493449 |       0.468234 |   0.485804 |
| Bori_Aron_solution-1 |     0.47422  |       0.594304 |   0.588288 |
| solution-1           |     7.47701  |       1e-06    |   0.623357 |
| k-d_tree_pandas      |     0.493069 |       0.437178 |   0.63583  |
| k-d_tree_sklearn     |    10.3923   |       1.2933   |   1.16035  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.465378 |       0.413256 |   0.429954 |
| barab-szabi-2        |     0.477941 |       0.435643 |   0.437588 |
| barab-szabi-1        |     0.474358 |       0.4232   |   0.44628  |
| Bori_Aron_solution-1 |     0.514353 |       0.579305 |   0.551532 |
| k-d_tree_pandas      |     0.482722 |       0.412573 |   0.598167 |
| k-d_tree_sklearn     |     0.511122 |       1.07653  |   1.11174  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.4846   |       0.467277 |   0.455604 |
| k-d_tree_polars      |     0.461471 |       0.459818 |   0.481357 |
| barab-szabi-1        |     0.479457 |       0.464051 |   0.50099  |
| Bori_Aron_solution-1 |     0.479008 |       0.617037 |   0.575607 |
| k-d_tree_pandas      |     0.482426 |       0.432161 |   0.613795 |
| k-d_tree_sklearn     |     0.475585 |       1.09008  |   1.1668   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5097   |       0.557137 |   0.514957 |
| Bori_Aron_solution-1 |     0.47582  |       0.787962 |   0.573958 |
| barab-szabi-1        |     0.500031 |       0.589658 |   0.601445 |
| k-d_tree_polars      |     0.473328 |       0.592579 |   0.603738 |
| k-d_tree_pandas      |     0.506636 |       0.578479 |   0.777322 |
| k-d_tree_sklearn     |     0.496866 |       1.3046   |   1.15095  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497738 |       0.764215 |   0.513531 |
| Bori_Aron_solution-1 |     0.484552 |       1.58129  |   0.647216 |
| barab-szabi-1        |     0.482486 |       0.937912 |   1.00168  |
| k-d_tree_polars      |     0.498596 |       0.975373 |   1.04051  |
| k-d_tree_pandas      |     0.456991 |       0.794307 |   1.21383  |
| k-d_tree_sklearn     |     0.504379 |       2.29386  |   1.28008  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460679 |        5.55108 |   0.753097 |
| Bori_Aron_solution-1 |     0.46034  |       11.5671  |   0.806236 |
| k-d_tree_sklearn     |     0.465702 |       17.735   |   1.30512  |
| barab-szabi-1        |     0.466418 |        5.32576 |   7.34164  |
| k-d_tree_polars      |     0.452098 |        5.27931 |   7.39821  |
| k-d_tree_pandas      |     0.460429 |        4.24317 |   7.89184  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.706567 |        84.0632 |    2.63796 |
| k-d_tree_sklearn     |     0.45693  |       274.835  |    3.27696 |
| Bori_Aron_solution-1 |     0.469438 |       163.091  |   18.2187  |