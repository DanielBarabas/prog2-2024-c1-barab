# 2025-09-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551129 |       0.575318 |   0.429122 |
| k-d_tree_polars      |     0.562004 |       0.426921 |   0.435026 |
| barab-szabi-1        |     0.553981 |       0.426859 |   0.436886 |
| solution-1           |     7.89301  |       1e-06    |   0.540414 |
| Bori_Aron_solution-1 |     0.555966 |       0.567853 |   0.577103 |
| k-d_tree_pandas      |     8.49197  |       0.443763 |   0.787763 |
| k-d_tree_sklearn     |     3.34484  |       1.24427  |   1.1012   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561908 |       0.451133 |   0.440106 |
| barab-szabi-1        |     0.55876  |       0.429473 |   0.44946  |
| k-d_tree_polars      |     0.569943 |       0.429684 |   0.456852 |
| k-d_tree_pandas      |     0.557994 |       0.406499 |   0.58788  |
| Bori_Aron_solution-1 |     0.552986 |       0.617479 |   0.603681 |
| k-d_tree_sklearn     |     0.565079 |       1.02725  |   1.13746  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.592359 |       0.462727 |   0.470677 |
| barab-szabi-2        |     0.558165 |       0.467615 |   0.47389  |
| barab-szabi-1        |     0.593107 |       0.484624 |   0.508918 |
| Bori_Aron_solution-1 |     0.577494 |       0.637031 |   0.606303 |
| k-d_tree_pandas      |     0.588988 |       0.443115 |   0.635921 |
| k-d_tree_sklearn     |     0.574304 |       1.07559  |   1.17702  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580715 |       0.515393 |   0.480956 |
| k-d_tree_polars      |     0.566113 |       0.558001 |   0.569061 |
| Bori_Aron_solution-1 |     0.54429  |       0.779779 |   0.576812 |
| barab-szabi-1        |     0.571754 |       0.560059 |   0.587034 |
| k-d_tree_pandas      |     0.567614 |       0.500894 |   0.765996 |
| k-d_tree_sklearn     |     0.560629 |       1.27112  |   1.17863  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554701 |       0.787605 |   0.548575 |
| Bori_Aron_solution-1 |     0.554636 |       1.43014  |   0.603638 |
| k-d_tree_polars      |     0.552807 |       0.89945  |   0.917806 |
| barab-szabi-1        |     0.562221 |       0.898338 |   0.971614 |
| k-d_tree_pandas      |     0.551582 |       0.778598 |   1.2122   |
| k-d_tree_sklearn     |     0.573895 |       2.24532  |   1.26416  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550496 |        5.41235 |   0.746388 |
| Bori_Aron_solution-1 |     0.542088 |       10.7522  |   0.860814 |
| k-d_tree_sklearn     |     0.563367 |       16.5895  |   1.33797  |
| barab-szabi-1        |     0.593138 |        5.04669 |   6.67944  |
| k-d_tree_polars      |     0.553173 |        5.01985 |   6.7188   |
| k-d_tree_pandas      |     0.552012 |        3.93025 |   7.12795  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556075 |        72.6002 |    2.67441 |
| k-d_tree_sklearn     |     0.558162 |       234.924  |    4.1864  |
| Bori_Aron_solution-1 |     0.783684 |       142.571  |   16.9646  |