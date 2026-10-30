# 2026-10-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.65419  |       1e-06    |   0.363846 |
| k-d_tree_polars      |     0.488762 |       0.436001 |   0.450568 |
| barab-szabi-2        |     0.484406 |       0.457423 |   0.452713 |
| barab-szabi-1        |     8.66162  |       0.470527 |   0.501732 |
| Bori_Aron_solution-1 |     0.495952 |       0.586325 |   0.577051 |
| k-d_tree_pandas      |     0.491943 |       0.409717 |   0.580546 |
| k-d_tree_sklearn     |     3.19009  |       1.09021  |   1.11916  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.486066 |       0.443571 |   0.447979 |
| barab-szabi-2        |     0.495319 |       0.453405 |   0.449592 |
| barab-szabi-1        |     0.496033 |       0.459095 |   0.476703 |
| Bori_Aron_solution-1 |     0.480475 |       0.577528 |   0.554659 |
| k-d_tree_pandas      |     0.502184 |       0.419574 |   0.576233 |
| k-d_tree_sklearn     |     0.495692 |       1.06067  |   1.12832  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490548 |       0.477106 |   0.465434 |
| k-d_tree_polars      |     0.489004 |       0.480906 |   0.476156 |
| barab-szabi-1        |     0.484667 |       0.476414 |   0.495803 |
| Bori_Aron_solution-1 |     0.480928 |       0.618015 |   0.571116 |
| k-d_tree_pandas      |     0.504936 |       0.442313 |   0.628489 |
| k-d_tree_sklearn     |     0.49808  |       1.1007   |   1.2759   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498423 |       0.548845 |   0.48226  |
| k-d_tree_polars      |     0.490113 |       0.592937 |   0.576043 |
| Bori_Aron_solution-1 |     0.488298 |       0.797626 |   0.596958 |
| barab-szabi-1        |     0.489092 |       0.645048 |   0.618118 |
| k-d_tree_pandas      |     0.490846 |       0.532477 |   0.765802 |
| k-d_tree_sklearn     |     0.502613 |       1.33057  |   1.21066  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480141 |       0.802588 |   0.599168 |
| Bori_Aron_solution-1 |     0.472127 |       1.50776  |   0.6378   |
| k-d_tree_polars      |     0.47712  |       0.9511   |   0.957415 |
| barab-szabi-1        |     0.483033 |       0.941803 |   1.00703  |
| k-d_tree_pandas      |     0.485189 |       0.835248 |   1.22866  |
| k-d_tree_sklearn     |     0.502404 |       2.1661   |   1.27041  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471972 |        5.79283 |   0.933142 |
| Bori_Aron_solution-1 |     0.480486 |       11.7958  |   1.15003  |
| k-d_tree_sklearn     |     0.485534 |       17.36    |   1.40411  |
| k-d_tree_polars      |     0.478812 |        5.33025 |   7.29738  |
| barab-szabi-1        |     0.478015 |        5.29253 |   7.42288  |
| k-d_tree_pandas      |     0.496687 |        4.4105  |   7.85518  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.484964 |       249.183  |    4.31725 |
| barab-szabi-2        |     0.484091 |        82.2768 |    4.64283 |
| Bori_Aron_solution-1 |     0.471911 |       163.188  |   24.6151  |