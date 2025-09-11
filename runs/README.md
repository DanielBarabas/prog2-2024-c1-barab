# 2025-09-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.85198  |       0.880995 |   0.436569 |
| barab-szabi-1        |     0.543997 |       0.421597 |   0.447622 |
| k-d_tree_polars      |     0.546447 |       0.41876  |   0.452905 |
| solution-1           |     7.47305  |       1e-06    |   0.556198 |
| k-d_tree_pandas      |     0.547214 |       0.402771 |   0.564683 |
| Bori_Aron_solution-1 |     0.527917 |       0.571352 |   0.610163 |
| k-d_tree_sklearn     |     3.32221  |       1.21894  |   1.09203  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.55962  |       0.427173 |   0.440576 |
| k-d_tree_polars      |     0.551652 |       0.423031 |   0.4412   |
| barab-szabi-2        |     0.555114 |       0.438873 |   0.442543 |
| Bori_Aron_solution-1 |     0.546415 |       0.570258 |   0.564482 |
| k-d_tree_pandas      |     0.565357 |       0.407574 |   0.585835 |
| k-d_tree_sklearn     |     0.561377 |       1.01678  |   1.08748  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562214 |       0.445643 |   0.457847 |
| k-d_tree_polars      |     0.567678 |       0.447105 |   0.458946 |
| barab-szabi-1        |     0.553902 |       0.445953 |   0.472254 |
| Bori_Aron_solution-1 |     0.554455 |       0.603671 |   0.570881 |
| k-d_tree_pandas      |     0.555461 |       0.42829  |   0.634268 |
| k-d_tree_sklearn     |     0.569201 |       1.04655  |   1.13278  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55092  |       0.510009 |   0.477896 |
| k-d_tree_polars      |     0.559255 |       0.560439 |   0.561353 |
| barab-szabi-1        |     0.555082 |       0.563886 |   0.576736 |
| Bori_Aron_solution-1 |     0.546006 |       0.77985  |   0.596713 |
| k-d_tree_pandas      |     0.553887 |       0.497761 |   0.751157 |
| k-d_tree_sklearn     |     0.561789 |       1.29662  |   1.17216  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549385 |       0.786074 |   0.548871 |
| Bori_Aron_solution-1 |     0.546096 |       1.45699  |   0.610882 |
| k-d_tree_polars      |     0.560022 |       0.909285 |   0.98042  |
| barab-szabi-1        |     0.572831 |       0.911585 |   1.01048  |
| k-d_tree_pandas      |     0.562819 |       0.772967 |   1.21392  |
| k-d_tree_sklearn     |     0.570053 |       2.23569  |   1.28534  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561872 |        5.8326  |   0.745666 |
| Bori_Aron_solution-1 |     0.547685 |       10.9713  |   0.857399 |
| k-d_tree_sklearn     |     0.559165 |       17.5781  |   1.38301  |
| barab-szabi-1        |     0.554303 |        5.04166 |   7.19064  |
| k-d_tree_polars      |     0.567302 |        5.07447 |   7.5095   |
| k-d_tree_pandas      |     0.554192 |        3.95717 |   7.72101  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554141 |        78.5694 |    2.82188 |
| k-d_tree_sklearn     |     1.08896  |       243.063  |    4.0942  |
| Bori_Aron_solution-1 |     0.550684 |       142.476  |   17.7336  |