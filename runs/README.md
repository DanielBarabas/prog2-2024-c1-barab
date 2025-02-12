# 2025-02-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     3.86001  |       0.477623 |   0.401873 |
| k-d_tree_polars      |     0.581668 |       0.405148 |   0.4056   |
| barab-szabi-1        |     0.624156 |       0.403545 |   0.407005 |
| Bori_Aron_solution-1 |     4.57884  |       0.648263 |   0.469849 |
| k-d_tree_pandas      |     0.584929 |       0.381952 |   0.531572 |
| solution-1           |     7.26428  |       1e-06    |   0.645988 |
| k-d_tree_sklearn     |     3.06075  |       1.08684  |   1.01507  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587915 |       0.409615 |   0.408268 |
| k-d_tree_polars      |     0.583879 |       0.40688  |   0.413919 |
| barab-szabi-1        |     0.594908 |       0.459902 |   0.416456 |
| Bori_Aron_solution-1 |     0.580054 |       0.548216 |   0.533706 |
| k-d_tree_pandas      |     0.592599 |       0.393299 |   0.55363  |
| k-d_tree_sklearn     |     0.595963 |       0.952785 |   1.04055  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594608 |       0.421508 |   0.418635 |
| barab-szabi-1        |     0.601254 |       0.442298 |   0.440153 |
| k-d_tree_polars      |     0.588931 |       0.436316 |   0.441614 |
| Bori_Aron_solution-1 |     0.577761 |       0.582516 |   0.533284 |
| k-d_tree_pandas      |     0.583383 |       0.411132 |   0.600538 |
| k-d_tree_sklearn     |     0.597605 |       0.995605 |   1.06523  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586074 |       0.483953 |   0.443101 |
| k-d_tree_polars      |     0.583539 |       0.539096 |   0.534052 |
| barab-szabi-1        |     0.584224 |       0.540011 |   0.543468 |
| Bori_Aron_solution-1 |     0.581262 |       0.743227 |   0.551835 |
| k-d_tree_pandas      |     0.581877 |       0.480038 |   0.716776 |
| k-d_tree_sklearn     |     0.591624 |       1.2082   |   1.10539  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591746 |       0.727415 |   0.487452 |
| Bori_Aron_solution-1 |     0.591037 |       1.38187  |   0.582896 |
| k-d_tree_polars      |     0.593419 |       0.895922 |   0.895503 |
| barab-szabi-1        |     0.603278 |       0.873108 |   0.921637 |
| k-d_tree_pandas      |     0.58696  |       0.762655 |   1.22539  |
| k-d_tree_sklearn     |     0.588103 |       2.10884  |   1.22727  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.599532 |        5.5925  |   0.834953 |
| Bori_Aron_solution-1 |     0.589079 |       11.1763  |   0.898189 |
| k-d_tree_sklearn     |     0.592288 |       17.1937  |   1.39593  |
| barab-szabi-1        |     0.62299  |        5.08195 |   7.34796  |
| k-d_tree_polars      |     0.613812 |        5.04455 |   7.43184  |
| k-d_tree_pandas      |     0.61961  |        3.9502  |   8.05674  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.66254  |       243.52   |    4.17563 |
| barab-szabi-2        |     0.788757 |        78.5921 |    4.35722 |
| Bori_Aron_solution-1 |     0.593762 |       161.145  |   15.4874  |