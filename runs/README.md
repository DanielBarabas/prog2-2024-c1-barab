# 2025-04-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.549714 |       0.395168 |   0.410523 |
| barab-szabi-2        |     0.548583 |       0.402711 |   0.422178 |
| barab-szabi-1        |     0.548055 |       0.414184 |   0.444245 |
| solution-1           |     7.2802   |       1e-06    |   0.44778  |
| Bori_Aron_solution-1 |     0.538644 |       0.534184 |   0.538194 |
| k-d_tree_pandas      |     7.58227  |       0.429941 |   0.655899 |
| k-d_tree_sklearn     |     3.0024   |       1.07181  |   1.01549  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555536 |       0.421662 |   0.406297 |
| barab-szabi-1        |     0.55467  |       0.407534 |   0.410077 |
| k-d_tree_polars      |     0.561729 |       0.404424 |   0.411928 |
| Bori_Aron_solution-1 |     0.552815 |       0.539448 |   0.537788 |
| k-d_tree_pandas      |     0.597811 |       0.390579 |   0.553192 |
| k-d_tree_sklearn     |     0.562459 |       0.939073 |   1.01544  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55705  |       0.427119 |   0.419885 |
| barab-szabi-1        |     0.578763 |       0.430915 |   0.434443 |
| k-d_tree_polars      |     0.555558 |       0.439423 |   0.440782 |
| Bori_Aron_solution-1 |     0.552852 |       0.585841 |   0.542712 |
| k-d_tree_pandas      |     0.55762  |       0.40012  |   0.594965 |
| k-d_tree_sklearn     |     0.562231 |       0.987653 |   1.04204  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558843 |       0.480899 |   0.444114 |
| k-d_tree_polars      |     0.557129 |       0.536315 |   0.540371 |
| barab-szabi-1        |     0.561455 |       0.539733 |   0.542541 |
| Bori_Aron_solution-1 |     0.552364 |       0.755163 |   0.554603 |
| k-d_tree_pandas      |     0.558783 |       0.478802 |   0.726552 |
| k-d_tree_sklearn     |     0.562483 |       1.20919  |   1.09868  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561065 |       0.728543 |   0.479637 |
| Bori_Aron_solution-1 |     0.550887 |       1.42409  |   0.594033 |
| k-d_tree_polars      |     0.583721 |       0.884366 |   0.878766 |
| barab-szabi-1        |     0.576092 |       0.905777 |   0.974923 |
| k-d_tree_pandas      |     0.582122 |       0.755459 |   1.16681  |
| k-d_tree_sklearn     |     0.567987 |       2.0389   |   1.19915  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566256 |        5.30202 |   0.714604 |
| Bori_Aron_solution-1 |     0.551711 |       10.6544  |   0.867358 |
| k-d_tree_sklearn     |     0.567165 |       15.7283  |   1.31869  |
| k-d_tree_polars      |     0.560387 |        5.02692 |   6.52029  |
| barab-szabi-1        |     0.557368 |        4.97802 |   6.54482  |
| k-d_tree_pandas      |     0.564077 |        3.97123 |   6.95593  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.786821 |        69.9502 |    3.10513 |
| k-d_tree_sklearn     |     0.63035  |       226.759  |    4.10662 |
| Bori_Aron_solution-1 |     0.550179 |       156.54   |   15.2787  |