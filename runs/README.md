# 2025-10-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563562 |       0.438859 |   0.460057 |
| k-d_tree_polars      |     0.565696 |       0.425099 |   0.493141 |
| solution-1           |     8.77136  |       1e-06    |   0.550575 |
| Bori_Aron_solution-1 |     0.681973 |       0.555302 |   0.570786 |
| barab-szabi-1        |     0.559176 |       0.438607 |   0.642126 |
| k-d_tree_pandas      |     8.80538  |       0.437155 |   0.906799 |
| k-d_tree_sklearn     |     3.32926  |       1.17819  |   1.09904  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569158 |       0.447437 |   0.443868 |
| k-d_tree_polars      |     0.574354 |       0.450765 |   0.458578 |
| barab-szabi-1        |     0.563316 |       0.423646 |   0.470184 |
| Bori_Aron_solution-1 |     0.565988 |       0.589845 |   0.575028 |
| k-d_tree_pandas      |     0.58956  |       0.423498 |   0.607139 |
| k-d_tree_sklearn     |     0.572432 |       1.0461   |   1.09367  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56754  |       0.45854  |   0.445276 |
| k-d_tree_polars      |     0.552958 |       0.447536 |   0.463724 |
| barab-szabi-1        |     0.566058 |       0.448353 |   0.467457 |
| Bori_Aron_solution-1 |     0.544997 |       0.600724 |   0.561226 |
| k-d_tree_pandas      |     0.571784 |       0.429662 |   0.60848  |
| k-d_tree_sklearn     |     0.567734 |       1.0834   |   1.16114  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560186 |       0.520406 |   0.485063 |
| k-d_tree_polars      |     0.561054 |       0.569702 |   0.556985 |
| Bori_Aron_solution-1 |     0.556769 |       0.784759 |   0.568573 |
| barab-szabi-1        |     0.556367 |       0.576232 |   0.576778 |
| k-d_tree_pandas      |     0.560242 |       0.508892 |   0.740468 |
| k-d_tree_sklearn     |     0.560046 |       1.28558  |   1.16988  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567091 |       0.757746 |   0.543882 |
| Bori_Aron_solution-1 |     0.54515  |       1.42791  |   0.593858 |
| k-d_tree_polars      |     0.562883 |       0.940042 |   0.935638 |
| barab-szabi-1        |     0.55422  |       0.960938 |   0.958151 |
| k-d_tree_pandas      |     0.563998 |       0.820555 |   1.1818   |
| k-d_tree_sklearn     |     0.564911 |       2.15726  |   1.25129  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556196 |        5.56709 |   0.76083  |
| Bori_Aron_solution-1 |     0.580272 |       11.766   |   0.869793 |
| k-d_tree_sklearn     |     0.566217 |       18.0006  |   1.32828  |
| k-d_tree_polars      |     0.564545 |        5.57495 |   6.89504  |
| barab-szabi-1        |     0.587272 |        5.43398 |   7.28163  |
| k-d_tree_pandas      |     0.573181 |        4.43607 |   7.57486  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.783207 |         75.987 |    2.88255 |
| k-d_tree_sklearn     |     1.19285  |        247.147 |    4.24147 |
| Bori_Aron_solution-1 |     0.549849 |        157.409 |   14.2288  |