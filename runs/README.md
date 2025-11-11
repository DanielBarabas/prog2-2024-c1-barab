# 2025-11-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.530433 |       0.407349 |   0.433472 |
| barab-szabi-1        |     0.533912 |       0.41055  |   0.438513 |
| barab-szabi-2        |     0.524279 |       0.499606 |   0.450291 |
| solution-1           |     8.33767  |       1e-06    |   0.475155 |
| Bori_Aron_solution-1 |     0.538225 |       0.565399 |   0.551735 |
| k-d_tree_pandas      |    30.0077   |       0.426164 |   0.67314  |
| k-d_tree_sklearn     |     3.5016   |       1.12933  |   1.07498  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542801 |       0.444802 |   0.429867 |
| barab-szabi-1        |     0.548771 |       0.417704 |   0.445982 |
| k-d_tree_polars      |     0.553272 |       0.428728 |   0.45148  |
| Bori_Aron_solution-1 |     0.538658 |       0.573579 |   0.550365 |
| k-d_tree_pandas      |     0.536656 |       0.397777 |   0.569086 |
| k-d_tree_sklearn     |     0.542204 |       1.00082  |   1.09549  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539006 |       0.453666 |   0.454009 |
| barab-szabi-1        |     0.86024  |       0.445528 |   0.469586 |
| k-d_tree_polars      |     0.53088  |       0.439712 |   0.477607 |
| Bori_Aron_solution-1 |     0.546062 |       0.60733  |   0.559438 |
| k-d_tree_pandas      |     0.535443 |       0.418626 |   0.616179 |
| k-d_tree_sklearn     |     0.537524 |       1.03377  |   1.13236  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550319 |       0.511063 |   0.481726 |
| k-d_tree_polars      |     0.53798  |       0.570955 |   0.555914 |
| barab-szabi-1        |     0.53924  |       0.57523  |   0.570735 |
| Bori_Aron_solution-1 |     0.527374 |       0.789835 |   0.598696 |
| k-d_tree_pandas      |     0.535991 |       0.511583 |   0.74969  |
| k-d_tree_sklearn     |     0.537562 |       1.27443  |   1.16837  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531492 |       0.754296 |   0.534929 |
| Bori_Aron_solution-1 |     0.524005 |       1.48453  |   0.592476 |
| k-d_tree_polars      |     0.546679 |       0.939682 |   0.915851 |
| barab-szabi-1        |     0.543133 |       0.948698 |   0.976058 |
| k-d_tree_pandas      |     0.551565 |       0.826111 |   1.19728  |
| k-d_tree_sklearn     |     0.548505 |       2.17621  |   1.28152  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532513 |        5.52043 |   0.777086 |
| Bori_Aron_solution-1 |     0.53088  |       11.6304  |   0.853385 |
| k-d_tree_sklearn     |     0.539802 |       17.8347  |   1.35725  |
| k-d_tree_polars      |     0.540356 |        5.36156 |   6.80998  |
| barab-szabi-1        |     0.545368 |        5.4853  |   6.91211  |
| k-d_tree_pandas      |     0.533877 |        4.46976 |   7.1927   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533368 |        74.2713 |    2.92644 |
| k-d_tree_sklearn     |     0.548294 |       240.217  |    4.16029 |
| Bori_Aron_solution-1 |     0.637196 |       149.81   |   17.6774  |