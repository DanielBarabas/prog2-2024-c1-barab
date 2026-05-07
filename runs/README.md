# 2026-05-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470796 |       0.459508 |   0.455583 |
| barab-szabi-1        |     0.467161 |       0.435133 |   0.457966 |
| k-d_tree_polars      |     0.473737 |       0.432891 |   0.481115 |
| solution-1           |     8.5604   |       1e-06    |   0.50447  |
| k-d_tree_pandas      |     0.462554 |       0.404606 |   0.581547 |
| Bori_Aron_solution-1 |     0.563841 |       0.575894 |   0.58711  |
| k-d_tree_sklearn     |    11.1107   |       1.36622  |   1.13138  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462534 |       0.459139 |   0.450753 |
| k-d_tree_polars      |     0.455925 |       0.435536 |   0.451713 |
| barab-szabi-1        |     0.462096 |       0.429899 |   0.461653 |
| k-d_tree_pandas      |     0.461716 |       0.40601  |   0.576097 |
| Bori_Aron_solution-1 |     0.460628 |       0.581634 |   0.584768 |
| k-d_tree_sklearn     |     0.476319 |       1.04944  |   1.16983  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.445286 |       0.453622 |   0.4505   |
| k-d_tree_polars      |     0.455414 |       0.450517 |   0.471699 |
| barab-szabi-1        |     0.46237  |       0.458298 |   0.480111 |
| Bori_Aron_solution-1 |     0.46555  |       0.629193 |   0.577842 |
| k-d_tree_pandas      |     0.454797 |       0.420635 |   0.605286 |
| k-d_tree_sklearn     |     0.464244 |       1.0542   |   1.13489  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463656 |       0.520568 |   0.493644 |
| k-d_tree_polars      |     0.44943  |       0.573106 |   0.553383 |
| barab-szabi-1        |     0.457541 |       0.583673 |   0.569968 |
| Bori_Aron_solution-1 |     0.452599 |       0.776382 |   0.574883 |
| k-d_tree_pandas      |     0.463165 |       0.506774 |   0.738933 |
| k-d_tree_sklearn     |     0.465204 |       1.29758  |   1.17455  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.447173 |       0.753866 |   0.607967 |
| Bori_Aron_solution-1 |     0.458152 |       1.40963  |   0.622651 |
| k-d_tree_polars      |     0.449053 |       0.890492 |   0.903344 |
| barab-szabi-1        |     0.459132 |       0.889417 |   0.926356 |
| k-d_tree_pandas      |     0.446486 |       0.788875 |   1.15181  |
| k-d_tree_sklearn     |     0.457717 |       2.07901  |   1.22242  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.437438 |        5.17941 |   0.722156 |
| Bori_Aron_solution-1 |     0.448442 |       10.4556  |   0.911458 |
| k-d_tree_sklearn     |     0.451402 |       15.4965  |   1.3117   |
| k-d_tree_polars      |     0.445878 |        4.90666 |   6.5022   |
| barab-szabi-1        |     0.47145  |        4.98273 |   6.53764  |
| k-d_tree_pandas      |     0.447695 |        3.90052 |   6.97135  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.709588 |        71.8127 |    2.65331 |
| k-d_tree_sklearn     |     0.450835 |       188.347  |    3.99721 |
| Bori_Aron_solution-1 |     0.443586 |       139.065  |   28.7991  |